# Differentiation vs. Table Stakes Framework

## Metadata
- **Source**: Paul Adams (CPO, Intercom) - Lenny's Podcast
- **Domain**: Product Management & Strategy
- **Type**: Framework
- **Applicable To**: Product Managers, Product Leaders, CPOs, Founders
- **Company Stage**: Particularly critical for startups entering established categories, but applies to all stages
- **Difficulty**: Intermediate

## Overview
A simplified adaptation of the Kano model for roadmap prioritization that balances two essential forces: differentiation (what makes customers attracted to your product) and table stakes (the basic requirements needed to be considered as a viable option). This framework helps teams avoid the trap of building exciting features while missing critical functionality that blocks adoption.

## When to Use
- During roadmap planning and prioritization
- When evaluating whether to build innovative vs. basic features
- When entering an established product category
- When customers love your product but can't fully adopt it
- When deciding resource allocation across teams
- When switching between growth phases (early startup vs. scale-up)
- When analyzing why prospects choose competitors

## Prerequisites
- Understanding of your target market and competitors
- Customer feedback about missing features or capabilities
- List of potential roadmap items to evaluate
- Sales feedback on why deals are won or lost
- Product analytics on feature usage and adoption

## Procedure

### Step 1: Understand the Two Forces
Recognize that product adoption is driven by two distinct and often competing forces.

**Force 1: Differentiation (Attraction)**
- **Definition**: Features that make your product different and better than alternatives
- **Purpose**: Creates attraction and desire to try/switch to your product
- **Characteristics**:
  - Novel or innovative capabilities
  - Better approach to existing problems
  - Delightful user experience
  - Unique competitive advantages

**Critical Requirement**: Must be different and better *in ways customers care about*

