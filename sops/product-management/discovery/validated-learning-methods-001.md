# Validated Learning Methods

## Metadata
- **Source**: Eric Ries - Lenny's Podcast
- **Domain**: Product Management / Discovery
- **Type**: Framework SOP
- **Applicable To**: Product Managers, Founders, Product Teams, Growth Teams
- **Company Stage**: All stages (especially pre-PMF)
- **Difficulty**: Intermediate

## Overview
Validated learning is the process of demonstrating empirically that a team has discovered valuable truths about a startup's present and future business prospects. It is learning backed by empirical data from real customers, not opinions or assumptions. This SOP provides methods to ensure your team is actually learning (changing behavior based on evidence) rather than just collecting data or confirming biases.

## When to Use
- Before committing to major product decisions
- When team debates about what customers want
- To justify resource allocation
- When distinguishing between customer opinions and behavior
- To prevent building features nobody wants
- When measuring progress in uncertain environments
- To create accountability for learning vs. just shipping

## Prerequisites
- Willingness to admit what you don't know
- Access to customers or users
- Ability to run experiments
- Culture that rewards learning over being right
- Understanding that invalidating assumptions is progress
- Commitment to changing direction based on evidence

## Core Principle: Learning Over Building

**Traditional approach:**
```
Build → Launch → Hope it works → Success or failure
```

**Validated learning approach:**
```
Hypothesis → Experiment → Measure → Learn → Decide → Repeat
```

**The fundamental shift**: Progress is measured by validated learning, not by features shipped or lines of code written.

## Types of Validated Learning

### 1. Problem Validation
**What you're learning**: Does this problem exist and matter to customers?

**Methods:**
- Customer interviews about past behavior
- Observation of current workflows
- Analysis of existing solutions they use
- Quantifying pain (time, money, frustration)

**Validation criteria:**
- Can articulate problem in customer's own words
- Customer has tried to solve it before
- They're actively searching for solutions
- Willing to pay or change behavior to solve it

### 2. Solution Validation
**What you're learning**: Does our solution actually solve the problem?

**Methods:**
- Prototype testing
- Concierge MVP (manually deliver the solution)
- Wizard of Oz (automated front-end, manual back-end)
- Beta programs with real usage

**Validation criteria:**
- Customers successfully complete desired action
- They return to use it again
- They prefer it to alternatives
- Measurable improvement in their outcome

### 3. Value Proposition Validation
**What you're learning**: Do customers understand and care about our unique value?

**Methods:**
- Landing page tests
- Message testing with cohorts
- Pitch tests with various positioning
- Comparison to how customers describe it

**Validation criteria:**
- Customers can explain what it does in their words
- They see it as different from alternatives
- The differentiation matters to them
- They can identify who it's for

### 4. Willingness to Pay Validation
**What you're learning**: Will customers actually pay what we need to charge?

**Methods:**
- Pre-orders before building
- Fake door pricing tests
- Payment during beta
- Pricing surveys (least reliable)

**Validation criteria:**
- Actual payment, not stated intent
- At scale needed for business model
- With acceptable acquisition cost
- Retention at that price point

### 5. Channel Validation
**What you're learning**: Can we reach customers efficiently through this channel?

**Methods:**
- Small-scale channel tests
- Cost per acquisition measurement
- Conversion rate by channel
- Cohort analysis by source

**Validation criteria:**
- Sustainable acquisition cost
- Scalable volume
- Quality of customers acquired
- Repeatability and consistency

## Procedure

### Step 1: Distinguish Opinions from Evidence

**The problem**: People say what they think, not what they'll do.

**Unreliable sources (opinions):**
- "I would definitely use this"
- "I would pay $X for this"
- "This is a great idea"
- "You should add feature Y"

**Reliable sources (evidence):**
- Past behavior
- Actual usage
- Real payments
- Retention data
- Time investment

**Rule**: "What customers do > what customers say"

**Practice**:
- In customer interviews, ask about past behavior, not future intent
- "Tell me about the last time you tried to solve this problem"
- NOT "Would you use a product that does X?"

### Step 2: Make Hypotheses Explicit and Falsifiable

**Framework for good hypotheses:**

**Format**: "We believe [target customers] will [measurable action] because [reason]"

**Example**:
- Bad: "Users want better analytics"
- Good: "We believe marketing managers will export reports at least weekly because they currently spend 4+ hours manually creating them in spreadsheets"

**Make it falsifiable:**
- Define what would prove it wrong
- Set specific thresholds
- Time-bound the test
- Predetermined decision criteria

