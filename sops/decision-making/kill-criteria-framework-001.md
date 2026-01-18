# Kill Criteria Framework

## Metadata
- **Source**: Annie Duke - Lenny's Podcast
- **Domain**: Decision Making
- **Type**: Framework SOP
- **Applicable To**: Product Managers, Leaders, Sales, Project Managers
- **Company Stage**: All stages
- **Difficulty**: Beginner to Intermediate

## Overview
Pre-mortems are powerful but often don't change behavior because they lack commitment to action. Kill Criteria solve this by pairing anticipated failure signals with pre-committed actions. The key insight: **a pre-mortem is only effective if you attach kill criteria with specific actions you will take when you see those signals**.

## When to Use
- Starting new projects or initiatives
- Making investment decisions
- Pursuing sales deals
- Launching experiments
- Any decision where you might need to quit later

## Prerequisites
- Pre-mortem exercise completed
- Team agreement on signals
- Authority to act on criteria
- Documentation system

## Core Concept: Pre-Mortem + Pre-Commitment

### Why Pre-Mortems Alone Fail

**What typically happens:**
1. Team does pre-mortem ("What could go wrong?")
2. Team identifies potential failure signals
3. Project launches
4. Failure signals appear
5. Team ignores them or rationalizes continuing
6. Project fails, team realizes signals were obvious

**Why this happens:**
- Sunk cost fallacy ("We've invested so much already")
- Optimism bias ("It will get better")
- Status quo bias ("Let's give it more time")
- Fear of admitting failure

### The Kill Criteria Solution

**Pre-mortem + Pre-commitment:**
1. Identify failure signals (pre-mortem)
2. Define specific actions for each signal (kill criteria)
3. Commit to taking those actions before launching
4. When signals appear, execute the pre-committed action

**Key insight:**
> "A pre-mortem is great, but only if you attach a pre-commitment with it. What a pre-mortem allows you to do is to set up kill criteria."

## Procedure

### Step 1: Run the Pre-Mortem
Imagine failure and identify signals.

**Pre-mortem prompt:**
> "Imagine it's [timeframe] from now and this project has failed completely. Looking back, what were the early signals that it was going to fail?"

**Collection method:**
- Collect independently (nominal group)
- Each person writes 3-5 signals
- Aggregate and deduplicate
- Discuss and prioritize

**Signal characteristics:**
- Observable (you can see it happen)
- Early (appears before full failure)
- Specific (not vague)
- Distinguishable (not normal variation)

### Step 2: Categorize Signals by Severity
Not all signals warrant the same response.

**Signal categories:**

| Category | Description | Example |
|----------|-------------|---------|
| **Red** | Fatal — should kill immediately | Customer won't demo, only discusses price |
| **Yellow** | Serious — requires intervention | Can't get decision-maker in room |
| **Orange** | Concerning — needs investigation | RFP written with competitor in mind |

### Step 3: Define Actions for Each Signal
Pre-commit to what you'll do.

**Action types:**

| Action | When to Use |
|--------|-------------|
| **Kill** | Signal is fatal, stop immediately |
| **Pivot** | Fundamentally change approach |
| **Investigate** | Gather more information before deciding |
| **Escalate** | Bring to leadership for decision |
| **Continue with changes** | Minor adjustments, proceed |

**Action requirements:**
- Specific and executable
- Has a clear owner
- Has a timeline
- Doesn't require additional approval (pre-approved)

### Step 4: Create Kill Criteria Document
Document the signals and actions.

**Template:**

```
PROJECT: [Name]
START DATE: [Date]
REVIEW DATE: [When to check criteria]

KILL CRITERIA:

Signal 1: [Description]
- Category: Red/Yellow/Orange
- Observable indicator: [What you'd actually see]
- Action if seen: [Specific action]
- Action owner: [Person]
- Timeframe: [When to act]

Signal 2: [Description]
- Category: Red/Yellow/Orange
- Observable indicator: [What you'd actually see]
- Action if seen: [Specific action]
- Action owner: [Person]
- Timeframe: [When to act]

[Continue for all signals...]
```

### Step 5: Commit Before Launch
Get explicit agreement on the criteria.

**Commitment ritual:**
1. Review kill criteria document with team
2. Each person confirms understanding
3. Each person confirms agreement to act
4. Document commitments
5. Set review checkpoints

