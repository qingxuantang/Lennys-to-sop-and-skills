# Value Metrics Identification Framework

## Metadata
- **Source**: Patrick Campbell (ProfitWell) - Lenny's Podcast
- **Domain**: Pricing & Monetization
- **Type**: Framework
- **Applicable To**: Product Managers, Founders, Pricing Leads at SaaS/subscription companies
- **Difficulty**: Intermediate

## Overview
A framework for identifying and implementing the optimal value metric (pricing metric) - the unit by which you charge customers. The value metric is the single most impactful pricing decision, affecting acquisition efficiency, churn rates, and expansion revenue more than any other pricing element.

## When to Use
- You're setting pricing for a new product
- Current pricing model feels misaligned with customer value
- High churn due to customers paying for unused capacity
- Expansion revenue is difficult to generate
- Large customers and small customers pay similar amounts
- You're reviewing your pricing strategy (quarterly/annually)

## Prerequisites
- Understanding of your customer segments
- Knowledge of how different customers use your product
- Ability to track usage or consumption patterns
- Customer development/research capability
- Basic understanding of your value proposition

## Core Concept

### What is a Value Metric?
The value metric is HOW you charge, not how much you charge.

Examples:
- Per user (Slack, Notion)
- Per 1,000 visits (analytics tools)
- Per contact (email marketing tools)
- Per transaction (payment processors)
- Per API call (developer tools)
- Per GB stored (storage services)

### Why Value Metrics Matter Most

**Impact on Acquisition:**
- Disney-sized companies pay Disney prices
- Startups pay startup prices
- Automatic market segmentation without complex pricing tiers

**Impact on Churn (20-25% lower):**
- Customers can downgrade instead of canceling
- Payment aligns with actual usage
- Less feeling of "paying for what I don't use"

**Impact on Expansion Revenue (typically 2x higher):**
- Implicit upsells as usage grows
- No friction of reselling features
- Natural revenue growth with customer success

## Procedure

### Step 1: List Your Candidates
Brainstorm potential value metrics based on:

**Usage-based metrics:**
- What customers DO in your product (videos created, emails sent, reports generated)
- What customers CONSUME (storage, bandwidth, API calls)
- How many people USE it (seats, team members, departments)

**Outcome-based metrics:**
- Value the customer receives (leads generated, revenue processed, candidates screened)
- Scale of their business (company size, revenue tier, employee count)

**Hybrid approaches:**
- Base platform fee + usage overage
- Tiered user counts (1-10, 11-50, 51-200)

List 5-10 candidate value metrics.

### Step 2: Evaluate Against Criteria

For each candidate metric, score against these criteria (1-10 scale):

**Criterion 1: Alignment with Value**
- Does this metric closely correlate with the value customers receive?
- As this metric increases, does customer value clearly increase?
- Example: For a video platform, "videos created" aligns better than "login sessions"

**Criterion 2: Easy to Understand**
- Can customers immediately grasp what they're paying for?
- Is it simple to explain in one sentence?
- Will finance/procurement teams understand it?

**Criterion 3: Trackable and Measurable**
- Can you reliably track this metric?
- Is the data accurate and real-time?
- Can customers see their current usage?

**Criterion 4: Growth Potential**
- Will successful customers naturally increase this metric?
- Is there room for expansion without hitting artificial ceilings?
- Example: "Projects" scales better than "workspaces" if customers typically have one workspace

**Criterion 5: Competitive Differentiation**
- Does this metric differentiate you from competitors?
- Does it make comparisons difficult (in your favor)?
- Can it be a strategic moat?

Calculate total scores for each metric.

### Step 3: Customer Validation
For your top 2-3 value metrics:

**Quantitative Research:**
- Survey 100+ customers/prospects with Van Westendorp pricing questions
- Test willingness to pay across different metrics
- Measure comprehension and appeal

**Qualitative Research:**
- Interview 10-20 customers across segments
- Ask: "How do you measure success with our product?"
- Ask: "What would be the fairest way for us to charge?"
- Listen for natural language around units and scale

**Competitor Analysis:**
- Map how 5-10 competitors charge
- Identify gaps or opportunities
- Note which metrics customers already understand from market education

### Step 4: Financial Modeling
Build a simple model comparing metrics:

**Assumptions:**
- Current customer base and usage distribution
- Expected customer growth rates
- Typical usage patterns for small/medium/large customers

**Calculations for each metric:**
- Revenue potential across customer segments
- Natural segmentation (do big customers pay more?)
- Expansion revenue opportunity
- Downgrade risk (can customers shrink instead of churn?)

