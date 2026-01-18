# Product-Led Sales (PLS) Implementation

## Metadata
- **Source**: Elena Verna - Lenny's Podcast (Episode 2.0)
- **Domain**: Growth / Product-Led Growth
- **Type**: Process SOP
- **Applicable To**: Growth Leaders, Product Leaders, Sales Leaders, Founders
- **Company Stage**: Series A+, Post-PMF
- **Company Size**: 50+
- **Difficulty**: Advanced

## Overview
Product-Led Sales (PLS) bridges the gap between product-led growth (PLG) and enterprise sales by converting self-serve product usage into sales pipeline. This SOP guides you through implementing a PLS motion that leverages product usage signals to qualify accounts and close larger enterprise contracts ($15K+).

## When to Use
- Your PLG motion has organic hand-raisers asking about enterprise plans
- Self-serve revenue is capped (~$10K per transaction) and you want to go upmarket
- You have established product-market fit with active, engaged users
- You're targeting mid-market (200+ employees) or enterprise (1000+) segments
- Your existing top-down sales motion isn't working because customers need to see value first

## Prerequisites
- Active self-serve user base with measurable engagement
- Product analytics infrastructure (Amplitude, Mixpanel, etc.)
- Clear understanding of your ideal customer profile (ICP)
- Baseline engagement and activation metrics established

## Procedure

### Step 1: Validate Organic Demand
Before building PLS infrastructure, confirm organic pull exists:
- Monitor support channels for enterprise purchase requests
- Track "contact sales" form submissions
- Look for hand-raisers through product usage signals
- **Critical**: Never hire salespeople until you feel this organic pull

### Step 2: Profile Your Users at Sign-up
Implement onboarding questions (3-4 screens max):
- Company size
- Department/team
- Seniority level
- Primary use case
- **Note**: Drop-off from profiling questions indicates low-intent users who wouldn't activate anyway

### Step 3: Define Product Qualified Account (PQA) Criteria
Start with intuition, then validate with data:

**Key signals to track:**
- Number of users per account (magic number often = 7)
- Volume thresholds (events sent, boards created, storage used)
- Velocity changes (sudden increase in user additions)
- Feature breadth (enterprise feature usage)

**Behavioral signals:**
- Admin transfers/changes (indicates evaluation)
- Terms of Use / Privacy Policy page views (indicates enterprise buyer interest)
- Pricing page visits

### Step 4: Distinguish PQA, PQL, and MQL
- **PQA (Product Qualified Account)**: Account-level aggregation showing enterprise readiness
- **PQL (Product Qualified Lead)**: Actual buyer/decision-maker within the user base
- **MQL (Marketing Qualified Lead)**: Lead brought in by marketing, may or may not have product usage

**Important**: 90% of PLS is finding the buyer OUTSIDE your user base. End user ≠ enterprise buyer.

### Step 5: Structure Team Collaboration
Reconfigure internal relationships:
- **Old model**: Marketing → Sales → Product (post-sale)
- **PLS model**: Product → Sales (Product creates pipeline)

**Product team must own:**
- PQA targets (conversion rate to PQA from engaged ICP teams)
- Free-to-paid conversion rates
- Pipeline creation metrics

### Step 6: Start Manual, Then Scale
1. Begin with Google Sheets and existing BI tools
2. Use intuition + sales feedback to identify patterns
3. Build simple regression models on top signals
4. Only invest in PLS platforms after achieving "data-sales fit"

### Step 7: Pilot with Dedicated Sales Resource
- Don't dump PLS leads into existing top-down sales funnel
- Assign one AE or SDR to pilot the motion separately
- Track conversion rates independently
- Gather feedback on lead quality

### Step 8: Implement Three-Channel Lead Attribution
Track separately:
1. **Usage + PQL**: User in account is the buyer
2. **Usage + MQL**: Marketing brings buyer, connect to existing usage
3. **MQL only**: No usage, pure top-down motion

Each channel requires different playbooks and often different sales resources.

## Expected Outcomes
- 12+ months from first user to enterprise contract (typical timeline)
- Freemium conversion: ~5%
- Trial conversion: ~10-15%
- Increasing contract values and customer lifetime value
- Predictable, sustainable pipeline from product usage

## Common Pitfalls

### Don't treat PLS as traditional top-down sales
- New sign-ups are NOT MQLs ready to buy
- Users are solving individual problems, not company problems
- Reaching out 10 minutes after sign-up destroys trust

### Don't leave product out of the equation
- PLS cannot be executed through marketing/sales alone
- Product must own pipeline targets
- Product-sales relationship must be closest collaboration

### Don't ignore marketing
- Most usage won't have a buyer in it
- Marketing must find/hunt buyers via ABM
- Connect marketing-sourced buyers with existing product usage

### Don't over-automate too early
- Understand your data before scaling
- Data can tell lies; validate with sales feedback
- PQA definitions should evolve, not be static

## Related SOPs
- Free-to-Paid Conversion Optimization
- PQA Definition and Scoring Framework
- Product Team Revenue Accountability
- Enterprise Value Proposition Development

## AI Integration Notes

### Context signals that should trigger this SOP:
- User mentions "adding sales to PLG"
- Questions about "going upmarket"
- Discussion of "enterprise sales" + "self-serve"
- Challenges with "converting free users to enterprise"

### How to adapt:
- For earlier-stage companies: Focus on Steps 1-3 (validation and profiling)
- For SLG companies adding PLG: Start from enterprise down, use PLS to go downmarket
- For mature PLG companies: Focus on PQA refinement and scaling

### Limitations:
- Not applicable for pure prosumer/freelancer products
- Requires sufficient user volume for pattern detection
- Timeline expectations must account for 12+ month cycles
