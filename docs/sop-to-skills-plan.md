# Plan: Converting 52 SOPs to Claude Skills

Generated: 2026-01-18

## Executive Summary

This plan outlines how to transform 52 extracted SOPs into actionable Claude Code skills. The approach uses **domain-based skill bundles** that load relevant SOPs based on context, rather than 52 individual skills that would be overwhelming to navigate.

---

## 1. Skill Architecture Strategy

### Option A: Individual Skills (NOT Recommended)
- 52 separate skills, one per SOP
- **Problems**: Menu clutter, overlapping triggers, hard to discover

### Option B: Domain Bundle Skills (RECOMMENDED)
- 8-10 bundled skills organized by use case
- Each skill loads relevant SOPs based on context
- **Benefits**: Cleaner organization, easier discovery, contextual relevance

### Proposed Skill Structure

| Skill Name | SOPs Included | Primary Triggers |
|------------|---------------|------------------|
| `/pm-coach` | PM Competencies, Three Levels, Product Sense, High Agency | "PM development", "career growth", "skills" |
| `/strategy-advisor` | Product Strategy Stack, DHM, Seven Powers, Execution vs Strategy | "strategy", "prioritization", "direction" |
| `/decision-maker` | SPADE, Nominal Group, Kill Criteria, Pre-Mortem | "decision", "choose", "should we" |
| `/growth-advisor` | Adjacent User, Understand Work, Kindle Fire, Platform Cycles | "growth", "acquisition", "retention" |
| `/leadership-coach` | Radical Candor, Selective Micromanagement, Managing Change, Coaching Tree | "management", "team", "feedback" |
| `/goal-setter` | NCT Framework, GEM, LNO, Opportunity Cost | "goals", "OKRs", "planning" |
| `/hiring-guide` | First PM Hiring, Hiring Leaders, PM Competencies (interview) | "hiring", "interview", "recruit" |
| `/gtm-advisor` | Champion Persona, Positioning, JTBD, Willingness to Pay | "launch", "positioning", "pricing" |

---

## 2. File Structure

```
.claude/skills/
├── pm-coach/
│   └── SKILL.md
├── strategy-advisor/
│   └── SKILL.md
├── decision-maker/
│   └── SKILL.md
├── growth-advisor/
│   └── SKILL.md
├── leadership-coach/
│   └── SKILL.md
├── goal-setter/
│   └── SKILL.md
├── hiring-guide/
│   └── SKILL.md
├── gtm-advisor/
│   └── SKILL.md
└── sop-library/
    └── SKILL.md          # Master index for browsing all SOPs
```

---

## 3. Skill Template

Each skill will follow this structure:

```yaml
---
name: skill-name
description: |
  [What it does] Use when [specific triggers].
  Includes frameworks: [list key frameworks].
  Sources: [expert names].
---

# Skill Name

## When This Skill Activates
- [Trigger phrase 1]
- [Trigger phrase 2]
- [Trigger phrase 3]

## Available Frameworks

### Framework 1: [Name]
**Source**: [Expert] - Lenny's Podcast
**Key Insight**: [One-liner]
**When to Use**: [Triggers]
**Procedure**:
1. Step 1
2. Step 2
3. Step 3

### Framework 2: [Name]
...

## How to Apply
1. Identify the user's situation
2. Select the most relevant framework(s)
3. Walk through the procedure step-by-step
4. Highlight common pitfalls to avoid

## Cross-References
- Related skill: /other-skill
- Full SOP: [link to sops/ directory]
```

---

## 4. Conversion Methodology

### Step 1: Extract Core Content from Each SOP
For each SOP, extract:
- **Key Insight** (1 sentence)
- **Trigger Phrases** (from "When to Use" + "AI Integration Notes")
- **Condensed Procedure** (5-7 steps max)
- **Top 3 Pitfalls**

### Step 2: Group into Domain Bundles
Map each SOP to its primary skill bundle:

