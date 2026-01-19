# Utility Curve Product Investment Framework

## Metadata
- **Source**: Stewart Butterfield - Lenny's Podcast
- **Domain**: Product Management / Strategy
- **Type**: Framework
- **Applicable To**: Product Managers, Product Leaders, Founders (All stages)
- **Difficulty**: Intermediate

## Overview
A mental model for understanding where to invest product development resources by visualizing features along an S-curve of utility vs. effort. This framework helps teams determine whether a feature needs more investment to reach the critical "usable" threshold, is at peak value extraction, or has passed into diminishing returns—preventing both under-investment and over-investment in product features.

## When to Use
- Deciding whether to invest more in an existing feature
- Evaluating if a new feature is "good enough" to ship
- Prioritizing between improving existing features vs. building new ones
- Determining why users aren't adopting a feature
- Planning feature iteration roadmap
- Assessing competitive positioning on specific capabilities

## Prerequisites
- Clear definition of what "value" means for the feature (convenience, quality, speed, etc.)
- Understanding of user expectations and competitive landscape
- Ability to measure or estimate feature usage and satisfaction
- Product analytics to understand feature adoption

## Procedure

### Step 1: Understand the Utility Curve Model
**Learn the fundamental S-curve shape and what it represents**

- **Visual Model**: S-curve graph
  - **X-axis**: Cost/Effort/Investment (could also be quality, polish, completeness)
  - **Y-axis**: Utility/Value/Convenience for users

- **Three Zones of the Curve**:
  1. **Flat Bottom (Under-Investment Zone)**:
     - Low effort produces almost no utility
     - Feature exists but isn't actually usable
     - Users try it and bounce
     - Example: "Hammer handle breaks with any impact" → completely useless

  2. **Steep Middle (High ROI Zone)**:
     - Critical threshold where utility rapidly increases
     - Each increment of effort produces significant value
     - Feature becomes genuinely useful
     - Example: Hammer is now durable enough to use reliably

  3. **Flat Top (Diminishing Returns Zone)**:
     - Additional effort produces minimal additional value
     - Feature is "good enough"
     - Users are satisfied
     - Example: Making hammer handle slightly more durable doesn't matter much

**Key Quote**: "The most basic example I can think of is let's say you're making a hammer, and on that bottom axis, it's now quality, and if the hammer has a handle that breaks with any impact, then is totally useless. And if you make it a little bit stronger, it's still pretty useless and it's like junk, junk, junk, junk, junk. Okay, good, great. Then it doesn't matter anymore."

### Step 2: Map Your Feature to the Curve
**Determine where your feature currently sits on the utility curve**

- **Diagnostic Questions**:
  - Are users even trying this feature? (If no → might not be discoverable or comprehensible)
  - When users try it, do they continue using it? (If no → might be in flat bottom zone)
  - Are users satisfied with it? (If no → might be in steep middle, need more investment)
  - Are users delighted by it? (If yes → might be at top of curve)
  - Are competitors significantly better at this? (If yes → curve has shifted up)

- **Evidence to Collect**:
  - Feature adoption rate
  - Feature retention (do users come back?)
  - User feedback and complaints
  - Competitive comparison
  - Support ticket volume related to feature
  - Success rate (do users accomplish their goal?)

- **Three Possible Diagnoses**:
  1. **On the Flat Bottom**: "We shipped this feature but no one uses it/appreciates it"
  2. **In the Steep Middle**: "Users want this but it's not quite good enough"
  3. **On the Flat Top**: "Users are satisfied, more investment won't help much"

### Step 3: Avoid the Binary Feature Trap
**Recognize that features aren't just "have it or don't have it"**

- **Common Mistake**: Thinking of features as binary (shipped vs. not shipped)
  - "We have search" ✓
  - "We have user profiles" ✓
  - "We have notifications" ✓

- **Reality**: Every feature exists on a spectrum of utility
  - Search could be basic keyword match or sophisticated semantic search
  - Profiles could be bare minimum or rich, customizable experiences
  - Notifications could be noisy and annoying or perfectly contextual

- **Critical Question**: "Have we just not invested enough in this or have we got all the value or convenience or quality that we could get out of this?"

**Key Quote**: "The reason I felt like this was so important is because we would talk about a feature, and usually features are thought of as a binary. You either have this feature or you don't. The argument I guess was have we just not invested enough in this or have we got all the value or convenience or quality or whatever that we could get out of this?"

### Step 4: Account for the Moving Bar (Divine Discontent)
**Understand that the curve shifts upward over time**

