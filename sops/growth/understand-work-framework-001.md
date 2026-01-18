# Understand Work Framework

## Metadata
- **Source**: Bangaly Kaba - Lenny's Podcast
- **Domain**: Growth / Product Management
- **Type**: Framework SOP
- **Applicable To**: Product Managers, Growth Teams, Product Leaders
- **Company Stage**: All stages
- **Difficulty**: Intermediate

## Overview
Most teams follow an anti-pattern: identify something to build, justify it with data, then execute — and wonder why results are flat. The Understand Work Framework flips this: **understand first, identify second, execute third**. The key insight: **intentionally allocating time to understand work increases execution velocity and win rates over time**.

## When to Use
- Starting a new growth initiative
- Joining a new team or product
- Missing expected results repeatedly
- Planning quarterly roadmaps
- High experiment failure rates
- Building a new growth function

## Prerequisites
- Willingness to slow down initially
- Access to data and research resources
- Cross-functional collaboration
- Leadership buy-in for learning time

## Core Concept: Identify-Justify-Execute vs. Understand-Identify-Execute

### The Anti-Pattern (Identify-Justify-Execute)
**What happens:**
1. Someone says "We should build X"
2. Team pulls data to justify why X is a good idea
3. Weeks/months spent building X
4. X launches → metrics are flat
5. Team demoralized, no learning captured

**Why it fails:**
- Building for assumed needs, not validated ones
- Data used to confirm bias, not discover truth
- No understanding of why something should work
- Can't repeat success or learn from failure

### The Right Pattern (Understand-Identify-Execute)
**What happens:**
1. Team does understand work first
2. Insights reveal what actually matters
3. Identify specific opportunities based on understanding
4. Execute with higher conviction
5. Results compound over time

**Why it works:**
- De-risks projects before heavy investment
- Builds genuine understanding of levers
- Enables better prioritization
- Creates compounding knowledge

## Procedure

### Step 1: Plan Understand Work Explicitly
Make understanding an intentional part of your roadmap.

**Key principle:**
> "It is an intentional affordance in your execution to do the work that helps you to de-risk a project and to learn what's going on."

**What this means:**
- Put understand work on the roadmap as explicit items
- Assign owners to understanding tasks
- Allocate real time (not "background" work)
- Treat it as seriously as feature work

**Planning template:**
| Theme | What We Know | What We Need to Understand | Understand Work Items | Owner |
|-------|--------------|---------------------------|----------------------|-------|
| Retention | Users churning at 6 months | Why? What predicts it? | Cohort analysis, user interviews | [PM] |
| Activation | First-week drop-off high | What defines success? | Funnel instrumentation | [Eng] |

### Step 2: Calibrate the Ratio
Balance understand work vs. execution based on your knowledge state.

**Starting ratios:**
| Team State | Understand Work | Execution |
|------------|-----------------|-----------|
| New to problem space | 40-60% | 40-60% |
| Some understanding | 20-30% | 70-80% |
| Deep understanding | 10-20% | 80-90% |

**Example (YouTube):**
> "When I started at YouTube we were doing 60% execution, 40% understand work. Now my teams are probably doing 80-85% execution, 15-20% understand work."

**Key insight:**
The ratio shifts as you learn more. Early investment in understanding enables faster execution later.

### Step 3: Types of Understand Work by Function
Every function can and should do understand work.

**Engineering understand work:**
- Instrument logging and tracking
- Code architecture review
- Technical debt assessment
- Performance profiling
- Scalability analysis

**Data Science understand work:**
- Funnel analysis
- Cohort studies
- Correlation analysis
- Proxy metric validation
- Experiment power analysis

**Product Management understand work:**
- User research synthesis
- Competitive analysis
- Partnership strategy
- Feature audit
- Jobs-to-be-done mapping

**Design understand work:**
- UX audit
- User journey mapping
- Usability testing
- Design pattern research

