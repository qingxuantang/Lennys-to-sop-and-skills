# Two-Sided ROI Modeling for Marketplaces

## Metadata
- **Source**: Dan Hockenmaier - Lenny's Podcast
- **Domain**: Growth / Marketplaces
- **Type**: Process + Framework
- **Applicable To**: Marketplace founders, Growth leads, Finance/Analytics teams
- **Difficulty**: Advanced
- **Company Stage**: Seed through Growth stage
- **Related Frameworks**: Unit economics, LTV:CAC, Payback period

## Overview
Traditional ROI models break down for marketplaces because acquiring a customer or supplier has cascading costs on the other side. This framework shows how to build dual-sided ROI equations that fully internalize marketplace dynamics, enabling you to push acquisition as aggressively as possible while maintaining healthy economics.

## When to Use
- When deciding how much to spend on supply vs demand acquisition
- When traditional LTV:CAC ratios don't account for marketplace interdependencies
- When debating marketplace "balance" without clear investment guidance
- When setting acquisition budgets across both sides of the marketplace
- When evaluating which side of the marketplace to prioritize

## Prerequisites
- Understanding of basic unit economics (CAC, LTV, payback period)
- Historical data on acquisition costs for both sides
- Understanding of your supply-to-demand ratio at different segments
- Customer/supplier lifetime value calculations
- Transaction data to calculate ratios

## Core Principle

**Traditional Mistake**: Treating supply and demand acquisition as independent channels with separate ROI calculations.

**Correct Approach**: Every customer acquisition requires corresponding supply (and vice versa). Build ROI models that account for the full cost of enabling a transaction on both sides.

As Dan explains: "If you're acquiring a new customer, you need to include the CAC of acquiring that customer, but also the CAC of acquiring the supply for that customer to purchase, which is based on some ratio between the two."

## Procedure

### Step 1: Calculate Supply-to-Demand Ratios
Understand the relationship between supply and demand volume:

**Determine Current Ratios:**
1. **For each new customer, how much supply is needed?**
   - Example (Uber): 1 driver can serve 10 passengers per day
   - Ratio: 0.1 drivers per passenger

2. **For each new supplier, how much demand is needed?**
   - Example (Uber): Each driver needs 10 rides per day to make target earnings
   - Ratio: 10 passengers per driver

**Calculate by Segment:**
- Ratios vary by geography, time of day, category
- Dense urban markets may need different ratios than suburban
- Peak vs off-peak times have different requirements
- Use actual transaction data, not assumptions

**Example Calculation (Uber):**
```
Market: San Francisco, weekday evenings
- Average driver serves: 12 rides in 4-hour shift
- Driver ratio needed: 1 driver per 12 passengers
- Passenger ratio needed: 12 passengers per driver
```

### Step 2: Build Demand-Side ROI Equation
Calculate the true cost of acquiring a customer, including the supply needed to serve them:

**Formula:**
```
True Demand CAC = Customer CAC + (Supply CAC × Supply Ratio)

Where:
- Customer CAC = Direct cost to acquire one customer
- Supply CAC = Direct cost to acquire one supplier
- Supply Ratio = How many suppliers needed per customer
```

**Example (Uber):**
```
Customer CAC: $50 (ads, promotions, referrals)
Driver CAC: $200 (sign-up bonus, onboarding)
Supply Ratio: 0.1 drivers per passenger (1 driver serves 10 passengers)

True Demand CAC = $50 + ($200 × 0.1)
                = $50 + $20
                = $70
```

**Compare to Customer LTV:**
```
Customer LTV: $400 (over 12 months)
LTV:CAC = $400 / $70 = 5.7x
Payback Period: Calculate based on margin per ride and ride frequency
```

### Step 3: Build Supply-Side ROI Equation
Calculate the true cost of acquiring a supplier, including the demand needed to transact with them:

**Formula:**
```
True Supply CAC = Supply CAC + (Customer CAC × Demand Ratio)

Where:
- Supply CAC = Direct cost to acquire one supplier
- Customer CAC = Direct cost to acquire one customer
- Demand Ratio = How many customers needed per supplier
```

**Example (Uber):**
```
Driver CAC: $200
Customer CAC: $50
Demand Ratio: 10 passengers per driver (to make driver happy)

True Supply CAC = $200 + ($50 × 10)
                = $200 + $500
                = $700
```

**Compare to Driver LTV:**
```
Driver LTV: $3,500 (commission over 6 months average tenure)
LTV:CAC = $3,500 / $700 = 5.0x
Payback Period: Calculate based on commission per ride
```

### Step 4: Account for Nuance and Complexity
Real marketplaces have additional factors to incorporate:

**Refinements to Consider:**

1. **Existing Supply/Demand Base**
   - If you already have idle supply, the marginal cost of supply for new demand may be $0
   - If you have unfilled demand, marginal cost of demand for new supply may be $0
   - Adjust ratios based on current utilization

2. **Cross-Side Referrals**
   - Suppliers may refer customers (reduces demand CAC)
   - Customers may refer suppliers (reduces supply CAC)
   - Model these as negative CAC or increased LTV