| Domain | SOPs to Include |
|--------|-----------------|
| pm-coach | product-sense-development, three-levels-product-work, high-agency-development, pm-competencies-framework, design-feedback-framework, product-review-best-practices, perceived-simplicity-design |
| strategy-advisor | product-strategy-stack, dhm-product-strategy-framework, execution-vs-strategy-diagnosis, execution-over-strategy, seven-powers-assessment |
| decision-maker | spade-decision-framework, nominal-group-decision-making, kill-criteria-framework, pre-mortem-technique, opportunity-cost-mindset |
| growth-advisor | adjacent-user-theory, understand-work-framework, kindle-fire-growth-strategy, distribution-platform-cycle, data-network-effects, instagram-growth-case-study, free-to-paid-conversion, product-led-sales, growth-tactics-anti-patterns, hypergrowth-innovation |
| leadership-coach | radical-candor-framework, selective-micromanagement, managing-complex-change, blooms-taxonomy-coaching, coaching-tree-leadership, career-impact-framework, founder-mode-operating-system, company-operating-system, personal-operating-principles |
| goal-setter | nct-goal-setting, gem-prioritization-framework, lno-framework-time-management |
| hiring-guide | first-pm-hiring, hiring-leaders-playbook |
| gtm-advisor | champion-persona-framework, five-component-positioning, jobs-to-be-done-interview, four-forces-demand-analysis, willingness-to-pay-research, ab-testing-implementation |

### Step 3: Write SKILL.md for Each Bundle
- Combine trigger phrases from all included SOPs
- Create condensed procedure summaries
- Include cross-references to full SOPs
- Add contextual selection logic

### Step 4: Test and Iterate
- Test with realistic user prompts
- Verify correct skill activation
- Check framework selection accuracy
- Refine descriptions for better matching

---

## 5. Example Skill: `/decision-maker`

```yaml
---
name: decision-maker
description: |
  Helps make high-quality decisions using proven frameworks. Use when:
  deciding between options, facing difficult choices, setting up decision
  processes, running pre-mortems, or determining when to quit/continue.
  Includes: SPADE, Nominal Group, Kill Criteria, Pre-Mortem, Opportunity Cost.
  Sources: Gokul Rajaram, Annie Duke, Shreyas Doshi.
---

# Decision-Maker Skill

## When This Skill Activates
- "Help me decide..."
- "Should we do A or B?"
- "How do we make this decision?"
- "We need alignment on..."
- "Should we continue this project?"
- "When should we quit?"
- "Run a pre-mortem"

## Available Frameworks

### 1. SPADE Framework (Big Decisions)
**Source**: Gokul Rajaram
**Key Insight**: Most decision delays come from unclear ownership and insufficient alternatives.
**Use When**: Major decisions, cross-functional choices, high-stakes irreversible decisions

**Quick Procedure**:
1. **Setting**: Define what, why, when, constraints
2. **People**: Assign one decision-maker, list approvers/consulted/informed
3. **Alternatives**: Generate 3+ options including "do nothing"
4. **Decide**: Decision-maker makes call, gets approvals
5. **Explain**: Communicate decision and rationale to all

### 2. Nominal Group Method (Group Decisions)
**Source**: Annie Duke
**Key Insight**: Discover independently, discuss together, decide independently.
**Use When**: Brainstorming, forecasting, any group input needed

**Quick Procedure**:
1. Collect opinions independently before meeting (no cross-influence)
2. Aggregate and share responses
3. Meet to discuss differences (not to discover or decide)
4. Vote/decide independently after discussion
5. Accept disagreement; don't force "alignment"

### 3. Kill Criteria Framework (When to Quit)
**Source**: Annie Duke
**Key Insight**: Pre-mortems only work if paired with pre-committed actions.
**Use When**: Starting projects, evaluating whether to continue

**Quick Procedure**:
1. Run pre-mortem: "If this fails, what were the early signals?"
2. For each signal, define specific action (kill, pivot, investigate)
3. Commit to actions before launching
4. Monitor for signals
5. Execute pre-committed actions without debate when signals appear

### 4. Pre-Mortem Technique (Risk Assessment)
**Source**: Shreyas Doshi
**Key Insight**: Imagining failure before it happens reveals hidden risks.
**Use When**: Before launching projects, major initiatives

**Quick Procedure**:
1. "Imagine it's 6 months from now and this failed completely"
2. Each person writes what went wrong (independently)
3. Aggregate and categorize risks
4. Create mitigation plans for top risks
5. Set up kill criteria for key signals

### 5. Opportunity Cost Mindset (Prioritization)
**Source**: Shreyas Doshi
**Key Insight**: The cost of doing something is everything else you can't do.
**Use When**: Prioritization debates, resource allocation

**Quick Procedure**:
1. Don't just ask "Is this worth doing?"
2. Ask "What are we NOT doing if we do this?"
3. Compare against the best alternative use of resources
4. Factor in learning and optionality value
5. Make explicit tradeoffs

## How to Apply

1. **Identify the decision type**:
   - Big strategic decision → SPADE
   - Group input needed → Nominal Group
   - Continue/quit decision → Kill Criteria
   - Risk assessment → Pre-Mortem
   - Prioritization → Opportunity Cost

2. **Walk through the selected framework** step-by-step

3. **Highlight pitfalls**:
   - Don't seek "alignment" (it doesn't exist)
   - Don't skip the alternatives step
   - Don't decide in meetings (do it independently)
   - Don't ignore pre-committed kill criteria

## Full SOPs (for deep dives)
- [SPADE Framework](/sops/decision-making/spade-decision-framework-001.md)
- [Nominal Group](/sops/decision-making/nominal-group-decision-making-001.md)
- [Kill Criteria](/sops/decision-making/kill-criteria-framework-001.md)
- [Pre-Mortem](/sops/product-management/prioritization/pre-mortem-technique-001.md)
- [Opportunity Cost](/sops/product-management/prioritization/opportunity-cost-mindset-001.md)
```

