# Systems Thinking for Engineering Leaders

## Metadata
- **Source**: Will Larson - Lenny's Podcast (via Donella Meadows "Thinking in Systems")
- **Domain**: Engineering Leadership & Problem-Solving
- **Type**: Framework
- **Applicable To**: Engineering Leaders, Staff+ Engineers, Product Managers, Engineering Directors
- **Difficulty**: Intermediate to Advanced
- **Company Stage**: Growth to Scale

## Overview
A practical framework for applying systems thinking to engineering problems using stocks and flows modeling. This approach helps diagnose complex problems (like hiring pipelines, incident management, or performance issues) by creating mental models, identifying where reality conflicts with your model, and using those gaps to learn and improve. Critically, it emphasizes that reality is always right when your model conflicts with it.

## When to Use
- When analyzing complex recurring problems (hiring, incidents, performance)
- When you need to diagnose where a process is breaking down
- When multiple teams have different theories about what's wrong
- When you're caught in analysis paralysis and need to move to action
- When you need to educate stakeholders about system dynamics
- When optimizing resource allocation or process improvements

## Prerequisites
- Ability to identify and articulate system components
- Willingness to be wrong (reality trumps your model)
- Access to historical data to validate your model
- Understanding that this is a learning tool, not an end goal
- Commitment to eventually taking action, not just analyzing

## Procedure

### Step 1: Understand Core Systems Thinking Concepts

**Stocks**: Things that accumulate
- Examples: Number of fish in a lake, candidates in pipeline, incidents in backlog, technical debt items

**Flows**: Movement between stocks
- Examples: Rate of fishing, conversion rates in hiring pipeline, incident resolution rate, debt accumulation rate

**System Dynamics**: How stocks and flows interact over time
- Flows are often influenced by current stock levels
- Multiple feedback loops can exist
- Small changes in one part can have unexpected effects elsewhere

**Foundational principle**: "Reality is never wrong. Reality is always right. Your model is always wrong if it's in conflict with reality."

### Step 2: Create Initial Model (Even If Imperfect)
Start by mapping out stocks and flows:

**Identify Stocks**:
- What accumulates in your system?
- What are the state variables?
- Example (hiring): potential candidates, sourced candidates, phone screen stage, hiring manager screen stage, team interview stage, offer stage, accepted offers

**Identify Flows**:
- What moves between stocks?
- What are the rates of movement?
- What influences those rates?
- Example (hiring): sourcing rate (influenced by number of sourcers), conversion rates at each stage (influenced by interview quality, role clarity, compensation)

**Map Relationships**:
- How does one stock affect flows to other stocks?
- Are there feedback loops?
- Example (hiring): Large candidate pool at offer stage but low acceptance → May indicate closing problem or compensation issues, NOT sourcing problems

### Step 3: Test Model Against Reality
Validate your mental model with real data:

**Gather Historical Data**:
- Pull data from applicant tracking systems, incident logs, performance databases
- Look at actual numbers, not estimates or assumptions
- Example: Greenhouse or similar ATS data for hiring pipeline

**Compare Model to Reality**:
- Where does reality differ from your expectations?
- Which flows are faster or slower than expected?
- Which stocks are larger or smaller than expected?
- Where are the surprising bottlenecks?

**The Gap Is the Learning**:
- Don't force reality to match your model
- The conflict between model and reality shows where your mental model is wrong
- This gap is where you can learn and improve

### Step 4: Use Model to Diagnose Problems
Apply your model to identify root causes:

**Hiring Pipeline Example**:
- **Symptom**: Not hiring enough people
- **Possible diagnoses**:
  1. Not enough candidates entering pipeline (sourcing problem)
  2. Poor conversion through stages (interview process problem)
  3. Can't make decisions (hiring managers won't extend offers)
  4. Can't close candidates (acceptance rate problem)

