# Engineering Strategy Development Framework

## Metadata
- **Source**: Will Larson - Lenny's Podcast
- **Domain**: Engineering Leadership & Strategy
- **Type**: Framework
- **Applicable To**: CTOs, VPs of Engineering, Engineering Directors, Staff+ Engineers
- **Difficulty**: Advanced
- **Company Stage**: All stages (techniques adapt by stage)

## Overview
A practical framework for developing and documenting engineering strategy based on Richard Rumelt's definition (diagnosis, guiding policies, actions). This approach focuses on creating boring but powerful constraints that align engineering efforts with business priorities, while avoiding the trap of "inert strategy" that never gets implemented.

## When to Use
- When engineers or leaders complain there's "no engineering strategy"
- When making decisions about technology choices, infrastructure investments, or technical debt
- During quarterly or annual planning cycles
- When engineering teams are pulling in inconsistent directions
- When onboarding new engineering leaders who need context
- When you need to explain engineering trade-offs to non-technical executives

## Prerequisites
- Understanding of your company's business strategy and constraints
- Awareness of current engineering challenges and bottlenecks
- Willingness to make and enforce unpopular constraints
- Ability to write down strategy (even imperfectly) to enable iteration

## Procedure

### Step 1: Recognize You Already Have a Strategy
Understand the foundational insight:
- Product, engineering, and business always have a strategy—it's just often not written down
- Unwritten strategy gets applied inconsistently across teams
- Written strategy enables debugging: Is the strategy bad? Is it being misapplied? Is it not appropriate for specific contexts?
- **The first rule of strategy**: If you write it down, you can improve it

Action: Before creating new strategy, articulate what you're already doing implicitly.

### Step 2: Apply Rumelt's Three-Part Framework
Structure your strategy using these components:

**Diagnosis**: What is the current reality?
- What constraints do we face? (Technical debt, skill gaps, infrastructure limits, time pressures)
- What problems are we trying to solve?
- What's working? What's not working?
- Be brutally honest about actual constraints, not aspirational ones

**Guiding Policies**: Based on diagnosis, how will we address them?
- These are your strategic constraints and principles
- They dictate how you'll invest limited capabilities
- They should be boring and clear, not inspiring
- Examples: "We only use our standard toolkit" or "We run everything in our own data centers"

**Actions**: How will we implement these policies?
- Specific initiatives and projects
- Resource allocation decisions
- What gets prioritized and what gets deprioritized
- Avoid "inert strategy"—ensure actions actually happen

### Step 3: Create Boring, Powerful Constraints
Develop guiding policies that focus energy:

**Characteristics of Good Engineering Strategy**:
- **Boring**: Not exciting or innovative—they're constraints
- **Clear**: No ambiguity about what they mean
- **Applicable**: Can be used to make real decisions
- **Honest**: Reflects actual priorities, not aspirational ones
- **Reversible**: You can imagine a valid alternative (if not, it's not strategy, it's identity)