- **The Rising Standards Problem**:
  - Users' expectations increase as competitors improve
  - What was "good enough" last year might not be this year
  - The curve itself moves upward
  - "Divine discontent" (Jeff Bezos term) must be embraced

- **Implications**:
  - Features implemented once need periodic reinvestment
  - "Most things get improved upon very infrequently and some things get improved upon never"
  - Competitive analysis needed: What's the new "good enough"?

- **Examples of Rising Bars**:
  - Login experience (now users expect SSO, magic links, biometrics)
  - Search capability (now users expect instant, typo-tolerant, semantic)
  - Mobile experience (now users expect native-feeling web apps)
  - Checkout experience (now users expect one-click, saved payment methods)

**Key Quote**: "The line actually moves because once people are familiar with a piece of software or the way a feature is implemented or something like that, their standards go up, and so there's this competition."

### Step 5: Prioritize Investment Decisions
**Use utility curve position to guide resource allocation**

- **Decision Matrix**:

  | Feature State | User Behavior | Investment Priority | Action |
  |--------------|---------------|-------------------|--------|
  | Flat bottom | Try once, never return | HIGH | Double down or kill |
  | Steep middle | Use but complain | HIGH | Invest to reach "good enough" |
  | Flat top | Satisfied, frequent use | LOW | Maintain, don't over-invest |
  | Flat top + competitors improving | Satisfied today | MEDIUM | Monitor, plan upgrade |

- **Specific Scenarios**:

  **Scenario A: Feature in Flat Bottom**
  - Shipped feature, low adoption
  - Users try it but bounce
  - Decision: Either invest significantly to reach steep part of curve OR remove feature entirely
  - Don't leave it in limbo (adds complexity without value)

  **Scenario B: Feature in Steep Middle**
  - Users want this capability
  - Current implementation doesn't meet needs
  - Decision: Highest priority for investment—small improvements = big value gains

  **Scenario C: Feature in Flat Top**
  - Users satisfied
  - Feature works well
  - Decision: Resist urge to over-invest; focus elsewhere
  - Exception: If competitors are improving, curve is shifting up

### Step 6: Recognize Infrastructure vs. User-Facing Curves
**Different types of work have different curve shapes**

- **Infrastructure Work** (Database, authentication, APIs):
  - Flat bottom is very flat (users table generates zero user value)
  - Must reach minimum viable threshold to generate any value
  - Often "all or nothing" investment

**Key Quote**: "If you're making an app, okay, this app's going to have users and so let's make a user's table and a database, and so far you have generated no value."

- **User-Facing Features** (Search, profiles, messaging):
  - Can sometimes ship minimal version and iterate
  - More forgiving curve shape
  - Easier to test and learn

- **Polish and Craft** (Animations, micro-interactions):
  - Often thought to be in diminishing returns
  - Actually can be in steep middle for differentiation
  - Creates emotional connection beyond functionality

### Step 7: Apply to Real Product Decisions
**Walk through concrete examples**

**Example 1: Google Calendar Time Zone Picker (Negative)**
- **State**: Flat bottom (technically works but usability is terrible)
- **Problem**: Presents all ~300+ time zones alphabetically
  - When typing "EAST" shows Eastern Australia before US Eastern
  - Treats Newfoundland (0.5M people) same as China Time (1.8B people)
  - No smart defaults based on user location
- **Investment Needed**: Small (smart sorting, geo-based defaults)
- **Value Gain**: Significant (from frustrating to delightful)
- **Diagnosis**: Under-invested feature in flat bottom zone

**Example 2: Slack Threads @-mention Pre-population (Negative)**
- **Initial State**: Flat top (threads working well)
- **Change**: Pre-populated @ mention of previous responder
- **Problem**: Over-investment in wrong direction
  - Took thousands of engineering hours
  - A/B testing, instrumentation, analytics, meetings
  - Result: "Threads are 2.17 messages long vs. 2.14" (meaningless difference)
- **Diagnosis**: Massive investment in diminishing returns zone
- **Learning**: Cost of analysis exceeded any possible value gain

**Key Quote**: "The problem with that... was the difference that you could possibly achieve between having this feature and not having this feature is like this much... The cost of doing the analysis was this much. So it's guaranteed to be a loser."

**Example 3: Slack Magic Link Authentication (Positive)**
- **Observation**: Typing complex passwords on mobile is terrible UX
- **Solution**: Just ask for email, send link, auto-authenticate
- **Investment**: Moderate (new auth flow, link generation, security)
- **Value**: High (dramatically better mobile onboarding)
- **Diagnosis**: Investment in steep middle zone, reached flat top with innovation

