# Six-Week Cycles vs. Sprint Framework

## Metadata
- **Source**: Ryan Singer - Lenny's Podcast
- **Domain**: Product Management & Delivery
- **Type**: Framework
- **Applicability**: Product Teams, Engineering Teams, Scrum Teams Looking for Alternatives
- **Difficulty**: Intermediate

## Overview
Six-week cycles (or time boxes) provide an upper limit on project duration that forces meaningful scoping decisions while giving teams enough time to build substantial features. Unlike two-week sprints, six weeks allows teams to see the end from the beginning, work with minimal meetings, and ship complete features rather than incremental progress.

## When to Use
- Building features substantial enough to be meaningful to customers
- Need to reduce meeting overhead and ritual burden
- Want teams to have creative freedom within clear boundaries
- Projects keep extending sprint after sprint with no clear end
- Two-week sprints feel too short to accomplish meaningful work
- Need to set realistic expectations with leadership about completion

## Prerequisites
- Well-shaped work ready to hand to team (see shaping-work-before-building-001.md)
- Ability to protect team from interruptions during the cycle
- Clear problem definition and solution approach
- Senior engineering able to make architectural choices that reduce dependencies
- Team has or can develop skills to break work into their own tasks

## Procedure

### Step 1: Understand Why Six Weeks is the Maximum
The six-week ceiling serves specific purposes:

**Why six weeks, not longer:**
- Six weeks is the longest you can realistically foresee and plan
- Beyond six weeks, too many unknowns and "ticking time bombs"
- Can't get arms around all problems that must be solved in 6+ months
- Forces asking "what piece can we really land?"
- Creates meaningful pressure to scope properly

**Why six weeks, not shorter (for feature work):**
- Very few substantial features can be completed in 2 weeks
- Two-week cycles lead to endless "one more sprint" syndrome
- Can't see the end, just keep taking one bite at a time
- Six weeks is "long enough chunk to actually get somewhere"
- Allows building something meaningful enough to sell

**Flexibility:**
- Six weeks is a maximum, not a requirement
- Growth teams might work in 1-2 week chunks
- Core features often need 4-6 weeks
- Can have different time boxes back-to-back without fixed cadence

### Step 2: Decide Between Cycles and Time Boxes

**Use Fixed Cycles (Regular Cadence) When:**
- You have multiple parallel teams
- Need to reduce management overhead
- Benefit from regular rhythm for planning
- Want synchronized cool-down periods between cycles
- Example: 4 weeks + 2 weeks cool-down = 6-week cycle aligning to quarters

**Use Variable Time Boxes When:**
- Small team (1-2 teams only)
- Projects naturally vary in size
- Can plan one after another without fixed dates
- More flexibility in responding to business needs
- Example: 3-week project, then 6-week, then 2-week

**Key principle:**
Time must push back at you - the constraint creates good forcing functions regardless of whether it's a cycle or time box.

### Step 3: Set Up the Kickoff

**Different from Sprint Planning:**

*Scrum Sprint Planning:*
- Product owner creates tickets
- Team reviews pre-made backlog
- Estimates work created by others
- Commits to completing tickets

*Shape Up Kickoff:*
- Present the shaped work (the whole idea)
- Team sees the complete problem and solution approach
- Team creates their own implementation tasks
- Team commits to shipping something meaningful

**Kickoff Exercise - The Nine Box Method:**
1. Share what was shaped with the team
2. Give team a grid with 9 boxes
3. Ask: "What are the 9 major chunks of implementation?"
4. Team translates shaped work into implementation scopes

**Why nine boxes:**
- Based on "7 plus or minus 2" cognitive science principle
- Ensures team has concrete picture of work
- Six weeks = 30 business days ÷ 9 boxes = ~4 days per box
- If team comes up with 50+ boxes, scope is too large
- Forces team to think in meaningful chunks, not tiny tickets

**Benefits of nine-box exercise:**
- Clarity on whether scope is realistic
- Junior engineers can describe approach, seniors can coach
- Team creates their own tasks (ownership)
- Surface if something was misunderstood in shaping

### Step 4: Minimize Rituals During the Build

**Don't carry over Scrum ceremonies:**
- No daily standups (unless team finds them helpful)
- No sprint retrospectives at fixed intervals
- No mandatory demo days
- Meet as needed, not on ritual cadence

**Why less meetings work:**
- Team has clarity from shaping (knows what to build)
- Team has ownership (created their own tasks)
- Time pressure creates natural urgency
- Creative work happens in flow, not status updates

**What replaces rituals:**
- Workshop sessions when needed to solve problems
- Ad-hoc conversations when blocked
- Senior engineer available for guidance
- Product person available for value trade-offs

