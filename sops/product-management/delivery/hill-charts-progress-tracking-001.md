# Hill Charts for Progress Tracking

## Metadata
- **Source**: Ryan Singer - Lenny's Podcast / Shape Up Methodology
- **Domain**: Product Management & Delivery
- **Type**: Tool/Technique
- **Applicable To**: Product Teams, Engineering Teams, Project Managers, CTOs
- **Difficulty**: Beginner

## Overview
Hill charts are a visual progress tracking tool that represents work moving through two distinct phases: the uphill phase of figuring things out (unknowns, problem-solving) and the downhill phase of execution (knowns, implementation). Unlike percentage-complete metrics, hill charts communicate the nature of remaining work and confidence in completion.

## When to Use
- Tracking progress during a time-boxed project or cycle
- Communicating status to leadership without detailed status meetings
- Identifying when work is stuck in "figuring it out" mode
- Surfacing risks and blockers earlier than traditional tracking
- Replacing meaningless "60% done" style progress reports
- When building with sufficient autonomy (Shape Up style cycles)

## Prerequisites
- Work broken into meaningful scopes (not tiny tickets)
- Ideally 9 or fewer major scopes per project
- Team understands the distinction between "figuring out" and "executing"
- Project management tool that supports hill charts (Basecamp, Shortcut, or custom)
- Team autonomy to work through problems vs. escalating immediately

## Procedure

### Step 1: Understand the Hill Chart Concept

**The Hill Metaphor:**

```
      Peak
     /    \
    /      \
   /        \
  /          \
Uphill     Downhill
(Unknown)  (Known)
```

**Two Distinct Phases:**

*Uphill (Left side):*
- Figuring things out
- Unknowns and uncertainty
- Problem-solving and exploration
- Spiking and prototyping
- Understanding scope
- Discovering hidden complexity

*Peak (Top of hill):*
- Transition point
- Scope is understood
- Path forward is clear
- Confidence in completion
- Ready to execute

*Downhill (Right side):*
- Executing known work
- Uncertainty resolved
- Implementation happening
- Steady progress
- Completion visible

**Why This Matters:**

Traditional tracking: "We're 60% done"
- Doesn't tell you if remaining 40% is known or unknown
- Could mean 4 more hours or 4 more weeks
- Hides risk and uncertainty

Hill chart: "This scope is 60% up the hill"
- Tells you work is still in figuring-out phase
- Remaining work is uncertain
- May need attention or help
- Not ready to commit to timeline

### Step 2: Break Work Into Scopes

**Before Using Hill Charts:**

Create meaningful scopes, not micro-tasks:
- **Good scope**: "Two-month calendar grid view"
- **Good scope**: "Agenda slide-up interaction"
- **Good scope**: "Event creation flow"

- **Bad scope (too small)**: "Add CSS for button"
- **Bad scope (too large)**: "Entire calendar feature"

**Ideal Number:**
- 9 or fewer scopes per project
- Aligns with "seven plus or minus two" cognitive limit
- Each scope is substantial enough to track separately
- Each scope can move independently on the hill

**Example from Shape Up:**
A 6-week project might have scopes like:
1. Calendar grid UI
2. Event data model
3. Navigation between months
4. Agenda view component
5. Create event interaction
6. Edit event interaction
7. Integration with existing schedule system
8. Mobile responsive layout
9. Performance optimization

### Step 3: Place Scopes on the Hill at Kickoff

**Initial Placement:**

At project start, most scopes begin at the bottom of the uphill:
- Haven't started figuring them out yet
- Unknowns to discover
- Path not yet clear

**Some Scopes Might Start Higher:**
- Well-understood patterns used before
- Clear implementation path from shaping
- Minimal uncertainty

**Don't Assume Placement:**
- Let team place scopes based on their understanding
- Some "simple" scopes may have hidden complexity
- Some "complex" scopes may be well-understood

### Step 4: Update Hill Positions Regularly

**Update Cadence:**
- Daily or every few days (not real-time)
- Async updates, not in meetings
- Takes minutes, not hours
- Team members move their own scopes

**Moving Up the Hill:**

*Scope moves uphill when:*
- Learning about the problem
- Trying different approaches
- Discovering edge cases
- Understanding requirements
- Prototyping solutions

*Signs scope is moving up:*
- Questions being answered
- Unknowns becoming knowns
- Clarity increasing
- Path forward emerging

**Reaching the Peak:**

*Scope reaches peak when:*
- All major unknowns resolved
- Path to completion is clear
- Confidence in finishing is high
- Just needs execution now

*Critical question:*
- "Do I know how to finish this?"
- If yes: Ready to go downhill
- If no: Still uphill work to do

**Moving Down the Hill:**

*Scope moves downhill when:*
- Executing against known plan
- Making steady progress
- No surprises expected
- Completion visible

*Signs scope is moving down:*
- Code being written
- Tests being added
- Features coming together
- Work remaining is clear

### Step 5: Interpret Hill Chart Patterns

