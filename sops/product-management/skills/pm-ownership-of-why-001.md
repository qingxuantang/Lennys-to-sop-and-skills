# PM Ownership of the "Why" Framework

## Metadata
- **Source**: Yuhki Yamashita (CPO, Figma) - Lenny's Podcast
- **Domain**: Product Management - Role Definition
- **Type**: Framework
- **Applicable To**: Product Managers (all levels), Product Leaders, Cross-functional Teams
- **Difficulty**: Intermediate

## Overview
While PMs don't need to come up with every idea (the "what") or specify every implementation detail (the "how"), they must uniquely own the "why" behind product decisions. Understanding and communicating the "why" enables teams to scale by empowering everyone to make great local decisions aligned with the product vision.

## When to Use
- When defining the PM's role in your organization
- When teams are struggling to make consistent decisions
- When engineers and designers are asking for more autonomy
- When you need to scale decision-making beyond yourself
- When dealing with customer feature requests
- When conducting post-mortems or retrospectives
- When writing product specs or PRDs

## Prerequisites
- Understanding of your product and customer problems
- Access to customer feedback and data
- Collaboration with design and engineering teams
- Context on business goals

## Procedure

### Step 1: Understand the Origin Story
**Why "owning the why" matters:**

At Microsoft (traditional culture):
- PMs wrote detailed specs that specified exactly how everything works
- Specs had to be perfect
- Tables specified every error handling scenario
- This doesn't scale beyond small feature crews

At YouTube/Google (scaling culture):
- Responsible for entire app with large teams
- Can't specify everything
- Designers and engineers make their own choices
- Need a different way to ensure great decisions

**The insight**: If everyone understands WHY you're doing something and WHAT problem you're solving, they can make really great local decisions. This is the only way to scale.

### Step 2: Apply the "Five Whys" to Customer Requests
**Purpose**: Go deeper than surface-level feature requests

When a customer asks for a feature:
1. **Why** are they asking for it? → Understand the problem
2. **Why** do they have that problem? → Find root cause
3. **Why** does that root cause exist? → Identify underlying condition
4. **Why** is that condition happening? → Discover systemic issues
5. **Why** does that systemic issue persist? → Find the biggest opportunity

**Key insight**: By fixing the underlying condition that created the problem in the first place, you can make a much bigger product impact.

**Example**: Engineering teams at Figma use "five whys" for post-mortems to find root causes of outages, not just surface issues.

### Step 3: Enable Decentralized Decision-Making
**Purpose**: Scale your influence through clarity of purpose

**What PMs should specify:**
- ✅ WHY we're building this (the problem, the customer need, the opportunity)
- ✅ WHAT success looks like (outcomes, not outputs)
- ✅ WHO we're solving for (customer segments, use cases)
- ✅ WHEN this matters (urgency, priority)

**What PMs should NOT specify:**
- ❌ Exact implementation details (let engineers decide)
- ❌ Every UI element (let designers decide)
- ❌ Every edge case (teams can figure it out with the "why")
- ❌ The specific solution (the "what" is shared across the team)

**The test**: Can an engineer or designer make a good decision about error handling without asking you? If they understand the "why," the answer should be yes.

### Step 4: Communicate the "Why" at Multiple Levels

**Level 1: Project Why**
- Why this project matters to customers
- Why it matters to the business
- Why now vs. later

**Level 2: Feature Why**
- Why this feature within the project
- Why this approach vs. alternatives
- Why these trade-offs

**Level 3: Decision Why**
- Why we chose option A over B
- Why we're comfortable with certain limitations
- Why we're prioritizing certain use cases

**Example format for communication:**
- "We're building [WHAT] because [WHY - customer problem]"
- "This matters because [WHY - business impact]"
- "We're doing it now because [WHY - timing/opportunity]"

### Step 5: Test for "Why" Clarity
**Methods to verify your "why" is understood:**

**The Hallway Test:**
- Stop an engineer or designer in the hallway
- Ask: "Why are we building this?"
- Can they articulate the customer problem and business reason?

**The Decision Test:**
- Present a hypothetical edge case
- Ask: "How would you handle this?"
- Is their reasoning aligned with the "why"?

**The Retro Test:**
- In retrospectives, ask: "Did we solve the right problem?"
- Can the team articulate what problem you were solving?

**Red flags:**
- Team members cite the "what" (features) instead of "why" (problems)
- Different team members give different reasons
- People can't explain why this matters to customers

### Step 6: Own the "Why" in Controversial Decisions