**Anti-pattern Example** (from Paul's experience):
- Google Wave: "Amazingly innovative product that no one really cared about"
- Google social projects: "Different and better in ways people didn't care about"
- Being innovative in areas customers don't value creates no differentiation advantage

**Force 2: Table Stakes (Entry Requirement)**
- **Definition**: Basic features and capabilities required to be considered as a viable option
- **Purpose**: Enables customers to actually adopt and use your product
- **Characteristics**:
  - Often boring and unsexy
  - Expected functionality in the category
  - Permissions, reporting, integrations, compliance
  - "Of course it does that" features

**Common Problem**: Easy to ignore table stakes because they're not exciting

**Example from Intercom**:
> "Everyone loved it and really wanted to buy, but they couldn't, because we didn't have the basic report that they needed or we didn't have the basic permission feature that they needed."

### Step 2: Audit Your Current Roadmap
Classify every item on your roadmap as differentiation or table stakes.

**For Each Roadmap Item, Ask**:
1. **Is this differentiation or table stakes?**
   - Differentiation: Would competitors struggle to copy this? Does it create competitive advantage?
   - Table stakes: Would customers expect any product in our category to have this?

2. **Which matters more to our customers right now?**
   - Talk to customers directly
   - Review why deals are won (differentiation) vs. lost (often table stakes)
   - Analyze feature requests by frequency and urgency

3. **What's blocking adoption today?**
   - Missing differentiation: Customers don't see why to switch
   - Missing table stakes: Customers love it but can't fully adopt

**Create a Simple Visualization**:
```
Current Roadmap Balance:
Differentiation: [####------] 40%
Table Stakes:    [######----] 60%

Target Balance:  [50/50 or context-dependent]
```

### Step 3: Determine Appropriate Balance by Context
The right mix of differentiation vs. table stakes depends on your stage and market position.

**Early Startup in Established Category**
- **Recommended Balance**: 70-80% Differentiation, 20-30% Table Stakes
- **Rationale**:
  - Must have incredible differentiation to get noticed
  - Can't compete on feature parity with established players
  - Customers will buy you "alongside" incumbents initially

**Example from Intercom's Early Days**:
> "People would just buy us alongside Service Cloud or Zendesk... 'We want that [modern messaging] for our customers, alongside the big giant bag of table stakes.' Because Intercom doesn't have any of those."

**Growth Stage (Moving Upmarket)**
- **Recommended Balance**: 50-60% Differentiation, 40-50% Table Stakes
- **Rationale**:
  - Building toward full product replacement capability
  - Need to catch up on critical table stakes
  - Must maintain differentiation advantage

**Mature Product in Established Position**
- **Recommended Balance**: 40-50% Differentiation, 50-60% Table Stakes
- **Rationale**:
  - Steady flow of table stakes maintains competitiveness
  - Still need differentiation to justify premium or preference
  - Risk of becoming commodity without continued innovation

**New Category Creation**
- **Recommended Balance**: 80-90% Differentiation, 10-20% Table Stakes
- **Rationale**:
  - Defining what the category should be
  - Fewer established expectations
  - Differentiation IS the category definition

### Step 4: Identify and Prioritize Table Stakes Gaps
Systematically catalog missing table stakes that block adoption.

**Sources for Table Stakes Discovery**:
- Lost sales opportunities (ask sales why deals were lost)
- "We'd love to use you fully, but we can't because..." customer feedback
- Competitive feature matrices
- Industry analyst reports and requirements
- RFP requirements that you can't fulfill
- Customer support escalations

**Common Table Stakes Categories**:
- **Permissions & Security**: Role-based access, SSO, audit logs
- **Reporting & Analytics**: Standard reports, data export, dashboards
- **Integrations**: CRM, data warehouse, existing tool connections
- **Compliance**: GDPR, SOC 2, industry-specific requirements
- **Workflow**: Automation, bulk operations, advanced filters
- **Enterprise Features**: Multi-workspace, API access, SLAs

**Prioritization Questions**:
1. How many customers/prospects need this? (Market size)
2. Is this a "must-have" or "nice-to-have"? (Deal blocking vs. nice-to-have)
3. Can customers work around the gap? (Severity)
4. What revenue is blocked by this gap? (Business impact)

### Step 5: Validate Differentiation with Customer Energy
Ensure your differentiation features address problems customers actually care about.

**The "Customer Energy" Test**:
- Do customers get excited when you describe this?
- Do they lean forward in conversations about it?
- Do they volunteer that this is a pain point?
- Would they pay more for this specifically?

**Red Flags for False Differentiation**:
- "That's interesting" (but not "I need that")
- "Sure, that could be useful" (lukewarm response)
- You're explaining why it's valuable (they should already know)
- It solves a problem customers have already solved another way

**How to Find True Differentiation**:
- Deep customer research on actual workflow pain points
- Jobs to be Done interviews to find emotional energy
- Observe where customers create workarounds
- Find problems that customers talk about unprompted

**Paul's Lesson from Google**:
> "We found a lot of people with the same problem, but they didn't really care. They didn't really care. What they had was fine."

Real differentiation requires:
1. Lots of people with the problem (market size)
2. High energy around the problem (motivation to switch)
3. Your solution is meaningfully better (actual advantage)

### Step 6: Make Strategic Trade-offs
Use the framework to make explicit roadmap decisions.

**Create a Decision Framework**:

For each potential feature, score:
- **Differentiation value**: 1-5 (How much does this differentiate us?)
- **Table stakes urgency**: 1-5 (How much is this blocking adoption?)
- **Customer energy**: 1-5 (How much do customers care?)
- **Effort required**: 1-5 (How much will this cost to build?)

**Decision Rules Example**:
```
High Differentiation + High Energy + Meets Balance Target = Build Now
High Table Stakes Urgency + Blocking Revenue = Build Now
Low Energy + Low Urgency + Any Category = Backlog
Doesn't Fit Balance Target + Low Urgency = Defer
```

**Example Trade-off Conversations**:
- "This reporting feature is boring, but we've lost 3 deals because of it. We need to shift toward table stakes this quarter."
- "We're at 70% table stakes right now. We need more differentiation or we'll become a commodity."
- "This AI feature is exciting, but customers are asking for basic permissions first. What's blocking more revenue?"

### Step 7: Monitor and Rebalance Over Time
Recognize that the pendulum will swing - plan for deliberate rebalancing.

**Expected Pattern** (from Intercom's experience):
- Year 1-2: Heavy differentiation (70/30)
- Year 3-4: Realize missing table stakes, swing to 30/70
- Year 5: Rebalance to 50/50
- Ongoing: Continuous rebalancing as priorities shift

**Warning from Paul**:
> "We've done this so many times in so many domains... A year later, 'Oh, wait a minute, we're missing all the table stakes. Okay, we're over there.'"

**Rebalancing Triggers**:
- Win/loss analysis shows pattern of lost deals due to missing features
- Customer adoption plateaus despite high interest
- Competitive analysis shows you're falling behind on basics
- Sales cycle lengthens due to feature gap discussions
- Multiple teams building similar basic functionality

**How to Rebalance**:
1. Acknowledge the imbalance (make it visible)
2. Set explicit target ratio for next planning period
3. Commit leadership to the rebalancing
4. Accept this means saying no to some attractive differentiation work
5. Communicate why to the team to maintain morale

### Step 8: Communicate Framework Across Organization
Make differentiation vs. table stakes a shared language.

**Use Cases**:
- **Roadmap reviews**: "Is this differentiation or table stakes? Why?"
- **Prioritization debates**: "We're at 70% differentiation right now. This table stakes feature deserves priority."
- **Hiring discussions**: "We need designers who can make table stakes feel differentiated"
- **OKR setting**: "This quarter we're rebalancing from 70/30 to 50/50"

**Benefits of Shared Language**:
- Faster prioritization conversations
- Less emotion in trade-off decisions
- Teams understand strategic rationale
- Easier to spot when pendulum has swung too far

## Expected Outcomes
- Clear, data-driven prioritization framework
- Balanced roadmap that drives both attraction and adoption
- Fewer lost deals due to missing table stakes features
- Maintained competitive differentiation
- Team alignment on prioritization rationale
- Awareness of when rebalancing is needed
- More honest assessment of feature value

## Common Pitfalls

**Pitfall 1: Over-Indexing on Differentiation**
- **Problem**: Building exciting features while customers can't adopt product due to missing basics
- **How to Avoid**: Regularly review why deals are lost. Talk to customers who love product but can't fully adopt.
- **Paul's Experience at Intercom**: "We were much more attracted to the differentiation... everyone loved it and really wanted to buy, but they couldn't."

**Pitfall 2: Building Table Stakes Forever**
- **Problem**: Becoming a commodity by only building what competitors have
- **How to Avoid**: Set explicit target for differentiation percentage. Protect time for innovation.

**Pitfall 3: False Differentiation**
- **Problem**: Building features that are different but customers don't care about
- **How to Avoid**: Apply the "customer energy" test. Validate that customers actually have energy around the problem.
- **Paul's Google Lesson**: "Different and better in ways people didn't care about... you've got to match... what AI can do, and what it will be able to do, and then ask yourself, 'Okay, what are we going to do?'"

**Pitfall 4: Misclassifying Features**
- **Problem**: Calling table stakes "differentiation" or vice versa
- **How to Avoid**: Check with sales and customers. Is this expected or surprising? Required or delightful?

**Pitfall 5: Over-Correcting When Rebalancing**
- **Problem**: Swinging pendulum too far in the other direction (see "Swinging the Pendulum" SOP)
- **How to Avoid**: Set target ratios, monitor progress, course-correct incrementally rather than dramatically.

**Pitfall 6: Ignoring Market Context**
- **Problem**: Using same ratio regardless of company stage or competitive position
- **How to Avoid**: Reassess appropriate balance when company stage or market changes.

**Pitfall 7: Making Table Stakes Feel Like Defeat**
- **Problem**: Team morale suffers because "boring" table stakes work isn't valued
- **How to Avoid**: Celebrate table stakes wins. Frame as "removing adoption blockers." Challenge teams to make table stakes differentiated through execution quality.

## Related SOPs
- `/sops/product-management/strategy/swinging-the-pendulum-001.md` - Avoiding over-corrections
- `/sops/product-management/prioritization/gem-prioritization-framework-001.md` - Shreyas Doshi's prioritization framework
- `/sops/customer-research/jobs-to-be-done-interview-framework-001.md` - Finding customer energy
- `/sops/product-management/strategy/product-market-story-fit-001.md` - Related framework from Paul Adams

## Real-World Example: Intercom's Journey

**Early Years (2012-2015)**:
- **Balance**: ~70-80% Differentiation
- **Strategy**: Modern conversational messaging was novel differentiation
- **Market Position**: Customers bought Intercom *alongside* Zendesk/Salesforce
- **Result**: High attraction, limited full replacement potential

**Mid-Stage (2015-2018)**:
- **Balance**: Swung to ~60-70% Table Stakes
- **Strategy**: Building depth to enable full replacement of incumbents
- **Market Position**: "It took us years to get there" to full product replacement
- **Challenge**: "We were missing all the table stakes"

**Current State (2018+)**:
- **Balance**: ~50/50
- **Strategy**: Maintain table stakes while investing heavily in AI differentiation
- **Market Position**: Can fully replace incumbents, AI creates new differentiation
- **Approach**: "50/50 probably in terms of resources, but it has swung 70/30 in both directions at times"

**Key Insight**:
> "If you're a startup and you're entering any established category... massive, a lot of table stakes built up over years, decades... So to play the game, you need a lot of the table stakes, unless you have incredible differentiation."

## AI Integration Notes

### For AI Models Using This SOP

**Context Signals That Should Trigger This SOP**:
- User struggling with roadmap prioritization
- Debate between innovative vs. basic features
- User mentions customers love product but can't adopt fully
- Discussion of startup entering established category
- Sales team reporting lost deals due to missing features
- Questions about resource allocation across teams

**How to Adapt for Different Situations**:
- **New market category**: Weight toward differentiation (80/20)
- **Established category**: More balanced or table-stakes heavy early (60/40 or 50/50)
- **Enterprise customers**: Table stakes often more critical due to requirements
- **Consumer products**: Differentiation may matter more than comprehensive features
- **Developer tools**: Table stakes like integrations, APIs especially critical

**Key Principles to Emphasize**:
1. Differentiation must be in areas customers care about (have energy around)
2. Table stakes are often boring but blocking adoption
3. The pendulum will swing - this is normal and expected
4. Right balance depends on stage, market, and competitive position
5. Make the framework a shared language across organization

**Questions to Help Users Apply This**:
- Is this feature something customers expect (table stakes) or something that would surprise/delight them (differentiation)?
- Why are you losing deals - missing differentiation or missing table stakes?
- What percentage of your roadmap is differentiation vs. table stakes right now?
- Based on your stage and market, what's the right balance?
- Do customers have genuine energy around this problem?
