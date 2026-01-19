# Appetite-Based Scoping Framework

## Metadata
- **Source**: Ryan Singer - Lenny's Podcast
- **Domain**: Product Management & Delivery
- **Type**: Framework
- **Applicable To**: Product Managers, Engineering Leads, Executives, Product Teams
- **Difficulty**: Intermediate

## Overview
Appetite-based scoping flips traditional project planning on its head by starting with how much time the business is willing to invest, then working backward to define what can be built in that time. Instead of estimating scope and hoping it fits, you fix time and vary scope through creative problem-solving and trade-offs.

## When to Use
- Before starting any feature development or project planning
- When estimates consistently prove wrong and projects overrun
- Projects need executive buy-in on time investment
- Engineering time is scarce and contested
- Need to make hard trade-offs between competing ideas
- Want to set realistic expectations from the start
- Evaluating whether a feature idea is worth pursuing

## Prerequisites
- Understanding of business priorities and constraints
- Willingness to negotiate scope, not just accept requests
- Senior engineering who can evaluate feasibility
- Product sense to identify minimum valuable version
- Ability to say no to scope that doesn't fit appetite

## Procedure

### Step 1: Understand the Appetite Concept

**Traditional Approach (Estimating):**
1. Define full desired scope
2. Create detailed designs/requirements
3. Ask engineering for estimate
4. Hope it fits available time
5. Extend timeline when estimate is wrong

**Appetite Approach (Time-Boxing):**
1. Determine maximum time willing to spend
2. Work backward to define what's possible
3. Creatively vary scope to fit the time
4. Make trade-offs during shaping, not during building
5. Only commit when confident it fits appetite

**Key Mindset Shift:**
- Appetite is not a deadline (external pressure)
- Appetite is a budget (intentional allocation)
- Question changes from "How long?" to "What's it worth?"

**From transcript:**
"We are not going to start something unless we can see the end from the beginning. We're not going to take a big concept and then say, 'What's the estimate for this thing?' We're going to go the other way around and say, 'What is the maximum amount of time we're willing to go before we actually finish something?'"

### Step 2: Set the Appetite

**Determine Business Time Budget:**

Ask the right questions:
- What is this opportunity worth to the business?
- How much engineering time can we justify spending?
- What else could we build with that same time?
- When do we need to see results?
- What's the maximum time before this becomes not worth it?

**Common Appetites:**
- **Small batch (1-2 weeks)**: Quick wins, small improvements, growth experiments
- **Standard (3-4 weeks)**: Meaningful feature additions, improvements
- **Large (5-6 weeks)**: Substantial features, new capabilities

**Six-week maximum rule:**
- Six weeks is the longest you can realistically plan and foresee
- Beyond that, too many unknowns emerge
- Forces asking "what slice can we actually finish?"

**Appetite factors:**
- Business value of solving the problem
- Urgency of the need
- Competitive pressure
- Available engineering capacity
- Other priorities in the pipeline

### Step 3: Frame the Problem Within Appetite

**Start Broad, Then Narrow:**

*Too broad (infinite scope):*
- "Build a calendar"
- "Create a dashboard"
- "Add social features"

*Appropriately framed (fits appetite):*
- "Let users see empty time slots for scheduling" (Calendar problem)
- "Show top 3 metrics for daily check-in" (Dashboard problem)
- "Allow @mentions in comments" (Social problem)

**Framing Questions:**
- What is the core struggle we're addressing?
- What's the minimum that would be valuable?
- What are we explicitly NOT solving?
- Can we solve a meaningful slice vs. the whole thing?

**Example from transcript - Calendar:**
- Don't: Build full Google Calendar competitor
- Do: Focus on seeing empty spaces (specific customer request)
- Narrows from unlimited scope to solvable problem

**Bob Moesta Quote Applied:**
"You can't put 10 pounds of crap in a five pound bag."
- Can't take any giant project and throw it at team saying "figure it out in six weeks"
- Must do framing work to match problem to appetite

### Step 4: Make Trade-Offs During Shaping

**Use Appetite as Decision Filter:**

When shaping the solution (see shaping-work-before-building-001.md), the appetite forces good trade-offs:

**Example from transcript - Bank Integration:**
- Problem: Remove onboarding step to improve conversion
- Discovery: That step has 3 different branches for different banks
- Without appetite: "Let's do all three branches perfectly"
- With appetite (say, 3 weeks):
  - Which branch covers most customers?
  - Could we ship one branch first?
  - Is doing all three worth 6 weeks instead?
  - Is there a different approach that works for all three?

**Trade-Off Framework:**

*Compare options against appetite:*
- Approach A: Covers 80% of users, fits in 3 weeks
- Approach B: Covers 100% of users, needs 7 weeks
- Approach C: Different UX that covers 100% in 4 weeks

*Make intentional choice:*
- Is the extra coverage worth extra time?
- Can we ship A now and B later?
- Is C's different UX acceptable?

