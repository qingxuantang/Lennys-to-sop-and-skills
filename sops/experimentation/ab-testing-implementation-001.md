# A/B Testing Implementation and Best Practices

## Metadata
- **Source**: Ronny Kohavi - Lenny's Podcast
- **Domain**: Experimentation / Data
- **Type**: Process SOP
- **Applicable To**: Product Managers, Growth Teams, Data Scientists, Engineering
- **Company Stage**: Series A+ (requires ~200K users minimum)
- **Difficulty**: Intermediate to Advanced

## Overview
This SOP provides a comprehensive guide to implementing trustworthy A/B testing based on learnings from Microsoft, Amazon, and Airbnb. It covers when to start, how to build culture, common pitfalls, and how to interpret results correctly.

## When to Use
- Ready to implement experimentation at your company
- Want to improve existing experiment rigor
- Need to build experimentation culture
- Questioning validity of current experiments
- Evaluating build vs. buy for experimentation platform

## Prerequisites
- Minimum ~10,000 users (basic experiments)
- Ideal: 200,000+ users (detect 5%+ effects reliably)
- Analytics infrastructure in place
- Clear product metrics defined
- Engineering capacity to implement

## Procedure

### Step 1: Determine Readiness

**User threshold requirements:**
- 10,000+ users: Can detect only large effects (10%+)
- 200,000+ users: Magic threshold - can detect 5% effects, run multiple tests
- Below 10,000: Statistics don't work; use qualitative methods instead

**Questions to answer:**
- Do we have enough traffic?
- Do we deploy frequently (weekly+)?
- Can we define what we're optimizing for?

### Step 2: Define Your Overall Evaluation Criterion (OEC)

**Critical**: Don't just optimize for revenue - you need countervailing metrics.

**OEC should be:**
- Causally predictive of lifetime value
- Include both business AND user experience metrics
- Have clear directional agreement (everyone agrees up = good)

**Components:**
1. **Primary metric**: What you're trying to improve (revenue, conversion)
2. **Guardrail metrics**: What you must not hurt (user experience, engagement)
3. **Debug metrics**: Help diagnose issues

**Example OEC structure:**
- Revenue: Maximize (but constrained)
- User experience metrics: Time to successful action, success rate
- Constraint: Fixed ad pixel budget per session

### Step 3: Implement Sample Ratio Mismatch (SRM) Check

**Most important validity check**: If you design 50/50 split, you should GET 50/50.

**What to do:**
1. Compute expected vs. actual ratio
2. Calculate statistical probability of observed difference
3. If probability < 1/10,000 → something is wrong

**Common SRM causes:**
- Bot traffic hitting variants differently
- Data pipeline issues
- Mid-experiment assignment problems
- External traffic sources

**Action**: If SRM detected, DO NOT trust results. Investigate first.

### Step 4: Set Appropriate P-Value Thresholds

**Standard p < 0.05 is NOT what you think:**

**Reality check:**
- If 8% of experiments succeed (like Airbnb search)
- And you use p < 0.05
- Your false positive rate is actually ~26%

**Recommendations:**
- p < 0.01 for single experiment launches
- p < 0.05 but > 0.01: Replicate the experiment
- Use Fisher's method to combine replicated experiments
- Adjust thresholds based on your historical success rate

### Step 5: Establish Experiment Review Process

**Before launch:**
- Hypothesis clearly stated
- Expected effect size documented
- OEC and metrics defined
- Sample size calculation done
- Experiment duration planned

**During experiment:**
- Monitor for SRM daily
- Check guardrail metrics
- Look for anomalies

**After experiment:**
- Full scorecard review
- Comparison to hypothesis
- Learning documentation

### Step 6: Build Institutional Memory

**Create documentation:**
- Searchable experiment history
- Quarterly "most surprising results" review
- Success AND failure case studies

**Surprising = where estimate ≠ actual:**
- Expected big, got flat → learn why
- Expected small, got big → understand mechanism
- Expected positive, got negative → crucial insight

**Resource**: goodui.org catalogues patterns that work across companies

### Step 7: Avoid Common Pitfalls

**Don't run big redesigns without iteration:**
- 80% of major redesigns fail
- Decompose into smaller testable changes
- "17 changes together" → mostly negative
- Test incrementally, learn, adjust

**Don't ignore flat results:**
- Flat = no ship (code complexity cost)
- Exception: Legal requirements
- Even legal: Test 3 versions, ship least negative

**Don't celebrate too early (Twyman's Law):**
- "If any figure looks interesting or different, it is usually wrong"
- 9/10 times amazing results have bugs
- Hold celebratory dinner until verified

### Step 8: Apply Variance Reduction Techniques

**To get results faster:**

1. **Cap outliers**: Limit extreme values (e.g., nights booked capped at 30)
2. **Use pre-experiment data**: CUPED technique uses historical data to reduce variance
3. **Focus on high-variance opportunities**: 5-10% effects, not 1%

### Step 9: Build vs. Buy Decision

**Buy (third-party platform) when:**
- Starting out
- Limited engineering resources
- Need to ship quickly
- Standard use cases

**Build when:**
- Need deep customization
- Running thousands of experiments/year
- Marginal cost needs to approach zero
- Complex OEC calculations

**Reality**: Usually a mix - buy foundation, build custom layers

### Step 10: Create Culture of Experimentation

**Techniques that work:**
- Share surprising results broadly
- Celebrate learnings, not just wins
- Executive support (air cover)
- Start with one willing team, expand via success stories

**Kill resistance by:**
- Showing their peers' surprising failures
- Demonstrating counterfactual value
- Moving people between teams who've seen the light

## Expected Outcomes
- 8-20% experiment success rate (normal!)
- Reduced shipping of negative changes
- Institutional learning accumulation
- Data-driven decision making
- Compounding small improvements (2%/year = massive over time)

## Common Pitfalls

### Thinking "we have better PMs"
- Every org thinks they're different
- You're not - expect 66-90% failure rate

### Real-time p-value monitoring
- Inflates false positive rate from 5% to ~30%
- Set duration upfront, don't peek

### Launching on flat
- Adds code complexity
- No value delivered
- Maintenance cost forever

### Ignoring SRM
- 8% of experiments have SRM issues
- Results are invalid if SRM present

## Related SOPs
- OEC Definition Framework
- Experiment Documentation Template
- Statistical Significance Guidelines

## AI Integration Notes

### Context signals that should trigger this SOP:
- User mentions "A/B testing," "experimentation"
- Questions about statistical significance
- Discussions of experiment validity
- Building experimentation culture

### How to adapt:
- For small companies (<200K users): Focus on qualitative methods
- For mature platforms: Focus on advanced techniques (CUPED, OEC refinement)
- For resistant orgs: Focus on culture change tactics

### Key numbers to remember:
- 200K users = threshold for reliable experiments
- 66-90% = normal failure rate
- 8% = typical SRM issue rate
- p < 0.01 = safer threshold than 0.05