## Expected Outcomes
- **Better resource allocation**: Invest where ROI is highest (steep part of curve)
- **Fewer wasted efforts**: Avoid over-investing in diminishing returns
- **Clearer prioritization**: Understand which features need doubling down
- **Improved shipping decisions**: Know when feature is "good enough" vs. "not ready"
- **Competitive positioning**: Identify where you're under-invested vs. competitors

## Common Pitfalls

### Pitfall 1: Shipping Features in Flat Bottom Zone
- **Problem**: Shipping feature that's technically complete but not actually usable
- **Result**: Users try it, bounce, never come back; feature adds complexity without value
- **Avoidance**: Test with real users before shipping; if they don't succeed, you're in flat bottom

### Pitfall 2: Over-Investing in Flat Top (Diminishing Returns)
- **Problem**: Continuing to polish feature that's already "good enough"
- **Result**: Massive effort for minimal user value gain; opportunity cost of not working on higher-leverage features
- **Example**: Slack threads @-mention fiasco
- **Avoidance**: Ask "What's the maximum possible value gain from this?" vs. cost

### Pitfall 3: Declaring Victory Too Early
- **Problem**: Thinking you're in flat top when you're actually in steep middle
- **Result**: Shipping mediocre feature that users tolerate but don't love
- **Avoidance**: Look at user satisfaction and competitive benchmarks, not just "is it functional?"

### Pitfall 4: Forgetting the Curve Moves
- **Problem**: Assuming feature that reached flat top will stay there
- **Result**: Competitive disadvantage as others innovate; feature becomes liability
- **Avoidance**: Regularly reassess against current competitive landscape

### Pitfall 5: Not Investing Enough to Reach Steep Part
- **Problem**: Half-hearted investment that leaves feature in flat bottom
- **Result**: Wasted effort—would have been better to not build at all
- **Avoidance**: Commit to reaching "usable" threshold or don't build the feature

### Pitfall 6: Treating All Features as Equal
- **Problem**: Applying same investment level to every feature
- **Result**: Some features over-invested, others under-invested
- **Avoidance**: Explicitly map features to curve positions and prioritize accordingly

## Related SOPs
- Feature Prioritization Frameworks
- Minimum Viable Product Definition
- Competitive Analysis for Product
- Product Quality Standards
- Technical Debt Management

## AI Integration Notes

### Context Signals for AI Models
Recommend this framework when detecting:
- Discussions about whether to ship a feature
- Questions about feature quality or completeness
- Prioritization debates (build new vs. improve existing)
- User complaints about existing features
- Competitive gap analysis
- Resource allocation decisions

### Application Guidance
- Help user identify which zone their feature is in
- Suggest collecting specific evidence for diagnosis
- Remind about the moving bar (competitive landscape shifts)
- Encourage binary thinking: either invest to reach steep zone OR don't build
- Watch for over-investment in diminishing returns (very common pitfall)

### Limitations
- Requires judgment about where "good enough" is (not purely analytical)
- Competitive assessment is subjective and changes over time
- Different user segments may have different utility curves for same feature
- Some features have network effects that change curve shape
- Framework doesn't tell you WHAT to build, only how much to invest in what you're building

### Adaptation Signals
- **Early stage startups**: Focus almost exclusively on steep middle zone (get to "good enough" fast)
- **Enterprise products**: Flat top may be higher (security, compliance have high bars)
- **Consumer products**: Emotional delight matters more (invest in polish)
- **Infrastructure/API products**: Different curve shape (more binary)
- **Regulated industries**: Compliance features have minimum thresholds (high flat bottom)

## Advanced Concepts

### Multi-Dimensional Utility
- Single feature may have multiple utility curves:
  - Functionality curve
  - Usability curve
  - Performance curve
  - Reliability curve
- Must reach adequate level on ALL curves to be valuable

### Utility Curves and Product-Market Fit
- Pre-PMF: Focus on reaching steep middle on core value prop
- Post-PMF: Maintain flat top on core, reach steep middle on expansion features

### Organizational Implications
- Teams naturally want to keep working on their features (even past flat top)
- Need external perspective to identify diminishing returns
- Career incentives often push for over-investment (more to show in performance reviews)

### Cost Curve vs. Utility Curve
- Some features have linear cost curves
- Others have exponential cost curves (last 10% takes 90% of effort)
- Optimal investment is where marginal utility gain = marginal cost increase