**How to diagnose**:
- Look at stock levels at each stage
- Identify where the bottleneck actually is
- Example: Tons of candidates at offer stage but few offers extended → Hiring manager conviction problem, NOT sourcing problem
- Example: Many offers extended but few acceptances → Closing problem

**Incident Management Example** (from Will's Stripe experience):
- **Symptom**: System availability not improving
- **Model**: Track incidents through detection → triage → resolution
- **Reality check**: Spending too much time measuring/analyzing, not enough time fixing
- **Diagnosis**: Lost track of whether actually improving things vs. just measuring better
- **Learning**: "Measure twice, cut once" is good, but infinite measurement without action is analysis paralysis

### Step 5: Avoid the Expert Trap
Watch for when systems thinking becomes counterproductive:

**Red Flags**:
- Believing "reality is wrong" when it conflicts with your model
- Spending more time refining the model than taking action
- Analysis paralysis—measuring indefinitely without implementing improvements
- Becoming overly attached to the elegance of your model

**Will's Example**: At Stripe, the incident management team (including Will) got "caught up in the systems thinking model" and prioritized measurement over actual improvements.

**Solution**: Remember that systems thinking is a learning tool, not the end goal. "You do have to cut at some point to actually make impact."

### Step 6: Move from Analysis to Action
Use your improved understanding to drive results:

**Decision Making**:
- Use your model to identify the highest-leverage intervention point
- Prioritize actions based on where model shows bottleneck
- Example: If hiring bottleneck is at offer acceptance, invest in closing process, not more sourcers

**Communicate Trade-offs**:
- Use model to explain why you're prioritizing certain actions
- Help stakeholders understand system dynamics
- Example: "Adding more sourcers won't help because our bottleneck is hiring manager decision-making"

**Iterate**:
- Take action
- Measure impact
- Update model based on new reality
- Repeat

### Step 7: Apply to Common Engineering Problems

**Hiring Pipeline**:
- Stocks: Candidates at each stage
- Flows: Conversion rates
- Common insights: Bottleneck often NOT sourcing (despite assumptions)

**Incident Management**:
- Stocks: Open incidents, resolved incidents, prevention work
- Flows: Incident rate, resolution rate, prevention effectiveness
- Common insight: Can over-invest in measurement vs. improvement

**Technical Debt**:
- Stocks: Debt items, new debt, resolved debt
- Flows: Debt creation rate, debt resolution rate
- Common insight: If creation rate exceeds resolution rate, debt always grows

**Team Velocity**:
- Stocks: Completed work, work in progress, blocked work
- Flows: Start rate, completion rate, blocking rate
- Common insight: WIP limits matter; starting more doesn't mean finishing more

## Expected Outcomes
- Clear diagnosis of where systems are actually breaking down (vs. assumptions)
- Better prioritization of improvement efforts
- Reduced "solution thrashing" (trying random fixes)
- Improved communication about complex problems
- Faster learning through model-reality comparison
- Movement from analysis to action

## Common Pitfalls

### Pitfall 1: Reality Is Wrong (Model Worship)
**Problem**: "The least successful but smartest people I've worked with were really strong systems thinking advocates" who think reality is wrong when it conflicts with their model.
**Solution**: Always remember: reality is never wrong, your model is always wrong. The gap is where you learn.

### Pitfall 2: Analysis Paralysis
**Problem**: Getting so caught up in measuring and refining the model that you never take action to improve the system.
**Solution**: "Measure twice, cut once. Sure, but you don't measure infinite times and never get to cut." Set time limits on analysis; force yourself to act.

### Pitfall 3: Solving the Wrong Problem
**Problem**: Making big changes with no data, based on assumptions about where the bottleneck is.
**Solution**: Build even a simple model and validate against reality before making large investments.

### Pitfall 4: Over-Complicating the Model
**Problem**: Creating extremely complex models that are hard to validate or use.
**Solution**: Start simple. A rough model validated against reality is better than a perfect model never tested.

### Pitfall 5: Using Systems Thinking Everywhere
**Problem**: Applying this framework to every problem, even simple ones.
**Solution**: Reserve for complex, recurring problems with multiple variables. Simple problems don't need system models.

### Pitfall 6: Ignoring Qualitative Factors
**Problem**: Over-indexing on what can be measured, missing important qualitative dynamics.
**Solution**: Use systems thinking to structure analysis, but complement with qualitative insights from practitioners.

## Real-World Example: Hiring Pipeline Analysis

### Scenario
Company isn't hitting hiring targets. Multiple theories:
- Recruiters say: "We need more sourcers"
- Hiring managers say: "The candidates aren't good enough"
- Engineers say: "We're too picky"

### Systems Thinking Application

**Step 1: Model the System**
- Stocks: Potential candidates (infinite) → Sourced → Phone Screen → Hiring Manager Screen → Team Interview → Offer Stage → Accepted
- Flows: Sourcing rate, conversion rates at each stage

**Step 2: Gather Data**
- Pull last 6 months from applicant tracking system
- Calculate actual conversion rates at each stage
- Calculate time-to-fill, offer acceptance rates

**Step 3: Analyze**
Actual finding:
- Plenty of candidates reaching offer stage (40+ qualified candidates per role)
- Almost none converting from potential offer → actual offer extended
- High acceptance rate when offers ARE extended

**Step 4: Diagnose**
- Real problem: Hiring managers can't get to conviction on any candidate
- NOT a sourcing problem (enough candidates)
- NOT a closing problem (high acceptance rate)
- IS a decision-making problem

**Step 5: Take Action**
- Work with recruiters and hiring managers on decision-making frameworks
- Create clearer role requirements and evaluation rubrics
- Coach hiring managers on getting to conviction
- Do NOT hire more sourcers (would waste resources)

**Result**: Faster hiring, better outcomes, resources spent on actual bottleneck

## Related SOPs
- Engineering Strategy Development
- Staff Engineer Sponsorship Framework
- Engineering Productivity Measurement
- Incident Management and Remediation

## Recommended Reading
- **Thinking in Systems** by Donella Meadows (Will's #1 recommendation)
- **Silent Spring** by Rachel Carson (foundational systems thinking example)
- **An Elegant Puzzle** by Will Larson (applies systems thinking to engineering management)

## AI Integration Notes

### Context Signals
Trigger this SOP when detecting:
- Complex, recurring problems with multiple theories about root cause
- Debates about where to invest resources to improve a process
- "We've tried everything" statements about persistent problems
- Requests to optimize hiring, incidents, performance, or throughput
- Questions about bottleneck identification
- Situations where intuition conflicts with data

### Adaptation Guidance
- **For beginners**: Start with simple two-stock models (input/output)
- **For advanced practitioners**: Can handle multi-loop feedback systems
- **For technical audiences**: Can use more formal notation and tools
- **For non-technical audiences**: Use concrete examples and avoid jargon
- **When time-constrained**: Build simple model, test one hypothesis, iterate

### Key Principles to Emphasize
1. Reality is always right; your model is wrong when they conflict
2. The gap between model and reality is where learning happens
3. Systems thinking is a learning tool, not an end goal
4. Must eventually move from analysis to action
5. Start with simple models and iterate

### Warning Signs of Misapplication
- Spending more time on model than on improvements
- Declaring reality is wrong when it doesn't match model
- Paralysis by analysis
- Creating models too complex to validate
- Applying to simple problems that don't need this level of analysis

### Example Prompts for AI Application
"Our hiring is too slow" → Ask diagnostic questions to build a simple model and identify bottleneck
"We can't improve system reliability" → Create incident flow model to find leverage points
"Should we hire more engineers?" → Model the constraint: is the bottleneck people, or something else?
"Everything is high priority" → Model WIP flows to show capacity constraints
