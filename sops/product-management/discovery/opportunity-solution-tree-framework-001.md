# Opportunity Solution Tree Framework

## Metadata
- **Source**: Teresa Torres - Lenny's Podcast
- **Domain**: Product Management / Discovery
- **Type**: Framework SOP
- **Applicable To**: Product Managers, Product Designers, Product Trios
- **Company Stage**: All stages
- **Difficulty**: Intermediate (looks simple, hard in practice)

## Overview
The Opportunity Solution Tree (OST) is a visual framework that helps product teams navigate from an assigned outcome to discovering the right solutions to build. It structures the messy problem of "how do I start from an outcome and figure out what to build?" into a tree that branches from outcome → opportunities → solutions → assumption tests.

## When to Use
- You're assigned an outcome (not a feature) and need to decide what to build
- Prioritizing which problems to solve across your product
- Aligning team around customer needs
- Creating strategic focus for discovery work
- Moving from output-focused to outcome-focused product development

## Prerequisites
- An outcome you're responsible for improving
- Access to customers for interviews
- Willingness to think deeply (this is hard work)
- Understanding of customer interview techniques

## Core Concept: The Tree Structure

```
                     [OUTCOME]
                         │
        ┌────────────────┼────────────────┐
        │                │                │
   [Opportunity 1]  [Opportunity 2]  [Opportunity 3]
        │                │                │
   ┌────┴────┐      ┌────┴────┐      ┌────┴────┐
   │    │    │      │    │    │      │    │    │
  Sub  Sub  Sub    Sub  Sub  Sub    Sub  Sub  Sub
   │    │    │      │    │    │      │    │    │
Solutions        Solutions        Solutions
```

**Components:**
1. **Outcome** (root): The business/product metric you're trying to improve
2. **Opportunities** (branches): Customer needs, pain points, desires
3. **Solutions** (leaves): Ideas to address opportunities
4. **Assumption Tests**: Ways to validate solutions before building

## Procedure

### Step 1: Start with a Clear Outcome

**The outcome is NOT a feature.** It's a measurable result you're trying to achieve.

**Examples:**
- Good: "Increase engagement with streaming content"
- Bad: "Add a recommendation algorithm"

**Source of outcomes:**
- Product strategy
- OKRs
- Company goals
- Customer retention/growth metrics

### Step 2: Map the Customer Experience

Structure opportunities using an experience map of your customer's journey:

**Netflix example:**
1. Trigger: Decide to watch something
2. Discovery: How do I decide what to watch?
3. Evaluation: Is this content good?
4. Viewing: The actual watching experience
5. Post-viewing: What happens after?

**Each step becomes a top-level opportunity branch.**

### Step 3: Identify Opportunities Through Customer Stories

**Critical skill**: Opportunities emerge from customer STORIES, not direct questions.

**Bad approach (direct questions):**
- "What do you like to watch?"
- "How do you decide what to watch?"
- These give facts, not insight into experience

**Good approach (story-based):**
- "Tell me about the last time you watched a movie"
- "Walk me through what happened"
- "Where were you? Who were you with? What happened first?"

**You'll hear needs the customer isn't even aware of.**

### Step 4: Frame Opportunities Correctly

**The #1 mistake: Writing opportunities as solutions.**

**Test your opportunity:**
- Does it describe a customer need, pain point, or desire?
- Is it solution-agnostic?
- Could competitors have the same opportunity?

**Bad (solution):** "Needs a better recommendation algorithm"
**Good (opportunity):** "Can't tell if this show is good or not"

**Bad (solution):** "Wants easier login"
**Good (opportunity):** "Hard to enter password using TV remote"

**Be specific:**
- Bad: "I wish this was easier to use" (too vague)
- Good: "Hard to select specific letters on screen with Apple TV remote" (specific, solvable)

### Step 5: Structure Opportunities Vertically

Opportunities decompose into smaller, more specific opportunities:

**Level 1**: I can't decide what to watch (big, evergreen)
↓
**Level 2**: I can't tell if this show is any good (decomposed)
↓
**Level 3**: I don't know who's in the cast (specific, solvable)

**The deeper you go, the smaller and more actionable the opportunity.**

### Step 6: Generate Multiple Solutions Per Opportunity

For each specific opportunity, brainstorm multiple possible solutions:

**Opportunity**: "Hard to enter password with TV remote"
- Solution A: Voice input for passwords
- Solution B: QR code login from phone
- Solution C: Email magic link
- Solution D: Biometric via phone handoff

**Always have 3+ solutions before committing to one.**

### Step 7: Test Assumptions Before Building

For each promising solution, identify and test assumptions:

**Assumption types:**
- Desirability: Will customers want this?
- Viability: Does this work for the business?
- Feasibility: Can we build this?
- Usability: Can customers use this?

**Create lightweight tests** before committing to full development.

### Step 8: Maintain and Update the Tree

The OST is a living document:
- Add new opportunities from ongoing customer interviews
- Remove or deprioritize opportunities that aren't resonating
- Update solutions as you learn from tests
- Revisit quarterly or as strategy changes

## Guidelines for Tree Structure

**Horizontal breadth (top level):**
- 3-7 opportunity branches at top level
- Map to steps in customer experience
- More than 9 becomes hard to process

**Vertical depth:**
- Go deep enough that opportunities are solvable
- Each level should be smaller than the one above
- 2-4 levels is typical

**Solutions:**
- Multiple solutions per opportunity
- Compare and test before committing
- Solutions can sometimes address multiple opportunities

## Expected Outcomes
- Clear visualization of where you could invest
- Strategic decisions about which opportunities to pursue
- Customer-focused product development
- Reduced risk of building wrong things
- Alignment across team on what you're solving

## Common Pitfalls

### Writing opportunities as solutions
- 98% of people do this
- If it includes a "how," it's a solution
- Opportunities are about what customers need, not how you'll help

### Staying too high-level
- "Make it easier to use" isn't actionable
- Decompose until you can solve the problem
- Specific is better than general

### Not interviewing well
- Direct questions yield opinions, not insights
- Story-based interviewing reveals true needs
- "Tell me about the last time..." unlocks context

### Using OST as a one-time exercise
- It's a continuous practice, not a phase
- Update weekly with new learnings
- Structure evolves as you learn

### Jumping to solutions too quickly
- Explore the opportunity space first
- Multiple solutions per opportunity
- Test before committing

## Related SOPs
- Customer Interview Technique
- Assumption Testing Framework
- Continuous Discovery Habits

## AI Integration Notes

### Context signals that should trigger this SOP:
- User mentions "what to build," "prioritization"
- Questions about outcome-based development
- Team is assigned metrics, not features
- Transitioning from feature teams to product teams

### How to adapt:
- For early-stage: Simpler tree, fewer branches
- For mature products: More branches, deeper structure
- For platform teams: Map to user journey through platform

### Key insight:
The OST looks simple but is hard because it requires thinking in the problem space, which is the opposite of how our brains naturally work.