---

## 6. Implementation Timeline

| Phase | Task | Output |
|-------|------|--------|
| **Phase 1** | Create skill directory structure | `.claude/skills/` with 8 folders |
| **Phase 2** | Build `/decision-maker` skill (example) | 1 working skill |
| **Phase 3** | Build `/pm-coach` skill | 2 working skills |
| **Phase 4** | Build `/strategy-advisor` skill | 3 working skills |
| **Phase 5** | Build `/growth-advisor` skill | 4 working skills |
| **Phase 6** | Build `/leadership-coach` skill | 5 working skills |
| **Phase 7** | Build remaining skills | All 8 skills complete |
| **Phase 8** | Create `/sop-library` master index | Complete system |
| **Phase 9** | Test and iterate | Refined skills |

---

## 7. Success Criteria

- [ ] All 8 domain skills created and functional
- [ ] Each skill correctly activates on relevant triggers
- [ ] Condensed procedures are actionable (not just references)
- [ ] Cross-references to full SOPs work
- [ ] Skills don't conflict with each other
- [ ] User can browse all SOPs via `/sop-library`

---

## 8. Additional Considerations

### Skill Description Optimization
Descriptions must be specific enough for Claude to match correctly:
- Bad: "Helps with product decisions"
- Good: "Helps make high-quality decisions using proven frameworks. Use when: deciding between options, facing difficult choices, setting up decision processes, running pre-mortems, or determining when to quit/continue."

### Progressive Disclosure
- Keep SKILL.md under 500 lines
- Include condensed procedures in skill
- Link to full SOPs for detailed walkthroughs
- Only load additional content when user asks for deep dive

### Avoiding Overlap
- Each SOP maps to one primary skill
- Cross-reference related skills when relevant
- Use specific triggers to differentiate

---

## 9. Next Steps

1. **Approve this plan** - Confirm the 8-skill bundle approach
2. **Create directory structure** - Set up `.claude/skills/` folders
3. **Build first skill** - `/decision-maker` as proof of concept
4. **Iterate based on testing** - Refine approach
5. **Complete remaining skills** - Build all 8 bundles
6. **Document** - Update todos.md with progress

---

*Plan created: 2026-01-18*
