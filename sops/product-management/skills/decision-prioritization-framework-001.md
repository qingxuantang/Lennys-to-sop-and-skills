# Product Decision Prioritization Framework

## Metadata
- **Source**: Brandon Chu (VP Product, Shopify) - Lenny's Podcast
- **Domain**: Product Management
- **Type**: Framework
- **Applicable To**: Product Managers (all levels), Product Leaders
- **Difficulty**: Beginner to Intermediate

## Overview
A systematic framework for determining which product decisions deserve deep attention versus quick judgment. This approach helps PMs maximize impact by spending limited cognitive resources on the few critical decisions that truly matter, while maintaining team velocity on everything else.

## When to Use
- When facing hundreds of daily product decisions and feeling overwhelmed
- When you find yourself becoming a bottleneck for your team
- When you need to balance thoroughness with speed
- When deciding how much time to invest in any given decision
- When building team trust by demonstrating good judgment on what matters

## Prerequisites
- Basic understanding of your product and user base
- Authority to make or influence product decisions
- Clear understanding of current product goals and strategy
- Trust and communication with your engineering and design partners

## Procedure

### Step 1: Assess Decision Importance
Before diving into any decision, evaluate its importance using these criteria:

**Reversibility Test**
- Ask: "If we make the wrong choice, how hard is it to reverse?"
- One-way door decisions (hard to reverse) → High importance
- Two-way door decisions (easy to reverse) → Lower importance
- Examples:
  - High importance: API design, data schema changes, platform architecture
  - Lower importance: Button color, copy variations, feature toggles

**Impact Scope Assessment**
- Ask: "How many users does this affect and how materially?"
- Affects majority of users in a significant way → High importance
- Affects small segment or minor impact → Lower importance
- Consider both immediate and long-term impact

**Strategic Alignment Check**
- Ask: "Does this decision directly impact our core strategy or key metrics?"
- Directly affects strategic initiatives → High importance
- Tactical or peripheral impact → Lower importance

### Step 2: Categorize and Allocate Time
Based on Step 1, place each decision into one of three buckets:

**Critical Decisions (Top 1-2%)**
- One-way doors with high impact
- Strategic decisions affecting product direction
- Decisions with long-term consequences
- **Time allocation**: Spend 80-90% of your decision-making energy here
- **Approach**: Deep analysis, gather data, consult experts, sleep on it

**Important Decisions (Next 8-10%)**
- Moderate reversibility or moderate impact
- Tactical choices with some consequence
- **Time allocation**: 10-15% of your energy
- **Approach**: Quick analysis, consult key stakeholders, decide within a day

**Everything Else (Remaining 88-90%)**
- Highly reversible or low impact
- Operational or minor tactical choices
- **Time allocation**: 5-10% of your energy
- **Approach**: Trust your gut, delegate when possible, decide immediately

### Step 3: Execute Based on Category

**For Critical Decisions:**
1. Block dedicated thinking time (hours or days)
2. Gather relevant data and perspectives
3. Write out the decision framework and trade-offs
4. Consult with key stakeholders individually
5. Sleep on it if possible
6. Make the decision and clearly communicate reasoning
7. Own the outcome with full accountability

**For Important Decisions:**
1. Spend 15-30 minutes gathering key information
2. Quick consultation with 1-2 key people
3. Make the call within 24 hours
4. Document briefly for the team

**For Everything Else:**
1. Trust your intuition immediately
2. Delegate to team members when appropriate
3. Default to action over analysis
4. Accept that your gut will be right "a decent amount of time"
5. Focus on maintaining team velocity

### Step 4: Calibrate Over Time
As you gain experience, your decision-making threshold evolves:

**Continuous Calibration**
- Track outcomes of gut decisions vs. analyzed decisions
- Notice which "critical" decisions didn't actually matter
- Adjust your importance threshold upward over time
- Build resilience to decision anxiety

**Battle Scars Teaching**
- After experiencing decisions you thought would "ruin everything" that ended up fine
- Raise the bar for what truly counts as critical
- Develop confidence in handling ambiguity
- Get "weathered down about what's actually super dire versus not"