**From transcript:**
"I'm getting tired of having so many meetings and rituals that are not actually working on the problem. The team is just going to be cooking for six weeks, buzzing and humming like a happy bee colony."

### Step 5: Handle the End of the Time Box

**Three Possible Outcomes:**

**1. Project Ships Successfully**
- Celebrate the launch
- Team feels accomplishment
- Build trust for future cycles
- Learn what helped it succeed

**2. Close to Done, Minor Cuts Acceptable**
- Ship with small scope reductions
- Ensure core value is preserved
- Don't cut what made the project worthwhile
- Better to extend slightly than ship broken value

**3. Not on Track, Can't See the End**
- DO NOT just extend the deadline
- DO NOT just cut scope arbitrarily
- DO pull project back into shaping mode

**Handling Projects That Aren't Finishing:**

From transcript: "We can't just keep reinvesting in something that we don't understand. Take this out of build mode and bring this back into shaping mode."

**Steps when project is off track:**
1. Stop the build clock
2. Different people (may include some same people)
3. Different type of work (shaping, not building)
4. Ask different questions:
   - What is fuzzy here?
   - What couldn't we see?
   - What don't we understand?
   - What time bombs did we miss?
5. Re-shape before re-committing time

**The Circuit Breaker (Advanced/Optional):**
- Basecamp principle: Cancel projects that don't finish in time box
- Most teams don't have stomach for this
- More realistic: Don't keep building, return to shaping
- Understand what went wrong before trying again

### Step 6: Adapt to Company Context

**At Larger Companies:**
When other teams operate on quarterly cadence:

*Option A: Align to quarters*
- Example: 5-week cycles + 1-week cool-down = 6 weeks
- Three cycles = one quarter
- Makes reporting easier

*Option B: Continuous delivery*
- Keep shipping complete features on your cadence
- Report completion, not "in progress"
- From transcript: "When you are consistently saying 'We said we were going to do this and it finished,' that's what everyone wants to see. That movement."
- If you're shipping reliably, people leave you alone

**Handling Dependencies:**
- Senior engineering untangles architectural dependencies
- "It's actually not inevitable. Good engineering leadership untangles things."
- Work on systems independently of other systems
- Protect team from being pulled onto other work during time box

**Managing Stakeholders:**
- Shape work addresses business needs upfront
- Time box commits to solving problem, not building forever
- Leadership gets yes/no on completion, not maybes
- Consistent shipping builds trust to operate this way

### Step 7: Know When Team is Ready for Six-Week Cycles

**Team is ready when:**
- Senior engineering leadership can protect time
- Product and engineering aligned on need to change
- Can shape work with sufficient detail
- Team has mix of skills (some senior presence)
- Leadership frustrated with current lack of shipping

**Team is NOT ready when:**
- Can't get engineering and product in same room to shape
- No pain with current process
- No senior engineer who knows the codebase
- Can't protect team from constant interruptions
- Unfamiliarity is the biggest concern (not shipping pain)

**From transcript:**
"I would say wait until it hurts more. If the unfamiliarity is the big problem, then maybe things are fine. Changing is really hard, and if there's a good reason to do it... but we can't continue this way."

## Expected Outcomes
- Complete, shippable features at end of time boxes
- Reduced meeting overhead compared to sprint ceremonies
- Team has creative freedom within clear boundaries
- Morale improvement from seeing work reach completion
- Engineering feels ownership, not ticket completion
- Leadership gets clear completion status
- Better use of scarce engineering time

## Common Pitfalls
- **Adopting six-week cycles without shaping**: Team gets time but no clarity, leads to chaos
- **Artificially bundling small work into six weeks**: Growth teams forcing short projects into long cycles
- **Extending every time box**: Defeats the purpose of the constraint
- **Cutting core scope to claim completion**: Kills morale, feels like failure
- **Continuing Scrum rituals**: Keeping all the meetings defeats the benefit
- **No senior engineering involvement**: Junior team can't handle the autonomy
- **Treating six weeks as estimate**: It's a budget/appetite, not a timeline to exceed

## Related SOPs
- shape-up-methodology-overview-001.md
- shaping-work-before-building-001.md
- appetite-based-scoping-001.md

## AI Integration Notes
When recommending six-week cycles:
- First check if work is well-shaped (if not, shaping is the first problem)
- Emphasize six weeks is a maximum, not every project needs to be six weeks
- For growth teams, may not be appropriate (1-2 week work is fine)
- Highlight the difference from sprints: whole ideas vs. tickets
- Note that less meetings only works because of better upfront clarity
- If team is used to two-week sprints, may be uncomfortable at first
- The constraint is what creates value, not the specific number
- Larger companies can run this within teams without company-wide adoption
- Most valuable for feature development, less so for continuous growth optimization