**The Budget Analogy:**
From transcript: "It's like if you're going to buy a car or rent a flat, you have to have a budget in mind. The budget is how you choose between alternatives and make hard choices and trade-offs. I want the faster engine, but I have to give this up, or I want it to be fun to drive, but we also need space for longer road trips."

### Step 5: Validate Scope Fits Appetite

**During Shaping, Continuously Check:**

*Can describe in less than 10 pieces?*
- If shaped well, can list 9 or fewer major components
- Example: "Two-month grid, dots for events, agenda view that slides under, navigation, create button"
- If you have 50 pieces, scope is too big

*Senior engineer believes it's feasible?*
- Technical person says "yes, I see how to build this"
- Not "maybe" or "we'll see"
- Major technical risks have been surfaced and addressed

*Team can break into ~9 implementation chunks?*
- At kickoff, team should identify 9 or fewer major scopes
- 30 days ÷ 9 = about 4 days per chunk
- If team sees 100 tasks, red flag on scope

*Can explain without hedging?*
- "It's this, this, and this" (confident)
- Not "We'll probably have... maybe... we'll figure out..." (unclear)

### Step 6: Hold the Line on Appetite

**During the Build:**

*If project is on track:*
- Team making good progress
- End is visible
- Trade-offs being made within shaped scope
- Let team continue

*If project is off track:*
- Don't automatically extend time
- Don't arbitrarily cut core scope
- Pull back to shaping mode
- Understand what was unclear/fuzzy
- Re-evaluate if it's still worth the investment

**What NOT to do:**
- "We estimated 4 weeks but it's actually 8, so let's extend"
- This defeats the entire purpose of appetite
- Returns to estimation-based planning
- Loses forcing function of constraint

**What TO do:**
- "We thought this was 4 weeks of value, but we were wrong"
- "Let's understand what we missed"
- "Is this still worth it with better information?"
- "Should we re-shape to fit original appetite?"
- "Should we increase appetite based on new understanding of value?"

### Step 7: Communicate in Appetite Terms

**With Leadership:**

*Don't say:*
- "This will take 6-8 weeks" (estimate)
- "We're 60% done" (meaningless percentage)
- "We need more time" (open-ended)

*Do say:*
- "We're willing to spend 4 weeks on this" (appetite)
- "We've shaped it to fit in 4 weeks" (commitment)
- "It shipped / it didn't ship" (clear outcome)
- "We need to re-shape based on what we learned" (taking ownership)

**With Stakeholders:**

*Frame requests in appetite terms:*
- Stakeholder: "We need a complete dashboard"
- Response: "What would make a dashboard valuable enough to justify 6 weeks?"
- Or: "What could we do in 2 weeks that would be a meaningful first step?"

**With Team:**

*Make the constraint generative:*
- Not: "You only get 4 weeks, good luck"
- Instead: "We have 4 weeks, what's the most valuable thing we can ship?"
- The constraint creates focus and creativity

### Step 8: Refine Appetite Setting Over Time

**Learn from Projects:**

*Track patterns:*
- What appetites proved realistic?
- What types of work took longer than expected?
- What time bombs frequently surprise us?
- What technical areas are less predictable?

*Adjust calibration:*
- Maybe your "4-week" appetite is really 6 weeks for your codebase
- Certain types of features might need larger appetites
- Some areas of the product are faster to work in

*Build track record:*
- Consistent shipping builds confidence
- Leadership trusts appetite-setting judgment
- Team learns to shape to appetites effectively

## Expected Outcomes
- Realistic project scoping from the start
- Hard trade-offs made during planning, not during crunch time
- Engineering time used intentionally, not accidentally
- Clear go/no-go decisions based on value vs. time
- Fewer scope surprises mid-project
- Better alignment between business and engineering
- More disciplined product decisions

## Common Pitfalls
- **Treating appetite as soft deadline**: Saying "4-week appetite" but expecting it to flex to 8 weeks
- **Not doing framing work first**: Trying to shape "build calendar" with a 6-week appetite
- **Skipping the shaping**: Setting appetite but not working backward to define feasible scope
- **Appetite without engineering input**: Product sets 2-week appetite for 6-week work
- **Always extending appetites**: Defeats the forcing function if you always give in
- **Making appetite too small**: Forcing meaningful work into unrealistic time boxes
- **Confusing appetite with estimate**: Appetite is what you're willing to spend, not what it "should" take
- **Not communicating what appetite means**: Team thinks it's a deadline, not a budget

## Related SOPs
- shape-up-methodology-overview-001.md
- shaping-work-before-building-001.md
- six-week-cycles-framework-001.md

## AI Integration Notes
When recommending appetite-based scoping:
- First check if user is struggling with estimates or timeline overruns
- Explain this is fundamentally different from estimation
- Emphasize the need to work backward from time to scope
- Highlight that framing and shaping are required, not optional
- Note that appetites should be realistic business decisions, not arbitrary
- Six weeks is a maximum for planning horizon, not every project
- The constraint is what creates value, not punishment
- Most common mistake: Setting appetite but not actually shaping to it
- If organization requires estimates, appetites may be challenging to introduce
- Works best when product and engineering leadership both embrace it