### Step 4: Execute Parallel Paths
Run understand work alongside execution work.

**Sprint structure:**
```
Each Sprint Contains:
├── Execution Work (things we're confident about)
│   ├── Low effort, high impact items
│   ├── Medium effort, high impact items
│   └── Experiments with clear hypotheses
│
└── Understand Work (things we need to learn)
    ├── Data analysis
    ├── User research
    ├── Instrumentation
    └── Strategic exploration
```

**End of sprint output:**
1. Execution results: "This worked/didn't work, here's why"
2. Understanding results: "We learned X, which informs Y"
3. Next sprint inputs from both streams

### Step 5: Use Understand Work to Force Better Decisions
Empower teams to push back on unjustified ideas.

**When someone says "We should build X":**
- Don't immediately add to backlog
- Ask: "What do we understand about this?"
- Identify gaps in understanding
- Propose understand work first if gaps exist

**Team empowerment:**
> "Because the team adopts this mentality, it becomes this forcing function for execution. When someone says, 'You know what we should build?' You have a team that's enabled and empowered to say, 'That's a good idea, but we don't actually understand these three things.'"

### Step 6: Build Compounding Knowledge
Let understanding compound over time.

**Compounding cycle:**
```
Sprint 1: 40% understand, 60% execute → Learn A, B, C
Sprint 2: 30% understand, 70% execute → Validate A, learn D, E
Sprint 3: 25% understand, 75% execute → Apply A+D, refine approach
Sprint 4: 20% understand, 80% execute → High velocity, high win rate
```

**Results over time:**
- Higher experiment win rates (60-70% vs. typical 20-30%)
- Faster execution velocity
- Better prioritization
- More confident decision-making

## Application Example: Instagram Onboarding

**The problem:**
Instagram's sign-up flow had no logging — only knew start and end counts, not the 8 steps in between.

**Understand work done:**
1. **Engineering**: Instrument the full funnel (logging each step)
2. **PM/Design**: Manually test flows, identify obvious friction
3. **Data Science**: Build funnel dashboard once data available

**Execution in parallel:**
- While waiting for instrumentation, ran tests on obviously broken things
- Mid-quarter: Reviewed full funnel data
- Added more targeted tests based on understanding

**Result:**
- Clear visibility into where users dropped
- Targeted fixes based on data, not guesses
- 60-70% experiment win rate across teams

## Expected Outcomes
- Higher experiment success rates
- Faster long-term velocity
- More confident prioritization
- Better stakeholder alignment
- Compounding knowledge base

## Common Pitfalls

### Treating understand work as optional
- "We'll figure it out as we go"
- Understanding happens "in background"
- Never explicitly planned
- Results in guess-and-check execution

### All understand, no execute
- Analysis paralysis
- "We're still learning"
- No shipping velocity
- Must maintain execution balance

### Not documenting learnings
- Understand work completed, insights lost
- Same questions researched repeatedly
- No institutional knowledge
- Create a learning repository

### One-time understanding
- "We did research last year"
- Context changes, understanding doesn't
- Adjacent users have different needs
- Understanding is ongoing, not one-time

### Same ratio forever
- 40% understand when you have deep knowledge
- 10% understand when you're new
- Ratio should shift with knowledge state
- Reassess quarterly

## Related SOPs
- Adjacent User Theory
- Growth Experimentation Framework
- Data-Informed Decision Making

## AI Integration Notes

### Context signals that should trigger this SOP:
- "Why aren't our experiments working?"
- "We keep shipping but metrics are flat"
- "Team moving fast but no impact"
- New team/product onboarding

### How to apply:
- Assess current understand/execute ratio
- Identify key knowledge gaps
- Plan explicit understand work items
- Track learnings systematically

### Key insight:
The counterintuitive truth: slowing down to understand speeds up everything else. Teams that invest 20-40% of time in understand work achieve higher win rates and faster velocity than teams that execute 100% of the time. Understanding is the multiplier on execution.