**Healthy Patterns:**

*Early in project:*
- Most scopes at bottom or moving up
- Natural discovery happening
- Team figuring things out

*Mid project:*
- Some scopes reaching peak
- Some scopes moving downhill
- Progress across multiple fronts

*Late in project:*
- Most scopes downhill
- Few or no scopes still uphill
- Clear path to completion

**Warning Patterns:**

*Scope stuck uphill for too long:*
- Signal: Hasn't moved in several days
- Meaning: Team is blocked or struggling
- Action: Discuss, provide help, or rescope

*Scope oscillating (up and down):*
- Signal: Moving down then back up
- Meaning: Thought it was figured out, but wasn't
- Action: Need more uphill time, may need shaping help

*Everything still uphill late in cycle:*
- Signal: No scopes reaching peak with limited time left
- Meaning: Project was under-shaped or scope too large
- Action: May need to pull back to shaping mode

*Scope moving downhill too fast:*
- Signal: Went from start to done quickly
- Meaning: Either well-understood or being rushed
- Action: Verify quality, ensure not skipping important work

### Step 6: Use Hill Charts for Communication

**With Leadership:**

*Instead of:*
- "We're 65% done" (meaningless)
- "On track" (vague)
- "Some blockers" (unclear)

*Say:*
- "5 scopes are downhill, 3 are at peak, 1 is stuck uphill"
- "Calendar grid was more complex than we thought, still uphill"
- "Event creation cleared the peak, should finish this week"

**Benefits:**
- Shows real progress, not just time elapsed
- Surfaces risks early
- Builds confidence or appropriate concern
- No need for detailed status meetings

**With Team:**

*Daily/weekly check-ins:*
- "What moved this week?"
- "What's stuck uphill?"
- "What needs help to get over the peak?"
- "What's ready to move downhill?"

*Asynchronous visibility:*
- Everyone sees what everyone is working on
- Can offer help when scopes are stuck
- Celebrate scopes reaching downhill
- Identify bottlenecks without meetings

### Step 7: Make Decisions Based on Hill Position

**Scope is Stuck Uphill:**

*Options:*
1. **Provide help**: Pair programming, bring in expert
2. **Simplify scope**: Cut features to reduce unknowns
3. **More shaping**: Needs clearer direction before building
4. **Kill scope**: Not essential, other work more important

**Too Many Scopes Still Uphill Late in Cycle:**

*Options:*
1. **Re-evaluate time box**: Not realistically completable
2. **Cut scopes**: Ship with reduced scope
3. **Return to shaping**: Project wasn't ready
4. **Extend** (rarely): Only if core value intact and business agrees

**All Scopes Downhill Early:**

*Interpretation:*
- Project was well-shaped
- Scope was realistic
- Team is executing well
- May finish early or add scope

### Step 8: Combine with Other Progress Indicators

**Hill Charts + To-Do Lists:**
- Hill chart: High-level scope progress
- To-dos: Specific tasks within each scope
- Use together for complete picture

**Hill Charts + Demos:**
- Show what's downhill in working demos
- Explain what's uphill and why
- Give stakeholders confidence or appropriate concern

**Hill Charts + Retrospectives:**
- Review what caused scopes to get stuck
- Learn patterns of underestimated complexity
- Improve shaping for next cycle

## Expected Outcomes
- Better visibility into real progress vs. time elapsed
- Earlier identification of stuck or risky work
- More honest communication about uncertainty
- Less time in status meetings
- Better calibration of shaping over time
- Team feels ownership over progress reporting
- Leadership has realistic expectations

## Common Pitfalls
- **Moving scopes on calendar, not on understanding**: "It's day 10, so it must be 30% up the hill"
- **Faking progress**: Moving scopes downhill prematurely to look good
- **Too many scopes**: 50+ scopes makes hill chart meaningless
- **Too few scopes**: 2-3 scopes doesn't give enough granularity
- **Not discussing stuck scopes**: Chart shows problem but team doesn't act
- **Ignoring uphill time**: Treating all uphill as waste instead of necessary discovery
- **Using for micro-management**: Questioning every scope movement instead of trusting team
- **Treating it as deadline**: "You must get this downhill by Friday"

## Related SOPs
- shape-up-methodology-overview-001.md
- six-week-cycles-framework-001.md
- shaping-work-before-building-001.md

## AI Integration Notes
When recommending hill charts:
- Best suited for teams with some autonomy and trust
- Requires work broken into meaningful scopes (9 or fewer)
- Most valuable in time-boxed projects with clear endpoints
- Not well-suited for continuous maintenance or support work
- Complements Shape Up methodology but can be used independently
- The "stuck uphill" pattern is the most valuable early warning signal
- Don't recommend if work is already broken into hundreds of tiny tasks
- Works better with team self-reporting than external tracking
- Visual nature makes it great for async teams
- Available in Basecamp, Shortcut (formerly Clubhouse), and other tools
- Can be simulated in spreadsheets or simple diagrams if needed