**Example:**
```
Per-user metric:
- Small customer: 5 users × $10 = $50/mo
- Large customer: 200 users × $10 = $2,000/mo
- Expansion: Adding users as team grows
- Downgrade: Can remove unused seats

Per-project metric:
- Small customer: 3 projects × $20 = $60/mo
- Large customer: 10 projects × $20 = $200/mo
- Expansion: Limited (large customers may only have a few projects)
- Downgrade: Can archive completed projects
```

### Step 5: Implementation Planning

**For a New Product:**
- Launch with your chosen value metric
- Plan to revisit after 6 months of data
- Build usage tracking into product from day one

**For Existing Product (Metric Change):**
- Grandfather existing customers or provide transition period
- Communicate changes 60-90 days in advance
- Offer choice between old and new model during transition
- Start with new customers only, then migrate existing base
- Expect 3-6 month transition period

**Technical Requirements:**
- Usage tracking and metering infrastructure
- Billing system integration
- Customer-facing usage dashboards
- Overage alerts and notifications

### Step 6: Monitor and Iterate

Track these metrics post-implementation:

**Acquisition Metrics:**
- Conversion rate by customer segment
- Average contract value by segment
- Sales cycle length

**Retention Metrics:**
- Churn rate (compare to previous metric)
- Downgrade rate
- Reasons for cancellation

**Expansion Metrics:**
- Percentage of customers expanding
- Time to expansion
- Expansion revenue as % of total revenue

**Customer Sentiment:**
- NPS scores
- Pricing-specific feedback
- Support ticket volume related to pricing

Review monthly for first quarter, then quarterly ongoing.

## Expected Outcomes
- 20-25% lower churn compared to suboptimal metrics
- 2x expansion revenue compared to feature-based upsells
- Natural segmentation (enterprise customers pay 10-100x more than SMB)
- Simplified sales conversations (less negotiation on value)
- Pricing that scales with customer success

## Common Pitfalls

**Pitfall 1: Choosing Metrics That Don't Scale**
- Example: Charging per "account" when customers only need one account
- Impact: No expansion revenue opportunity
- Solution: Find the metric that grows WITH customer success

**Pitfall 2: Too Complex or Unclear**
- Example: Combination of 3+ metrics (users + storage + API calls)
- Impact: Confused customers, difficult sales conversations
- Solution: Choose ONE primary metric, possibly one secondary

**Pitfall 3: Misaligned with Value**
- Example: Charging per login when value comes from reports generated
- Impact: Customers optimize wrong behavior, resent pricing
- Solution: Align metric with core value delivered

**Pitfall 4: Not Tracking the Metric**
- Example: Choosing "per campaign" but not instrumenting campaign tracking
- Impact: Billing errors, customer disputes, technical debt
- Solution: Build tracking infrastructure before launching metric

**Pitfall 5: Wrong Granularity**
- Example: Per 1 email vs. per 1,000 emails vs. per 100,000 emails
- Impact: Too granular = confusing micro-charges; too coarse = no segmentation
- Solution: Test different tiers, ensure 10x range between smallest and largest customers

**Pitfall 6: Ignoring Market Norms**
- Example: Being only company in space NOT charging per-user
- Impact: Confusing positioning, difficult comparisons
- Solution: Understand when to follow vs. differentiate from market standards

## Examples from Real Companies

**Great Value Metrics:**
- **Stripe**: Per transaction (perfectly aligned with customer success)
- **Slack**: Per active user (not just seats, but actual usage)
- **AWS**: Per resource consumption (exact alignment with value)
- **Mailchimp**: Per contact (scales with business growth)

**Poor Value Metrics:**
- Per login (encourages less usage)
- Per month regardless of usage (no expansion)
- Per "organization" (no scaling)
- Per feature access (requires reselling)

## Related SOPs
- [SaaS Pricing Optimization Framework](./saas-pricing-optimization-framework-001.md)
- [Annual Price Increase Process](./annual-price-increase-process-001.md)
- [Pricing Page Design Best Practices](./pricing-page-best-practices-001.md)

## AI Integration Notes
This SOP should be suggested when:
- User mentions pricing strategy or monetization
- User complains about low expansion revenue
- User mentions high churn for "not using enough"
- User asks about how to charge for their product
- User mentions misalignment between customer size and revenue

Key adaptation signals:
- **B2B SaaS**: Emphasize per-seat or per-usage metrics
- **Infrastructure/APIs**: Focus on consumption-based pricing
- **Consumer products**: Consider tiered capacity models
- **Marketplaces**: Transaction-based or GMV-based metrics
- **Hardware**: May need hybrid approach (upfront + subscription)

Limitations:
- Physical goods companies have limited flexibility
- Some markets have strong incumbents with locked-in metric expectations
- Requires technical capability to track chosen metric
- Consumer businesses may need simpler tier-based approach
