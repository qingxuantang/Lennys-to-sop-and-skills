# AI-Era Product Development Framework

## Metadata
- **Source**: Mike Krieger (Instagram Co-founder, CPO Anthropic) - Lenny's Podcast
- **Domain**: Product Management & Strategy
- **Type**: Framework
- **Applicable To**: Product Managers, Engineering Leaders, CTOs building with AI (All company stages)
- **Difficulty**: Advanced

## Overview
A framework for adapting product development processes when AI writes 70-95% of your code, shifting bottlenecks from engineering throughput to strategic alignment, decision-making, and deployment infrastructure. Based on Anthropic's experience as "patient zero" for AI-native development.

## When to Use
- Your team is using AI code generation tools (Claude Code, GitHub Copilot, Cursor) extensively
- Engineering velocity has increased dramatically but new bottlenecks are emerging
- Traditional product development processes feel misaligned with AI capabilities
- You're experiencing merge queue overload or deployment bottlenecks
- PMs/designers want to prototype directly without engineering handoffs

## Prerequisites
- Team has adopted AI coding tools with >50% code generation
- Engineering team comfortable with AI-assisted development
- Existing CI/CD and code review processes in place
- Understanding of traditional product development lifecycle

## Procedure

### Step 1: Identify the New Bottlenecks
When engineering speed increases 5-10x, bottlenecks shift from "building" to:

**Upstream Bottlenecks:**
- **Strategic alignment**: Teams lack clarity on what to build
- **Decision-making**: Too many options, unclear prioritization
- **Context sharing**: Information doesn't flow to decision-makers

**Downstream Bottlenecks:**
- **Merge queue capacity**: Infrastructure can't handle 2-5x more PRs
- **Code review volume**: Too much code for line-by-line review
- **Deployment coordination**: "Air traffic control" for landing changes
- **Testing coverage**: Ensuring AI-generated code works correctly

**Action**: Run retrospective asking "What stopped us from shipping faster this sprint?"
- If answer is "waiting for eng to build" → traditional bottleneck
- If answer is "unclear what to build" or "merge queue backed up" → AI-era bottleneck

### Step 2: Evolve Your Product Process

**New PM Capabilities Enabled:**
- PMs can create functional prototypes using Claude/Artifacts without engineering
- Designers can build interactive demos, not just static mockups
- Non-engineers can contribute code via natural language prompting

**Action Items:**
- Encourage PMs to prototype ideas in Artifacts/Claude Code before writing specs
- Replace static mockups with functional demos for product reviews
- Reduce time from idea → tangible prototype from days/weeks to hours

**Example**: "My favorite things that happen now are nice PMs that have an idea they want to express will use Claude and Artifacts to put together an actual functional demo. That makes it tangible."

### Step 3: Strengthen Upstream Strategy
With engineering no longer the constraint, strategy becomes THE bottleneck.

**Minimum Viable Strategy Components:**
- **Clear problem space**: What user problem are we solving?
- **Decision authority**: Who can make calls without escalation?
- **Success criteria**: How do we know if this worked?
- **Scope boundaries**: What's explicitly OUT of scope?

**Action**: Create "minimum viable strategy" doc (1-2 pages max) covering:
```markdown
## Problem
[User pain point in one sentence]

## Proposed Direction
[High-level approach, not detailed specs]

## Success Looks Like
[2-3 measurable outcomes]

## Explicit Non-Goals
[What we're NOT solving for now]

## Decision Rights
[Who can make what calls]
```

Mike's advice: "How do I provide the minimum viable strategy to let people feel empowered to go run and type and build and explore at the edge of model capabilities?"

### Step 4: Re-architect Code Review
Traditional line-by-line review doesn't scale when AI generates large, mostly-correct PRs.

**Claude Code Team Approach:**
- Use AI to review AI-generated code
- Humans do "acceptance testing" rather than line review
- Focus on: Does it work? Does it solve the problem? Is the approach sound?
- Less focus on: Syntax, style, minor optimizations (AI usually gets these right)

**Action**:
- For AI-generated PRs >200 lines: Use Claude to review, human validates the review
- Create acceptance test criteria before code is written
- Shift review time from syntax → architecture and user impact

**Warning**: "I could also imagine it going off the rails and having a completely unmaintainable or even understandable by Claude codebase. That hasn't happened, but watching them change their review processes has been interesting."

### Step 5: Scale Deployment Infrastructure
Your merge queue and deployment systems weren't built for this volume.

**Anthropic's Experience:**
- "Over half of our pull requests are Claude Code generated. Probably at this point over 70%"
- "We had to completely re-architect [our merge queue] because so much more code was being written"

**Actions**:
- Audit merge queue capacity: What's the max PRs/day it can handle?
- Implement smarter queuing: Fast-track low-risk changes, batch similar changes
- Invest in CI/CD speed: Faster tests = faster queue throughput
- Consider deployment windows: Not everything needs immediate production deploy