**Examples of Effective Boring Strategies**:
- "We only use the tools we have today" (standard kit approach)
- "We run everything in our own data centers" (Uber's approach)
- "We maintain a Ruby monolith" (Stripe's approach)
- "We optimize globally, not locally" (Stripe's value)
- "Engineers spend their energy on user-facing features, not internal tooling"

### Step 4: Test for Reversibility
Ensure your strategy is actually strategy, not just identity statements:

**Good (Reversible) Strategy Examples**:
- "We only use our standard toolkit" ↔ "We adopt new tools when they solve specific problems"
- "We run in our own data centers" ↔ "We use cloud providers for flexibility"
- "We're a team, not a family" ↔ "We're a family" (Netflix's deliberate choice)

**Bad (Identity, Not Strategy) Examples**:
- "We build good software" (Who wouldn't?)
- "We care about customers" (Not reversible—everyone claims this)
- "We solve customer problems that matter" (Too vague to be useful)

If you can't imagine a legitimate alternative approach, it's an identity value, not strategy.

### Step 5: Document Even Imperfect Strategy
Write it down despite imperfection:
- Start with something "mediocre" rather than waiting for perfect
- Use documentation to educate stakeholders about trade-offs
- Treat the document as a living artifact that improves over time
- Share broadly to enable consistent application

**Minimum Viable Strategy Document**:
```markdown
# Engineering Strategy

## Diagnosis
[Current constraints and challenges]

## Guiding Policies
1. [Constraint/Principle 1]
2. [Constraint/Principle 2]
3. [Constraint/Principle 3]

## Actions
- [Priority 1 with rationale]
- [Priority 2 with rationale]
- [What we're NOT doing and why]
```

### Step 6: Focus Energy on What Matters
Use strategy to align with business priorities:
- Boring strategies tell engineers what the company actually values
- Constraints force energy toward problems the company cares about
- Acknowledge that alignment can be painful for individuals with different interests
- Accept that some engineers will be frustrated—that's the point of having strategy

**Example**: "Standard Kit" Strategy
- Frustrates engineers who want to use new languages/tools
- But focuses collective energy on user problems instead of tooling problems
- Carta: Eric Vogel wrote "the standard kit"—clear documentation of approved tools
- Result: Faster development on features that matter to customers

### Step 7: Address Complaints About "No Strategy"
When engineers or PMs complain about missing strategy:

**Common complaint**: "There's no product strategy" or "There's no engineering strategy"
**Reality**: Strategy exists but isn't articulated or is inconsistently applied

**Response approach**:
1. Acknowledge the pain point (inconsistent application)
2. Document current implicit strategy
3. Validate whether strategy is appropriate
4. Clarify or revise as needed
5. Communicate broadly

### Step 8: Avoid Bad Strategy Pitfalls
Watch for common failure modes:

**Bad Diagnosis**: Wishful thinking about constraints
- Example: "We can do all these projects at once" (when you can't)
- Solution: Be brutally honest about time, people, and technical constraints

**Inert Strategy**: Guiding policies without actions
- Example: "We will deprecate unused features" (but no one deprecates anything)
- Solution: Define specific actions, owners, and timelines

**Identity Masquerading as Strategy**: Non-reversible statements
- Example: "We build high-quality products"
- Solution: Apply the reversibility test

## Expected Outcomes
- Clear, documented engineering strategy that enables decision-making
- Reduced debate about technology choices (strategy provides answers)
- More consistent decisions across different engineering teams
- Better ability to explain engineering trade-offs to non-technical stakeholders
- Increased engineering velocity due to reduced thrashing
- Engineers understanding what the company values (even if frustrating)

## Common Pitfalls

### Pitfall 1: Waiting for Perfect Strategy Before Writing
**Problem**: Leaders delay documenting strategy until it's perfect, resulting in nothing written.
**Solution**: Write down current implicit strategy, even if mediocre. You can only improve what's documented. Use documentation process to educate stakeholders.

### Pitfall 2: Confusing Strategy with Identity
**Problem**: Filling strategy with non-reversible statements like "We care about quality."
**Solution**: Apply reversibility test. If you can't imagine a valid alternative, it's identity, not strategy. Remove it or make it more specific.

### Pitfall 3: Creating Inert Strategy
**Problem**: Beautiful strategy document with no actual implementation or accountability.
**Solution**: Include specific actions with owners and timelines. Will Larson is "less worried" about this in engineering than other domains, but still monitor implementation.

### Pitfall 4: Trying to Please Everyone
**Problem**: Strategy that doesn't constrain anything to avoid frustrating anyone.
**Solution**: Remember that good strategy's goal is NOT to appease everyone. It's to dictate how to invest limited capabilities into problems you care about. Some frustration is expected and healthy.

### Pitfall 5: Ignoring Reality in Diagnosis
**Problem**: Exerting what you want to be true rather than accepting actual constraints.
**Solution**: "Reality is never wrong. Your model is always wrong if it's in conflict with reality." Start with honest assessment of constraints.

### Pitfall 6: Strategy That Can't Make Decisions
**Problem**: Strategy too vague to help with actual decisions engineers face.
**Solution**: Test strategy against recent debates. Does it provide clear guidance? If not, make it more specific and applicable.

## Examples from Leading Companies

### Uber: Own Data Centers Strategy
**Diagnosis**: Need to operate in varied geopolitical environments with different regulations
**Guiding Policy**: Run everything in our own data centers, no cloud dependencies
**Actions**: Build internal infrastructure team, establish data center partnerships globally
**Result**: Able to launch in China in 3 months (including crane-lifting racks onto roofs when they didn't fit through doors); able to enter/exit markets based on business decisions, not infrastructure constraints
**Trade-off**: Engineers had to build/maintain more tooling; frustrated engineers who wanted cloud

### Stripe: Ruby Monolith Strategy (circa 2016)
**Diagnosis**: Limited engineering resources; need to maximize user-facing innovation
**Guiding Policy**: Maintain Ruby monolith; avoid introducing new languages
**Actions**: Invest in Ruby infrastructure; optimize monolith; focus hiring on Ruby engineers
**Result**: Engineers spent time on innovative user features instead of supporting multiple languages
**Trade-off**: Some engineers frustrated by language constraints; evolved later as company scaled (more Java by 2023)
**Note**: Frustration was a feature, not a bug—it focused energy on what mattered

### Carta: Standard Kit
**Diagnosis**: Proliferation of tools creates maintenance burden and slows development
**Guiding Policy**: Only use approved standard toolkit
**Actions**: Eric Vogel documented "the standard kit"; new tool introductions require exception process
**Result**: Faster development; reduced maintenance; clearer onboarding
**Trade-off**: Engineers frustrated by constraints on tool choice

## Related SOPs
- Systems Thinking for Engineering Leaders
- Staff Engineer Sponsorship Framework
- Engineering Productivity Measurement
- EM/PM Partnership Framework

## AI Integration Notes

### Context Signals
Trigger this SOP when detecting:
- Questions about "how to create engineering strategy"
- Complaints about lack of engineering direction or strategy
- Debates about adopting new technologies or tools
- Requests for how to align engineering teams
- Questions about saying "no" to engineer requests
- Confusion about what engineering strategy means

### Adaptation Guidance
- **For early-stage startups**: Focus on diagnosis and 1-2 key constraints; avoid over-strategizing
- **For scale-ups**: Emphasize documentation to ensure consistency as teams grow
- **For enterprises**: May need more formal review processes; focus on communication strategy
- **For technical audiences**: Emphasize that boring strategy is powerful strategy
- **For non-technical audiences**: Use business analogies; connect to business strategy

### Key Principles to Emphasize
1. Writing down strategy enables improvement—perfect is enemy of good
2. Strategy is about constraints, not inspiration
3. Good strategy is boring and clear
4. Reality is never wrong; your model is wrong if they conflict
5. Reversibility test separates strategy from identity
6. Some engineer frustration indicates good strategy (focus effect)

### Common Misapplications
- Applying this framework to create aspirational vision (that's not strategy)
- Creating strategy without honest diagnosis
- Writing strategy but never using it to make decisions
- Refusing to document strategy because "it's not perfect yet"
- Creating strategy that doesn't constrain anything to avoid conflict

### Example Prompts for AI Application
"Help me document our implicit engineering strategy" → Guide through diagnosis of current practices, then codify
"Should we adopt [new technology]?" → Apply documented strategy constraints; if none exist, help create them
"Engineers complain we have no strategy" → First step: help articulate implicit strategy that exists