3. **Multi-Tenanting**
   - If suppliers/customers use multiple platforms, LTV may be lower
   - Factor in share-of-wallet metrics
   - May increase CAC as they compare platforms

4. **Network Effects on CAC**
   - As marketplace grows, organic acquisition increases (CAC decreases)
   - Later cohorts often have better CAC than early cohorts
   - Model CAC as function of marketplace maturity

**Advanced Formula:**
```
True Demand CAC = (Customer CAC - Cross-Side Referral Value) + (Supply CAC × Incremental Supply Ratio)

Where Incremental Supply Ratio accounts for existing idle supply
```

### Step 5: Set Acquisition Investment Thresholds
Use ROI models to determine how aggressively to invest:

**Set Payback Period Targets:**
1. **Define acceptable payback window**
   - Early-stage: May accept 12-18 month payback
   - Growth-stage: Often target 6-12 months
   - Depends on cash position and growth goals

2. **Calculate maximum CAC at target payback**
   - Work backwards from payback period
   - Example: If you earn $20/month margin per customer and want 6-month payback, max CAC = $120

3. **Push acquisition to the threshold**
   - Spend up to max CAC on both sides
   - Don't artificially constrain if ROI is positive

**Investment Decision Rules:**
```
IF (True Demand CAC < Max Acceptable CAC)
  → Increase demand acquisition spend

IF (True Supply CAC < Max Acceptable CAC)
  → Increase supply acquisition spend

IF (Both are below threshold)
  → Increase both proportionally to maintain ratios
```

### Step 6: Monitor and Adjust for Externalities
Watch for dynamics not captured in ROI equations:

**Supply-Side Externalities:**
- **Supply dissatisfaction**: If demand is too low, suppliers may churn faster, badmouth platform
- **Supply quality degradation**: Oversupply may attract lower-quality suppliers
- **Platform switching**: Oversupply may push suppliers to competitors

**Demand-Side Externalities:**
- **Wait time/availability**: Under-supply degrades experience beyond what LTV captures
- **Quality concerns**: Too many low-quality suppliers harm brand
- **Customer expectations**: Inconsistent availability destroys trust

**Monitoring Approach:**
1. Set extreme threshold alerts (e.g., supply utilization <20% or >95%)
2. Track qualitative feedback and NPS by supply density
3. Monitor supplier churn rates by utilization level
4. Watch for non-linear changes in retention at extreme ratios

**When to Override the Model:**
- If externalities show clear degradation despite positive ROI
- Usually manifests as retention problems before ROI breaks
- Use liquidity metrics (from Liquidity Optimization SOP) as guardrails

### Step 7: Iterate Based on Segment Performance
ROI models should be segmented and refined:

**Segment-Specific Models:**
- Different geographies have different CACs and ratios
- Different categories/verticals have different economics
- Different customer segments have different LTVs

**Build Hierarchy:**
```
Level 1: Marketplace-wide average model (directional guidance)
Level 2: Geography/category-specific models (investment allocation)
Level 3: Micro-market models (tactical optimization)
```

**Update Frequency:**
- Review quarterly as marketplace matures
- Update CAC assumptions monthly
- Refresh LTV calculations quarterly
- Adjust ratios as liquidity improves

## Critical Rules

### Rule 1: Ignore Marketplace Balance Ratios, Focus on ROI
"I've actually become less and less focused on pure marketplace balance metrics. They're important to monitor, so ratio of buyers to sellers... But actually the thing that matters is can you write an ROI equation for acquiring supply and demand which fully internalizes the marketplace dynamic."

- A "balanced" marketplace with poor economics is not sustainable
- An "imbalanced" marketplace with strong ROI on both sides is fine
- Push both sides to their ROI thresholds, don't artificially balance

### Rule 2: Push Acquisition to Payback Thresholds
"If you have dual-sided ROI equations which are appropriately capturing this dynamic, actually I think you can somewhat ignore marketplace balance and just push your acquisition all the way out to the payback period that you're comfortable with on either side."

- Don't leave growth on the table if ROI is positive
- Marketplace will naturally balance if both sides have healthy economics
- Growth speed is often more important than perfect balance

### Rule 3: Watch for Externalities
"The one exception to this would be are there externalities which you can't capture in this equation. So for example, if you have too little demand for Uber drivers, at some point do they just become disillusioned with the service, switch to Lyft, talk badly about it on social media."

- Models don't capture everything
- Set extreme threshold alerts
- Use qualitative feedback to catch externalities early

## Expected Outcomes
- Clear investment targets for both supply and demand acquisition
- Elimination of arbitrary "balance" constraints that limit growth
- Faster growth by pushing both sides to economic thresholds
- Better capital efficiency through dual-sided thinking
- Aligned incentives across growth teams (not competing for budget)

## Common Pitfalls

