# SPADE Decision-Making Framework

## Metadata
- **Source**: Gokul Rajaram - Lenny's Podcast
- **Domain**: Decision-Making / Operations
- **Type**: Framework SOP
- **Applicable To**: Leaders, Managers, Cross-functional Teams
- **Company Stage**: All stages (especially scaling companies)
- **Difficulty**: Intermediate

## Overview
SPADE is a framework for making high-quality decisions efficiently: **Setting**, **People**, **Alternatives**, **Decide**, **Explain**. The key insight: **most decision-making delays come from unclear ownership and insufficient exploration of alternatives**. SPADE forces clarity on both.

## When to Use
- Major product decisions
- Strategic choices with significant tradeoffs
- Cross-functional decisions requiring alignment
- Decisions where stakeholders disagree
- High-stakes, irreversible decisions
- When decision ownership is unclear

## Prerequisites
- Clear decision to be made
- Identified stakeholders
- Willingness to commit to a process
- Time for proper alternatives exploration

## Core Concept: The Five Components

### S - Setting
**Definition**: The context and constraints around the decision.

**Components:**
- **What**: The precise decision being made
- **Why**: Why this decision matters now
- **When**: Deadline for the decision
- **Constraints**: Budget, time, technical, legal limitations

**Key insight**: A well-defined setting prevents scope creep and endless discussion.

### P - People
**Definition**: Who is involved and what role they play.

**Roles:**
- **Responsible**: The decision-maker (one person only)
- **Approvers**: Must approve the decision (keep minimal)
- **Consulted**: Provide input but don't approve
- **Informed**: Told about the decision after it's made

**Key insight**: Having one clear decision-maker is critical. If it's unclear who decides, it's probably you.

### A - Alternatives
**Definition**: The realistic options being considered.

**Requirements:**
- At least 3 alternatives (avoids false binary)
- Include "do nothing" as an option
- Each alternative should be viable
- Clearly articulate tradeoffs for each

**Key insight**: The quality of the decision is limited by the quality of alternatives generated.

### D - Decide
**Definition**: Making and documenting the decision.

**Process:**
1. Gather input from Consulted parties
2. Evaluate alternatives against criteria
3. Decision-maker makes the call
4. Get approval from Approvers
5. Document the decision and rationale

**Key insight**: Once decided, commit fully. Don't relitigate.

### E - Explain
**Definition**: Communicating the decision to all stakeholders.

**Components:**
- The decision made
- Why this alternative was chosen
- What alternatives were considered
- What happens next

**Key insight**: Explaining the "why" builds trust and alignment, even when people disagree.

## Procedure

### Step 1: Define the Setting
Write a clear decision statement.

**Template:**
> We need to decide [specific decision] by [date] because [why it matters now]. Our constraints are [list constraints].

**Example:**
> We need to decide which payment processor to use by March 15 because our current contract expires in April. Our constraints are: must support 50+ countries, cost under $0.30/transaction, PCI compliance required.

**Avoid:**
- Vague framing: "We need to figure out our payments strategy"
- Missing deadlines: Decisions without dates drag on
- Hidden constraints: Surface them upfront

### Step 2: Identify the People
Assign SPADE roles explicitly.

**Responsible (R):**
- One person only
- Has authority to decide
- Owns the process end-to-end

**Approvers (A):**
- Keep to minimum (1-2 max)
- Only include if their veto is real
- Not the same as "important stakeholders"

**Consulted (C):**
- People with valuable input
- Subject matter experts
- Impacted team leads

**Informed (I):**
- Affected parties
- Broader organization
- Told after decision is made

**Document clearly:**
| Role | Person | Why |
|------|--------|-----|
| R | Sarah | Owns payments team |
| A | CEO | Budget > $1M threshold |
| C | Engineering Lead | Technical integration |
| C | Finance | Cost analysis |
| I | Customer Support | Will handle support tickets |

### Step 3: Generate Alternatives
Brainstorm at least 3 viable options.

**Process:**
1. Individual brainstorming first (avoid groupthink)
2. Combine and refine
3. Ensure each alternative is truly viable
4. Include "do nothing" or "status quo"

**For each alternative, document:**
- Description
- Pros
- Cons
- Key risks
- Estimated cost/effort

**Example:**
| Alternative | Pros | Cons | Risk |
|-------------|------|------|------|
| Switch to Stripe | Best developer experience | Higher fees | Migration complexity |
| Negotiate with current | No migration | Limited features | Relationship strain |
| Build in-house | Full control | 6+ month timeline | Opportunity cost |

### Step 4: Make the Decision
Gather input and decide.

**Input gathering:**
- Share alternatives document with Consulted parties
- Set deadline for input (e.g., 48 hours)
- Synthesize feedback

**Decision meeting (if needed):**
- Present alternatives and input received
- Discuss key tradeoffs
- Decision-maker makes the call

**Getting approval:**
- Share decision with Approvers
- Address any blocking concerns
- Get explicit sign-off

**Key insight**: The decision-maker decides, not consensus. Consultation is input, not voting.

### Step 5: Explain the Decision
Communicate broadly.

**Template:**
> We decided to [decision]. We chose this because [rationale]. We also considered [alternatives] but didn't choose them because [reasons]. Next steps are [actions].

**Communication plan:**
- Who needs to know?
- What format? (Email, meeting, doc)
- When? (Immediately, after X happens)
- Q&A? (Office hours for questions)

**Example:**
> We decided to switch to Stripe for payment processing. We chose this because their developer experience will save us 3 months of engineering time annually, and their international coverage matches our expansion plans. We considered staying with our current provider (too limited) and building in-house (too slow). Migration begins April 1.

## Expected Outcomes
- Faster decisions with clear ownership
- Better decisions through alternatives exploration
- Higher buy-in through transparent process
- Less relitigating of past decisions
- Clearer accountability

## Common Pitfalls

### Too many Approvers
- Approval becomes bottleneck
- Only include true veto holders
- Everyone else is Consulted

### Binary framing
- "Should we do X or not?" is too narrow
- Force at least 3 alternatives
- Include creative options

### Decision by committee
- One person must be Responsible
- Consultation ≠ consensus
- Commit to the decision once made

### Skipping the Explain step
- Creates confusion and distrust
- People feel blindsided
- Take time to communicate clearly

### Relitigating decisions
- Once decided, commit
- New information may warrant revisit
- But not just because someone disagrees

## When Not to Use SPADE

**Overkill for:**
- Easily reversible decisions
- Low-stakes choices
- Individual contributor decisions
- Decisions within one person's clear authority

**Use SPADE for:**
- Cross-functional decisions
- High stakes or irreversible
- Significant resource commitment
- Disagreement among stakeholders

## Related SOPs
- RACI Framework
- Decision Documentation Template
- Cross-Functional Collaboration

## AI Integration Notes

### Context signals that should trigger this SOP:
- User mentions "decision-making process"
- Unclear decision ownership
- Cross-functional disagreement
- High-stakes decisions

### How to apply:
- Start with Setting clarification
- Emphasize single decision-maker (Responsible)
- Push for 3+ alternatives
- Ensure Explain step happens

### Key insight:
Most decision delays come from unclear ownership and insufficient alternatives. SPADE fixes both by forcing a single decision-maker and requiring multiple options to consider.