**Test your hypothesis:**
- Can someone disagree with it? (If not, it's not a hypothesis)
- Can you measure the outcome? (If not, make it more specific)
- Do you know what data would prove it wrong? (If not, define it)

### Step 3: Design Experiments That Generate Learning

**Characteristics of good experiments:**

**1. Minimal viable scope**
- Test one variable at a time when possible
- Smallest group size that gives signal
- Shortest time period that shows pattern
- Cheapest implementation that generates data

**2. Clear success criteria set upfront**
- Numerical thresholds
- Written before running experiment
- Agreed upon by team
- Include both success and failure definitions

**From Eric**: "From one experiment you can never know. You have to be willing to do a series of experiments."

**3. Actual customer behavior**
- Real people, not friends/family
- Real money when testing willingness to pay
- Real usage patterns, not demo scenarios
- Real competitive context

**4. Comparative structure**
- A/B test when possible
- Before/after measurement
- Cohort comparison
- Benchmark against alternatives

### Step 4: Collect the Right Data

**Actionable metrics vs. Vanity metrics:**

**Vanity metrics** (misleading):
- Total users (obscures retention)
- Page views (doesn't show value)
- Social media followers (not activation)
- Download counts (not usage)

**Actionable metrics** (guide decisions):
- Activation rate (% completing core action)
- Retention curves by cohort
- Revenue per customer
- Net Promoter Score with follow-up
- Time to value
- Feature adoption rate
- Churn rate and reasons

**Data collection principles:**

**Use cohort analysis:**
- Compare Week 1 users vs. Week 2 users
- Isolates product changes from user acquisition changes
- Shows true retention patterns
- Reveals improving or declining metrics

**Track complete funnels:**
- Acquisition → Activation → Retention → Revenue → Referral
- Find where users drop off
- Measure each step
- Compare cohorts at each step

**Qualitative + Quantitative:**
- Numbers show what happened
- Interviews show why
- Combine for complete picture

### Step 5: Analyze for Actual Insight

**Move beyond reporting to learning:**

**Level 1: Reporting** (not learning)
- "We got 100 signups"
- "Engagement is up 5%"
- "Users like feature X"

**Level 2: Analysis** (getting closer)
- "Week 2 cohort retained 10% better than Week 1"
- "Users who complete onboarding have 3x retention"
- "Enterprise customers pay 5x more than SMB"

**Level 3: Insight** (actual learning)
- "Changing onboarding from 5 steps to 2 increased completion by 40%, and those users have 2x retention → we should simplify all user flows"
- "Users coming from Partner channel have both higher LTV and lower CAC → we should focus BD efforts on similar partnerships"
- "Feature X drives engagement but not retention → it's not solving the core problem, we should pivot to what retained users actually use"

**Test if you've learned:**
- Can you articulate what you believed before vs. after?
- Did you change your behavior based on the data?
- Can you predict what will happen in the next experiment?
- Would you make different decisions based on this?

### Step 6: Document and Share Learnings

**Why documentation matters:**
- Prevents repeating failed experiments
- Builds institutional knowledge
- Enables pattern recognition
- Creates accountability

**What to document:**

**For each experiment:**
1. Hypothesis tested
2. Method used
3. Success criteria
4. Actual results
5. Insight gained
6. Decision made
7. Next experiment

**Learning repository:**
- Central location accessible to team
- Searchable by topic/hypothesis
- Updated regularly
- Referenced in planning

**Sharing format:**
- Weekly learning summaries
- Experiment readouts
- "What we learned this sprint"
- Pivot/persevere decision logs

### Step 7: Act on Learnings (Close the Loop)

**The test of validated learning: Did you change behavior?**

**After each experiment, you should:**

**Change something:**
- Modify product direction
- Adjust target customer
- Revise value proposition
- Update pricing
- Shift resources
- Kill a feature
- Double down on what works

**Or explicitly decide to persevere:**
- Document why you're staying course
- Set next validation milestone
- Define what would change your mind

**Red flags you're not learning:**
- Same strategy despite failed experiments
- "One more test" repeatedly
- Data ignored when inconvenient
- Confirmation bias in interpretation
- No changes after experiments

**Green flags you ARE learning:**
- Clear pivots based on data
- Experiments get more targeted over time
- Can predict outcomes better
- Failed experiments celebrated as learning
- Team references past experiments in decisions

### Step 8: Create a Learning Culture

**Psychological safety for learning:**

**From Eric**: "If you set yourself up in a position where psychologically you can't admit that something didn't work, you can't learn."

**Build a culture where:**
- Invalidated hypotheses are wins (you learned!)
- "I don't know" is acceptable and encouraged
- Changing your mind based on data is celebrated
- Failed experiments earn same recognition as successful ones
- Learning velocity is a team metric

**Anti-patterns to avoid:**
- Punishing "failed" experiments
- Only celebrating positive results
- Leaders who won't change their minds
- HiPPO (Highest Paid Person's Opinion) decision-making
- Confirmation bias in experiment design

**Leadership behaviors:**
- Publicly change your mind based on data
- Reward teams for discovering what doesn't work
- Ask "what did we learn?" not "did it work?"
- Share your own invalidated hypotheses
- Celebrate pivots, not just perseverance

## Expected Outcomes
- Decisions based on evidence, not opinions
- Faster discovery of what works/doesn't
- Reduced waste (less building of unused features)
- Team alignment around learnings
- Increased confidence in product direction
- Better predictions about future experiments
- Institutional knowledge that persists beyond individuals
- Culture of intellectual honesty

## Common Pitfalls

### Confusing data collection with learning
- **Problem**: Tracking metrics but not changing behavior
- **Solution**: Every experiment must lead to a decision or direction change
- **Test**: What did you do differently after your last experiment?

### Confirmation bias in experiment design
- **Problem**: Designing experiments to prove what you want to believe
- **Solution**: Define failure criteria as clearly as success criteria
- **Test**: What would prove you wrong? Write it down first.

### Relying on stated intent instead of behavior
- **Problem**: Surveys asking "would you pay $X?" instead of actually charging
- **Solution**: Test with real behavior whenever possible
- **Quote**: "What customers do > what customers say"

### Running one experiment and drawing conclusions
- **Problem**: Single A/B test determines product direction
- **Solution**: Series of experiments, look for patterns
- **From Eric**: "From one experiment you can never know. You have to be willing to do a series of experiments."

### Vanity metrics over actionable metrics
- **Problem**: Celebrating total users while ignoring retention
- **Solution**: Focus on cohort-based, actionable metrics
- **Test**: Does this metric tell you what to do next?

### Not documenting learnings
- **Problem**: Team forgets past experiments, repeats mistakes
- **Solution**: Central learning repository, updated after each experiment
- **Test**: Can new team member find past learnings?

### Learning but not acting
- **Problem**: "Interesting results" filed away, no change in direction
- **Solution**: Pre-commit to actions based on experiment outcomes
- **Test**: Did you actually change something based on last experiment?

### Psychological inability to admit failure
- **Problem**: Can't acknowledge when hypothesis is invalidated
- **Solution**: Reframe invalidation as progress and learning
- **Culture shift**: Celebrate "we learned it doesn't work" as much as "it worked"

### Analysis paralysis
- **Problem**: Need more data before any decision
- **Solution**: Define minimum viable data for decision, then decide
- **Test**: What's the smallest experiment that would change your mind?

### Not making hypotheses falsifiable
- **Problem**: Vague assumptions that can't be tested
- **Solution**: Specific, measurable, time-bound hypotheses
- **Test**: Could this hypothesis be proven wrong? How?

## Related SOPs
- Build-Measure-Learn Loop Framework
- Lean Startup MVP Development Process
- Pivot vs. Persevere Decision Framework
- Customer Interview Techniques
- A/B Testing Implementation
- Cohort Analysis Methods

## AI Integration Notes

### Context signals that should trigger this SOP:
- User mentions "testing," "validation," "experiments"
- Questions about "how do we know," "should we build this"
- Debates about customer needs
- Requests for decision-making frameworks
- Need to justify product decisions
- Discussion of metrics or analytics

### How to adapt for different situations:

**B2C products:**
- Higher volume enables quantitative testing
- Can run more experiments faster
- A/B testing highly viable
- Behavioral data more available
- Less deep qualitative per user

**B2B products:**
- Lower volume, more qualitative
- Each customer interaction more valuable
- Longer sales cycles
- More upfront customer development
- Case studies and references critical

**Pre-product:**
- Focus on problem and solution validation
- More qualitative methods
- Customer interviews primary
- Cheap, fast experiments
- High tolerance for pivots

**Growth stage:**
- Optimization over exploration
- More quantitative methods
- Larger sample sizes
- A/B testing infrastructure
- Incremental improvements

**Technical products:**
- Can test feasibility early
- Performance benchmarks
- Technical validation critical
- Developer-as-customer insights

### Key questions to ask users:
1. "What hypothesis are you testing?"
2. "What would prove that wrong?"
3. "Are you measuring what customers do or what they say?"
4. "What did you learn from your last experiment?"
5. "How did that change what you're doing?"
6. "What's the minimum data you need to decide?"

### Limitations and edge cases:
- Some decisions can't be tested incrementally (regulatory, security)
- Network effects require scale (can sometimes fake it)
- Long sales cycles make iteration slow (use proxies)
- Ethical constraints on some experiments
- Small markets may lack statistical power (use qualitative)

### The meta-lesson:
Validated learning is fundamentally about intellectual honesty and scientific thinking applied to business. It's not about being right; it's about discovering the truth as quickly and cheaply as possible. The companies that learn fastest win.

## Validated Learning Checklist

Before claiming you've "validated" something, check:

- [ ] Tested with real customers (not friends/family/colleagues)
- [ ] Observed actual behavior (not stated intent)
- [ ] Involved money changing hands (if testing willingness to pay)
- [ ] Used cohort analysis (not just totals)
- [ ] Ran multiple experiments (not just one)
- [ ] Had pre-defined success criteria
- [ ] Documented the learning
- [ ] Changed your behavior based on results
- [ ] Can articulate what you believed before vs. after
- [ ] Would make different decisions based on this learning

**If you can't check most of these, you've collected data but haven't validated learning.**