### Pitfall 1: Treating Sides Independently
**Problem**: Growth team manages demand CAC, supply team manages supply CAC separately
**Result**: Optimize locally but miss total economics; may overspend on one side
**Solution**: Build dual-sided models and share accountability for total ROI

### Pitfall 2: Using Wrong Ratios
**Problem**: Using average ratios instead of marginal/incremental ratios
**Result**: Over-estimate CAC when you have idle supply/demand capacity
**Solution**: Calculate incremental ratios based on current utilization

### Pitfall 3: Ignoring Geographic/Categorical Variation
**Problem**: Using marketplace-wide averages for all investment decisions
**Result**: Overspend in poor-ROI markets, underspend in great-ROI markets
**Solution**: Build segmented models and allocate investment accordingly

### Pitfall 4: Optimizing for LTV:CAC Instead of Payback Period
**Problem**: "If you look at paid marketing, as you generate contribution margin, you can reinvest that and grow and actually if you link those two up explicitly, it makes it really clear why thinking about something like payback period is a much better measure of paid marketing performance than LTV to CAC because the speed at which you get enough money back to then go acquire another customer has much more bearing on how fast your business can grow."
**Result**: Constrain growth to maintain high LTV:CAC ratios
**Solution**: Focus on payback period; money returned quickly can be reinvested for compounding growth

### Pitfall 5: Forgetting to Update Models
**Problem**: Using same CAC and ratio assumptions as marketplace matures
**Result**: Stale models lead to poor investment decisions
**Solution**: Quarterly model refresh with latest data

## Related SOPs
- Marketplace Liquidity Optimization Framework
- Growth Model Development for Marketplaces
- Unit Economics Analysis
- Marketplace Expansion Decision Framework

## Real-World Example: Uber Economics

**Simplified Model:**

**Demand Side:**
- Customer CAC: $50
- Driver CAC: $200
- Supply ratio: 0.1 drivers per passenger
- True Demand CAC = $50 + ($200 × 0.1) = $70
- Customer LTV: $400
- Demand-side LTV:CAC = 5.7x ✓

**Supply Side:**
- Driver CAC: $200
- Customer CAC: $50
- Demand ratio: 10 passengers per driver
- True Supply CAC = $200 + ($50 × 10) = $700
- Driver LTV: $3,500
- Supply-side LTV:CAC = 5.0x ✓

**Investment Decision:**
Both sides have strong ROI → Invest aggressively in both channels up to payback thresholds

**Reality Check:**
Monitor for externalities:
- Driver utilization <30% → Drivers becoming dissatisfied
- Passenger wait times >8 min → Customers getting poor experience
- Either triggers rebalancing even if ROI equations look good

## Practical Implementation Checklist

### Setup Phase
- [ ] Calculate current supply-to-demand ratios overall
- [ ] Segment ratios by key dimensions (geo, category, time)
- [ ] Gather CAC data for both sides over last 3-6 months
- [ ] Calculate LTV for both sides (or use industry benchmarks)
- [ ] Determine acceptable payback period for your stage/cash position

### Build Phase
- [ ] Create demand-side ROI equation
- [ ] Create supply-side ROI equation
- [ ] Calculate max CAC for each side given payback targets
- [ ] Identify which side (if either) is currently under-invested
- [ ] Set up externality monitoring (utilization, satisfaction, retention)

### Execution Phase
- [ ] Reallocate budget toward under-invested side(s)
- [ ] Push acquisition spend to ROI thresholds
- [ ] Monitor externalities weekly
- [ ] Track cohort performance monthly
- [ ] Refresh model quarterly

### Refinement Phase
- [ ] Add segment-specific models for top markets
- [ ] Factor in cross-side referrals
- [ ] Account for network effects on CAC
- [ ] Build sensitivity analysis for key assumptions
- [ ] Create automated dashboards for ongoing monitoring

## AI Integration Notes

### Context Signals That Should Trigger This SOP
- User discussing marketplace supply/demand balance
- Questions about how much to spend on acquisition
- Debates about prioritizing supply vs demand
- Discussion of marketplace unit economics
- Mentions of LTV:CAC ratios in marketplace context

### How to Adapt for Different Situations
- **Early-stage**: May lack data for precise ratios; use conservative estimates and iterate
- **Single-market**: Simpler model without geographic segmentation
- **Multi-category**: Need separate models per category if economics differ significantly
- **B2B marketplaces**: Often have longer sales cycles; adjust payback expectations

### Key Questions to Ask Users
1. "What does it cost you to acquire a customer? A supplier?"
2. "How many suppliers do you need to serve your current customer base?"
3. "What's your current supply utilization rate?"
4. "Are you seeing negative externalities (complaints, churn) from imbalance?"
5. "What payback period are you targeting given your cash position?"

### Limitations and Edge Cases
- Models assume rational, consistent behavior (reality is messier)
- Ratios change as marketplace matures (need regular updates)
- Some marketplaces have lumpy/irregular transaction patterns (harder to model)
- Network effects may create non-linear dynamics not captured in simple formulas
- Cross-side effects (e.g., high-quality supply attracting more demand) may not be fully captured