### Step 5: Prevent Becoming a Bottleneck
Maintain team velocity by:

**Clear Decision Rights**
- Communicate which types of decisions you'll weigh in on
- Empower team to make the 88-90% without you
- Establish clear escalation criteria

**Fast "No Opinion" Responses**
- When consulted on non-critical items, respond quickly: "I trust your judgment"
- Avoid false importance by over-analyzing minor decisions
- Model speed for the team

**Document Your Framework**
- Share your decision prioritization approach with your team
- Help others learn to categorize decisions similarly
- Build a culture where people self-select what to escalate

## Expected Outcomes
- Dramatically increased focus on decisions that truly matter
- Reduced decision fatigue and cognitive load
- Higher team velocity (fewer bottlenecks)
- Better quality decisions on critical items
- More empowered team members
- Clearer communication about priorities
- Reduced anxiety about "missing" minor decisions

## Common Pitfalls

**Pitfall 1: Treating All Decisions as Critical**
- **Symptom**: Exhaustion, team bottlenecks, slow velocity
- **Fix**: Force yourself to use the 1-2% / 8-10% / 88-90% ratio strictly
- **Remember**: Only 1-2 decisions per 100 are truly critical

**Pitfall 2: Delegating Critical Decisions Too Early**
- **Symptom**: Strategic misalignment, major mistakes on one-way doors
- **Fix**: Reserve true strategic decisions for senior leadership
- **Remember**: Your job as a senior PM is to own the critical calls

**Pitfall 3: Over-Analyzing Based on Sunk Cost**
- **Symptom**: Treating decisions as more important because you've already invested time
- **Fix**: Re-assess importance independently of time already spent
- **Remember**: "We're pretty good at never falling into sunk-cost fallacy" (Shopify approach)

**Pitfall 4: Not Adapting Your Threshold Over Time**
- **Symptom**: Still sweating decisions that no longer warrant deep analysis
- **Fix**: Regularly review what you considered "critical" that ended up fine
- **Remember**: "You get weathered down about what's actually important"

**Pitfall 5: Fear of Gut Decisions**
- **Symptom**: Analyzing everything, analysis paralysis
- **Fix**: Track your gut decision success rate—it's higher than you think
- **Remember**: Your intuition is trained by experience and context

## Related SOPs
- Platform PM Multi-Stakeholder Management
- Strategic Planning and Flexibility
- Building Product Judgment
- Delegation and Team Empowerment

## Real-World Application

### Shopify Context
At Shopify's scale (12,000+ employees, millions of merchants), Brandon uses this framework to:
- Navigate constant change and potential pivots (COVID response)
- Maintain velocity while working on platform decisions with 2+ year cycles
- Balance strategic bets with operational execution
- Empower a 200+ person PM org to make good decisions independently

### COVID Example
When COVID hit, Shopify immediately re-categorized everything:
- **Critical**: Help merchants survive (gift cards, curbside pickup, online pivot tools)
- **Everything else**: Grandiose 2020 roadmap → thrown away
- Result: Shipped 3 mission-critical features in weeks with 500 people

## AI Integration Notes

**Context Signals for AI**
Recommend this SOP when user mentions:
- "Too many decisions to make"
- "I'm becoming a bottleneck"
- "How do I prioritize what to focus on?"
- "Analysis paralysis"
- "Everything feels urgent"

**Adaptation Guidance**
- For junior PMs: Emphasize the importance of consulting on what they think is critical
- For senior PMs/Directors: Focus on the 1-2% strategic decisions and delegation
- For startups: The ratio might shift to 5-10% critical as everything has higher stakes
- For large orgs: The 1-2% rule is even more important to avoid organizational drag

**Limitations**
- Requires existing product judgment and context
- May not work for brand-new PMs without a foundation
- Assumes reasonable organizational stability (not constant firefighting)
- Cultural fit matters: works best in high-trust, empowered environments