### Step 6: Embed Product with Research (For AI Companies)
If building AI products, the biggest leverage is PMs working WITH model researchers, not just using finished models.

**Mike's Insight**:
"If we're shipping things that could have been built by anybody just using our models off the shelf... where we should play and what we can do uniquely should be stuff at that magic intersection between [product and research]."

**Actions for AI Product Teams:**
- Embed PMs in post-training conversations
- PMs should influence model capabilities for their use cases
- Create feedback loops: Product insights → Research priorities → Better models → Better products

**Success indicator**: "The PMs that have the most internal positive feedback from both research and engineering are the ones that get it."

### Step 7: Rethink Prototyping → Shipping Flow
The gap between prototype and production shrinks dramatically.

**New Reality:**
- Prototype in Claude Code → Often production-ready or close
- Non-engineer sees bug → Can fix it themselves with AI in 1 hour
- Example: "I saw a great comment yesterday where somebody had this thing driving them crazy about Claude Code and they're like, 'I don't know any TypeScript, I'm just going to talk to Claude about it.' They went from that to pull request in an hour."

**Action**:
- Reduce "prototype cleanup" phase expectations
- Enable non-engineering contributors with Claude Code access
- Create "self-serve fix" documentation for common issues

### Step 8: Evolve Metrics and Success Criteria
Traditional engagement metrics may not capture AI product value.

**Question Claude Asked Mike**: "How do you think about product metrics when a good conversation with me could be 2 messages or 200?"

**Mike's Philosophy**:
- Avoid over-optimizing "engagement" (can lead to sycophancy, prolonged conversations)
- Focus on: "Did it actually help you get work done?"
- Example: "Claude helped me put together a prototype that saved me literally probably six hours and it did it in about 20-25 minutes."

**Actions**:
- Track "hours saved" via surveys (even if imperfect)
- Measure retention over raw engagement
- Qualitative feedback: "Does this feel like it's working for you?"
- Mike's north star: "Do we repeatedly hear from people that Claude is the way they're unlocking their own creativity and getting things done?"

## Expected Outcomes
- Engineering remains highly productive but no longer the primary bottleneck
- Faster iteration from idea → working prototype → production
- Higher code volume without proportional headcount increase
- New bottlenecks surface (strategy, deployment, coordination) that you can explicitly address
- Cross-functional team members can contribute code directly

## Common Pitfalls

### Pitfall 1: Over-hiring Engineers
**Mistake**: "We need more headcount to build faster"
**Reality**: "More than that we need a couple of almost founder-type engineers with ideas paired with the right design and product support."

**Solution**: Prioritize 1-2 senior "founding engineers" over 5-10 junior engineers. Quality of engineering vision matters more than quantity when AI handles implementation.

### Pitfall 2: Maintaining Old Process Assumptions
**Mistake**: Keeping traditional sprint planning, estimation, story pointing
**Reality**: When AI codes, estimates are often wrong by 5-10x (in the fast direction)

**Solution**: Experiment with shorter cycles, outcome-based planning, and flexibility for "AI unlocked" faster delivery.

### Pitfall 3: Ignoring Strategy in Favor of Shipping
**Mistake**: "Engineering is so fast now, let's just build everything!"
**Reality**: "I think we'd miss out on an opportunity in the meantime [without clear strategy]."

**Solution**: Invest MORE in strategy as engineering gets faster. Speed without direction is chaos.

### Pitfall 4: Assuming AI-Generated Code is Always Correct
**Mistake**: Rubber-stamping AI PRs without validation
**Reality**: Models generally get it right but can introduce subtle bugs or architectural issues

**Solution**: Shift review focus to testing and validation rather than eliminating review entirely.

## Related SOPs
- perceived-simplicity-design-001.md
- product-strategy-stack-001.md
- pm-competencies-framework-001.md

## AI Integration Notes

### Context Signals for This SOP
- User mentions AI coding tools, Claude Code, Cursor, GitHub Copilot
- Questions about "how to manage when AI writes most code"
- Complaints about "engineering is fast but we're still slow"
- Merge queue or CI/CD bottlenecks mentioned
- Questions about product development process evolution

### Adaptation Guidance
- For earlier-stage teams (<50% AI code): Focus on Steps 1-3, skip infrastructure scaling
- For non-AI products: Skip Step 6 (research embedding), focus on other steps
- For enterprise: Emphasize deployment coordination and review processes more
- For startups: Emphasize founder-engineer model and minimal strategy docs

### Key Quotes to Reference
- "The team that works in the most futuristic way is the Claude Code team—they're using Claude Code to build Claude Code in a very self-improving way."
- "I'm 10x more a believer in the founding engineer tech lead with an idea paired with the right design and product support than before."
- "How do we figure out what we want to be when we grow up versus what we currently aren't?"

### Limitations
- Based on Anthropic's specific context (AI company with cutting-edge AI access)
- May not apply to heavily regulated industries with strict code review requirements
- Assumes team has strong technical foundation already
- Most applicable to software/SaaS, less to hardware or physical products
