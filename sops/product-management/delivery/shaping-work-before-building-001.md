# Shaping Work Before Building

## Metadata
- **Source**: Ryan Singer - Lenny's Podcast
- **Domain**: Product Management & Delivery
- **Type**: Process
- **Applicable To**: Product Managers, Senior Engineers, Design Leads, CTOs
- **Difficulty**: Advanced

## Overview
Shaping is the collaborative work of defining both the problem boundaries and a concrete solution approach before committing engineering time. It involves product, senior engineering, and design working together in intensive sessions to create clarity around what will be built, de-risk technical unknowns, and ensure the solution fits within the time appetite.

## When to Use
- Before starting any significant feature development (3+ weeks of work)
- When engineering keeps coming back with "I don't know what to build"
- Projects consistently blow up mid-development with unexpected complexity
- Beautiful designs get rejected by engineering for being technically infeasible
- PRDs are written but no one really knows what to build from them
- You need to commit scarce engineering time and want high confidence in success

## Prerequisites
- Clear time appetite established (e.g., "we have 6 weeks maximum for this")
- Problem has been framed/narrowed down (see framing work in procedure)
- Senior engineer available who knows the codebase and technical constraints
- Product person who deeply understands the business context and customer need
- Designer who can sketch and iterate quickly in low fidelity
- 3-hour blocks of uninterrupted time for shaping sessions

## Procedure

### Step 1: Frame the Problem (Before Shaping Sessions)
Narrow down from broad concepts to specific problems:

**Don't start with:**
- "We need a calendar"
- "Build a dashboard"
- "Newsletter builder"

**Do narrow down to:**
- "Customers can't see empty time slots to schedule meetings"
- "Users lose key accounts data in scattered views"
- "Creators struggle to send one-time announcements vs recurring newsletters"

**Framing questions to ask:**
- What is the actual struggle customers are having?
- Where specifically is the value in solving this?
- What is the minimum meaningful version of this problem?
- Can we solve a slice of this that's still valuable?
- What are we explicitly NOT solving?

**Output of framing:**
- One sentence problem definition
- Understanding of who this is for
- Clarity on what success looks like
- Boundaries on what's out of scope

### Step 2: Assemble the Shaping Team
Bring the right people into the room:

**Required participants:**
- **Senior Engineer**: Not just senior in title, but the person who:
  - Knows where the "bodies are buried" in the codebase
  - Understands what's truly hard vs. easy in your infrastructure
  - Can open up the code and inspect during sessions
  - Will push back on infeasible ideas
  - Can suggest alternative technical approaches

- **Product Person**: Someone who:
  - Deeply understands the business context
  - Knows the customer backstory and research
  - Can explain why this matters
  - Can make trade-offs on value
  - Understands what the business will spend time on

- **Designer**: Someone who:
  - Can sketch quickly and iterate
  - Thinks through user flows and interactions
  - Can work in low fidelity
  - Understands experience implications

**Team size:**
- Keep it small: 3 people ideal, 4 maximum
- If the same person covers multiple roles (like technical designer), even better

### Step 3: Set Up the Shaping Session
Create the right environment:

**Time:**
- Block 3 hours for first session
- Be prepared to do 2-3 sessions total
- Sessions can be same day or spread across days with thinking time between

**Materials:**
- Whiteboard or large sheets of paper
- Markers (fat markers force low fidelity)
- Access to codebase for quick inspection
- Problem framing written where everyone can see it

**Mindset:**
- This is intense, fast-paced collaborative work
- We're trying to break ideas, not protect them
- We're going all the way to concrete ideas, not stopping at concepts
- We must face the blank page and try things together

### Step 4: Generate and Test Solution Approaches
Work through multiple ideas quickly:

**Try different approaches:**
- Draw idea A: "What if we had a scrolling agenda view?"
- Draw idea B: "What if it was just a month view with dots?"
- Don't get stuck in details of one idea for hours
- Step back and try fundamentally different approaches

**Test each idea from multiple angles:**

*Technical Angle:*
- "Can we actually build this with our current tech?"
- "Is this data available in our database?"
- "Does this work with our existing authentication system?"
- Open the code and look at the actual implementation

*Product/Value Angle:*
- "Does this actually solve the customer problem?"
- "If I play through the user scenario, does this deliver value?"
- "Are we making the easy technical choice but losing the benefit?"

*Feasibility Angle:*
- "Can this fit in our time budget?"
- "Are we introducing new algorithms or using existing frameworks?"
- "What are the rabbit holes/time bombs hiding here?"

**Home renovation analogy:**
"You can have the most beautiful rendering of lamps by the bed, but if you haven't checked if there's electricity in that wall, it drastically changes cost and time."

### Step 5: Get Concrete on the Moving Pieces
Shape until you can describe it in less than 10 pieces:

**Good test of well-shaped work:**
If you can describe the solution in 9 or fewer major components, it's probably well-shaped.

**Calendar example from transcript:**
1. Two-month grid view
2. Dots to indicate days with/without events
3. Agenda view that slides underneath
4. Tap day to show agenda
5. Navigation to go forward/back months
6. Create button to add events
7. View shows events scheduled in selected day

**Not well-shaped:**
- "A calendar where users can see availability"
- Requires x-ray vision to understand what to build
- Team still asking "but how does it actually work?"

**Well-shaped:**
- Specific UI elements named
- Flow between screens defined
- Data requirements clear
- Actions/interactions specified

### Step 6: Surface and Resolve Technical Risks
Use engineering presence to find time bombs:

**Example from transcript - Onboarding step:**
- Product idea: "Let's remove this onboarding step to improve conversion"
- Sounds simple and valuable
- Senior engineer checks code
- Discovers: That "one step" has 3 different branches for different bank integrations
- Now have real conversation: "Which branch is most valuable? Do all three? Trade-offs?"

**Questions to force concrete investigation:**
- "Let's take a quick look at the actual code for this"
- "Which screen/component are we actually talking about?"
- "What happens behind the scenes when this action occurs?"
- "Are there different cases or logic branches?"
- "Do we handle this differently for different customer segments?"

**Finding these in shaping vs. building:**
- In shaping: "Great, now we can make informed trade-offs about scope"
- In building (week 4): "We're screwed, project is blowing up"

### Step 7: Create Low-Fidelity Artifacts
Document with the right level of detail:

**Use these techniques:**

*Breadboarding:*
- Shows flow from action to action
- "Click this button → calculation runs → get this result → choice to go here or here"
- Text and arrows, not visual design
- Communicates logic and interaction clearly

*Fat Marker Sketches:*
- Forces high-level representation
- Can't get lost in pixel-pushing
- Must communicate the core idea
- "When I look at this, I get what we're building"

**Don't use (yet):**
- Figma files with high-fidelity designs
- Detailed PRDs with hundreds of requirements
- User stories split into tickets
- Polished mockups

**Why low-fidelity works:**
- Can collaborate quickly
- Easy to throw away and try different approach
- Forces clarity on the idea itself
- Engineering can see through to implementation

### Step 8: Validate the Output
Check if shaping is complete:

**Test with technical person:**
- Show the breadboard/sketches to an engineer
- Ask: "Do you know what to go build now?"
- If yes: Shaped well enough
- If no: More shaping needed

**Can the team create 9 or fewer implementation scopes?**
- At kickoff, team should be able to divide work into 9 major chunks
- 6 weeks = 30 business days ÷ 9 boxes = ~4 days per box
- If team sees 50 boxes, scope is too big or too unclear

**Reality check questions:**
- Do we believe this is doable in the time appetite?
- Have we de-risked the major technical unknowns?
- Is the problem-solution connection clear?
- Can we explain this without hedging ("maybe we'd have a...?")?

## Expected Outcomes
- Clear shared understanding across product, engineering, design
- Major technical risks surfaced and addressed before building starts
- Solution fits within time appetite
- Team can confidently say "I know what to build"
- Reduced back-and-forth during build phase
- Better trade-off decisions made before committing time
- Realistic expectations set with leadership

## Common Pitfalls
- **No engineer in shaping sessions**: Product and design create something beautiful that engineering rejects when they see it
- **Too high fidelity too soon**: Creating Figma files or detailed PRDs instead of collaborative sketching
- **Unclear problem framing**: Trying to shape "calendar" instead of "see empty time slots"
- **Going in circles on one idea**: Spending 3 hours on details of first idea instead of trying multiple approaches
- **Not checking actual code**: Assuming implementation is simple without looking
- **Creating blurry wireframes**: Low-fi sketches that don't actually communicate what to build
- **Wrong engineer in room**: Junior person who doesn't know the codebase or senior person who's disconnected
- **Asynchronous document passing**: Treating shaping like "write PRD, get comments, revise" instead of intensive collaboration
- **Skipping shaping to "save time"**: Leads to much longer build phase with constant confusion

## Related SOPs
- shape-up-methodology-overview-001.md
- appetite-based-scoping-001.md
- six-week-cycles-framework-001.md

## AI Integration Notes
When recommending shaping practices:
- Emphasize this is different from sprint planning or writing PRDs
- Highlight the importance of senior engineering involvement (not just any engineer)
- Note that 3-hour intensive sessions are more effective than weeks of async work
- Suggest starting with one pilot project to learn the muscle
- Adapt detail level based on team seniority (more for junior, less for senior)
- If designers can code or engineers do design, that's a huge advantage
- Warn against high-fidelity designs or detailed documents as shaping outputs
- The "home renovation" and "grumpy plumber" analogies help explain the concept
- Most common failure: doing time boxes without proper shaping
