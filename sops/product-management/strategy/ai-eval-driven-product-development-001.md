# AI Eval-Driven Product Development Framework

## Metadata
- **Source**: Kevin Weil (CPO, OpenAI) - Lenny's Podcast
- **Domain**: Product Management & Strategy
- **Type**: Framework/Process
- **Applicable To**: Product Managers, ML Engineers, AI Product Teams
- **Difficulty**: Intermediate to Advanced
- **Prerequisites**: Working with AI/ML models, basic understanding of product development

## Overview
A framework for building AI products using evaluation-driven development where evals (tests for model performance) become the core mechanism for product iteration. This approach treats evals as both validation tools and continuous improvement drivers, enabling teams to systematically improve product performance while models evolve.

## When to Use
- Building products on top of LLM or AI capabilities
- Product success depends on specific model performance thresholds (60%, 95%, 99.5% accuracy)
- Working in environments where underlying technology evolves rapidly
- Need to measure and improve fuzzy inputs/outputs (unlike traditional deterministic software)
- Teaching models company-specific or use-case-specific knowledge

## Prerequisites
- Access to AI models (via API or internal)
- Understanding of your product's core use cases
- Ability to define success criteria for your product
- Basic knowledge of model fine-tuning concepts

## Procedure

### Step 1: Identify Hero Use Cases
Define the specific problems your product must solve exceptionally well.
- Identify 3-5 core scenarios where your product must excel
- For each scenario, write out what an "amazing answer" looks like
- Document the context: who is asking, what problem they're solving, what success means
- Prioritize use cases by impact and frequency

**Example from Kevin:** For ChatGPT's deep research feature, they identified complex queries that would take a human a week to research and synthesize into a 20-page answer.

### Step 2: Create Use-Case-Specific Evals
Turn your hero use cases into measurable tests.
- For each use case, create a structured eval:
  - Input: The question or problem
  - Expected output: The ideal answer or solution
  - Success criteria: How to measure quality (accuracy, completeness, tone, etc.)
- Start with 10-20 examples per use case
- Document edge cases and failure modes
- Use models themselves to help generate eval examples (models can write evals)

**Key Insight:** Evals are like quizzes for models - testing specific subject knowledge or response capabilities.

### Step 3: Establish Performance Thresholds
Determine what accuracy levels enable different product experiences.
- Map model accuracy to product viability:
  - 60% accuracy → Requires heavy scaffolding, suggestion-only UX
  - 95% accuracy → Can ship with confidence scores, human review
  - 99.5% accuracy → Can fully automate workflow
- Design your product UX around current model capabilities
- Plan for how UX will evolve as accuracy improves

**Critical Principle:** "If the model gets it right 60% of the time, you build a very different product than if it gets it right 99.5% of the time."

### Step 4: Implement Continuous Eval-Driven Improvement
Use evals as the feedback loop for model improvement.
- Run evals regularly against your current model
- Gather data from failed evals to create fine-tuning datasets
- Use eval performance as your north star metric
- Track eval scores over time as models improve
- Create new evals as you discover new use cases or failure modes

**Process Flow:**
1. Design product → Create evals → Fine-tune model
2. Test against evals → Identify gaps → Gather more data
3. Fine-tune again → Improve evals → Iterate

### Step 5: Practice Model Maximalism
Focus product development on model capabilities, not scaffolding.
- Assume models will dramatically improve every 2-3 months
- Don't over-invest in complex scaffolding around current limitations
- Build for capabilities that are "almost there"
- Ship products that work at the edge of current model capabilities
- Trust that the next model will make your product "sing"

**Kevin's Advice to Developers:** "If you're building and the product is right on the edge of the capabilities of the models, keep going because you're doing something right. Give it another couple months and the models are going to be great."

### Step 6: Customize Models with Fine-Tuning
Use evals to create company-specific or use-case-specific model variants.
- Collect company-specific data that isn't in public training sets
- Create eval sets from this proprietary knowledge
- Fine-tune base models using: "Here's a problem, here's a good answer" × 1000-10,000 examples
- Test fine-tuned models against your custom evals
- Iterate until performance meets your thresholds

**Application:** Most company processes, industry knowledge, and proprietary data isn't public - fine-tuning makes models experts in your domain.

### Step 7: Build Ensemble Architectures
Combine multiple specialized models for complex workflows.
- Break problems into specific sub-tasks
- Use different models for different purposes:
  - Smaller/cheaper models for simple classification
  - Reasoning models for complex analysis
  - Specialized fine-tuned models for domain expertise
- Chain models together with orchestration logic
- Optimize for speed, cost, and accuracy per task

**Example from OpenAI:** Customer support uses an ensemble - fast models for triage, reasoning models for complex issues, fine-tuned models for company-specific policies.

## Expected Outcomes
- Clear measurement of product readiness and model performance
- Systematic improvement path as models evolve
- Reduced time building scaffolding that becomes obsolete
- Products that improve automatically with each model iteration
- Quantifiable progress tracking via eval scores

## Common Pitfalls

### Pitfall 1: Not Breaking Down Problems Enough
**Problem:** Using single, generic, broad model calls instead of specific optimized ones.
**Solution:** Decompose your product into 10-20 specific tasks, each with custom models/prompts/evals.

### Pitfall 2: Over-Investing in Scaffolding
**Problem:** Building elaborate systems to compensate for current model limitations.
**Solution:** Build minimal scaffolding only for critical errors. Trust model evolution for other gaps.

### Pitfall 3: Treating Evals as Static
**Problem:** Writing evals once and never updating them.
**Solution:** Continuously add new evals as you discover edge cases and expand use cases.

### Pitfall 4: Ignoring Performance Thresholds
**Problem:** Shipping features before models reach necessary accuracy levels.
**Solution:** Match your UX to current model capabilities - suggestion mode at 60%, automation at 99.5%.

### Pitfall 5: Only Using Base Models
**Problem:** Using generic API models for specialized use cases.
**Solution:** Fine-tune models for company-specific knowledge and workflows.

## Related SOPs
- Fine-Tuning LLMs for Custom Use Cases
- Product Development in Rapidly Evolving Tech Environments
- Measuring AI Product Quality

## AI Integration Notes

### Context Signals for This SOP
- User is building AI-powered products
- User mentions uncertainty about model reliability
- User asks about testing AI features
- User discusses AI product iteration challenges
- User needs to measure AI product quality

### Adaptation Guidance
- For early-stage products: Focus on Steps 1-3 (hero use cases and basic evals)
- For mature products: Emphasize Steps 6-7 (fine-tuning and ensembles)
- For non-AI companies adopting AI: Start with Step 2 (creating evals) to understand current capabilities
- For infrastructure teams: Focus on Step 7 (ensemble architectures)

### Key Principles to Emphasize
1. **Intelligence is multidimensional** - Models excel at different things; test what matters for YOUR use case
2. **Evals cap product quality** - You can only improve what you measure
3. **Models evolve faster than traditional tech** - Build for tomorrow's capabilities, not just today's
4. **Fine-tuning unlocks specialized excellence** - Generic models need customization for specialized tasks

### Limitations and Edge Cases
- This framework assumes access to model fine-tuning capabilities
- Requires technical resources to implement eval infrastructure
- Best suited for products where model performance is the core value proposition
- May be overkill for simple AI features or one-off implementations
- Eval creation itself requires domain expertise and time investment