**Why pre-commitment matters:**
> "Instead of hoping that when I see those signals I actually act rationally — which is a hope that will not come true — use the pre-mortem to create structure around those signals and commit to actions before you launch."

### Step 6: Monitor and Act
Regularly check for signals and execute actions.

**Monitoring cadence:**
- Set regular review points
- Include kill criteria in status updates
- Create early warning dashboards if possible
- Assign someone to watch for signals

**When signal appears:**
1. Acknowledge the signal (don't ignore)
2. Reference the kill criteria document
3. Execute the pre-committed action
4. Document the decision

**No debate when signal appears:**
The time for debate was when setting criteria. When the signal appears, execute the plan.

## Example: Sales Deal Kill Criteria

**Context:** Sales team pursuing enterprise deals

**Pre-mortem signals identified:**
1. RFP/RFI was clearly written with a competitor in mind
2. Customer doesn't want to demo, only discusses price
3. Can't get decision-maker in room after first few meetings

**Kill criteria document:**

```
Signal: Customer doesn't want to demo, only discusses price
- Category: Red
- Observable indicator: Customer declines demo request, immediately asks about pricing
- Action: Kill the deal — they're using us to beat up a competitor on price
- Action owner: AE
- Timeframe: Within 24 hours of signal

Signal: RFP was written with competitor in mind
- Category: Orange
- Observable indicator: RFP language matches competitor's feature names/descriptions
- Action: Ask directly if they're working with a competitor and how far along
- Follow-up: If >60% through process with competitor, kill; otherwise continue
- Action owner: AE with manager approval
- Timeframe: Within 48 hours

Signal: Can't get decision-maker in room
- Category: Yellow
- Observable indicator: After 3rd meeting, no executive sponsor present
- Action: Offer executive alignment meeting at next touchpoint
- Follow-up: If they decline, kill the deal
- Action owner: AE
- Timeframe: At 3rd meeting
```

## Example: Product Launch Kill Criteria

**Context:** Launching new product feature

**Pre-mortem signals and criteria:**

```
Signal: DAU below threshold after 2 weeks
- Category: Red
- Observable indicator: <1000 DAU after 2 weeks live
- Action: Kill feature, conduct user research on why
- Action owner: PM
- Timeframe: Week 3

Signal: Engagement metrics declining week-over-week
- Category: Yellow
- Observable indicator: >20% WoW decline in engagement
- Action: Pause rollout, investigate root cause
- Action owner: PM + Data
- Timeframe: Within 3 days of signal

Signal: High-severity bugs reported
- Category: Orange
- Observable indicator: >5 P1 bugs in first week
- Action: Pause rollout, triage bugs, decide continue/kill
- Action owner: Engineering lead
- Timeframe: Immediate
```

## Expected Outcomes
- Faster decisions to quit failing projects
- Less sunk cost influence
- More resources for winning initiatives
- Better project selection over time
- Reduced emotional decision-making

## Common Pitfalls

### Not pre-committing
- Setting criteria but not agreeing to act
- "We'll decide when we see it"
- Defeats the purpose
- Explicit commitment before launch is essential

### Criteria too vague
- "If it's not working"
- "If customers don't like it"
- Can't observe or measure
- Make criteria specific and observable

### No action owner
- "Someone should do something"
- No accountability
- Signal appears, no one acts
- Assign specific person to each action

### Renegotiating when signal appears
- "But the situation is different now"
- "Let's give it more time"
- Sunk cost taking over
- The time to debate was during criteria setting

### Not reviewing regularly
- Criteria set then forgotten
- Signals missed
- Include in regular reviews
- Create dashboards if possible

## Related SOPs
- Pre-Mortem Technique
- SPADE Decision Framework
- Project Milestone Reviews

## AI Integration Notes

### Context signals that should trigger this SOP:
- "Starting a new project"
- "Should we continue this?"
- "How do we know when to quit?"
- Project planning discussions

### How to apply:
- Run pre-mortem first
- Help define specific, observable signals
- Ensure actions are pre-committed
- Create documentation template

### Key insight:
Pre-mortems identify what could go wrong. Kill criteria commit you to action when it does. Without pre-commitment to specific actions, you'll rationalize continuing even when failure signals appear. Set the criteria before you launch, and execute without debate when signals appear.