**When decisions are controversial:**
- Present both sides of the conflict
- Explain the underlying "why" behind each perspective
- Show how the "why" led to the decision
- Help everyone understand the reasoning, even if they disagree

**Interview question that tests this:**
"Describe a controversial product decision you were part of and what you did."

**Good answers demonstrate:**
- Clear articulation of the conflict
- Understanding of why the problem mattered
- Fair representation of all perspectives
- How the "why" informed the resolution

## Expected Outcomes
- Teams make better decisions independently
- Fewer questions about edge cases and implementation details
- More consistent decisions across the product
- Faster execution (less need for PM approval)
- Engineers and designers feel more empowered
- Product quality improves through aligned decision-making
- You can scale beyond your personal capacity

## Common Pitfalls

### Pitfall 1: Confusing "Why" with "What"
**Problem**: Stating the feature instead of the problem.
**Example**: "Why are we building this? To add collaborative editing."
**Solution**: Go deeper: "We're enabling real-time collaboration because designers are currently blocked by serial handoff processes that slow iteration cycles by 50%."

### Pitfall 2: Multiple "Whys" Creating Confusion
**Problem**: Having too many reasons that pull in different directions.
**Solution**: Prioritize one primary "why" with supporting secondary reasons. Be clear about trade-offs.

### Pitfall 3: Not Validating Understanding
**Problem**: Assuming everyone understood your explanation.
**Solution**: Use the hallway test and decision test regularly. Ask team members to explain the "why" back to you.

### Pitfall 4: Owning "How" When You Should Own "Why"
**Problem**: Getting pulled into implementation debates and losing sight of the problem.
**Solution**: Redirect conversations to the "why" first. "Before we decide how to build this, let's confirm we're solving the right problem."

### Pitfall 5: Weak "Whys" That Don't Inspire
**Problem**: Generic reasons like "customers asked for it" or "it's best practice."
**Solution**: Go deeper with five whys. Find the compelling underlying need.

## Related SOPs
- pm-storytelling-synthesis-001.md (How to communicate the "why" effectively)
- five-whys-root-cause-analysis-001.md (Engineering technique applied to PM)
- product-review-best-practices-001.md (Presenting the "why" in reviews)
- empowered-product-team-transformation-001.md (Creating empowered teams through clarity)

## Real-World Examples

### Example 1: Figma's Multiplayer Editing
**Surface request**: "We need collaborative editing"
**First why**: Why? → Designers waste time on handoffs
**Second why**: Why do handoffs waste time? → No visibility into each other's work
**Third why**: Why no visibility? → Design was historically single-player
**Fourth why**: Why single-player? → Tools were built for desktop isolation
**Deep why**: We need to fundamentally change how design teams work together by making the entire process transparent and collaborative

### Example 2: Error Handling at Scale
**Microsoft approach**: Table specifying every error scenario
**Google/Figma approach**: "We're building for professional designers who need to trust the tool won't lose their work. When errors happen, prioritize data integrity over speed, and always give users clarity about what happened."

Result: Engineers and designers can make good error handling decisions without detailed specs.

### Example 3: YouTube App iOS
When Yuhki led YouTube iOS app:
- Couldn't specify everything for a big team
- Had to rely on designers and engineers making local choices
- Success depended on everyone understanding WHY they were making the app better
- The "why" became the scaling mechanism

## AI Integration Notes

### Context Signals That Should Trigger This SOP
- User is writing specs or PRDs
- User is struggling with team alignment
- User mentions engineers/designers asking too many questions
- User is dealing with feature requests
- User is trying to scale their influence
- User mentions "micromanagement" concerns
- User is defining PM responsibilities

### How to Adapt for Different Situations
- **For junior PMs**: Focus on Steps 1-3, practice articulating basic "whys"
- **For senior PMs**: Emphasize Steps 4-6, including controversial decisions
- **For small teams (<10)**: Can be more informal, but still explicit about "why"
- **For large teams (50+)**: Must be rigorous about written "why" documentation
- **For technical products**: Include technical "why" (architecture reasons) alongside user "why"
- **For B2B products**: Layer in business stakeholder "why" alongside end-user "why"

### Limitations and Edge Cases
- Sometimes the "why" is legitimately unclear (early exploration)—be honest about this
- Some decisions are truly arbitrary (e.g., color hex codes)—don't force fake "whys"
- Highly regulated industries may require detailed "how" specs regardless of "why"
- Crisis situations may require directive decision-making without time for "why" communication
- Some team members may need more "how" guidance regardless of "why" clarity
