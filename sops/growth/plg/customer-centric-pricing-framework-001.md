# Customer-Centric Pricing Framework

## Metadata
- **Source**: Nilan Peiris - Lenny's Podcast
- **Domain**: Growth / Pricing / Product-Led Growth
- **Type**: Process
- **Applicable To**: Product Managers, Finance Leaders, Founders (Series A+)
- **Difficulty**: Advanced

## Overview
A cost-allocation pricing framework that prices each customer segment based on their actual cost to serve, plus margin. This approach enables continuous price reduction for most customers while ensuring profitability on every transaction. Wise used this methodology to drop prices from 6% industry standard to 0.35% while maintaining 20% EBITDA margins and becoming profitable in every transaction.

## When to Use
- When you want to pass infrastructure improvements directly to customers as lower prices
- When different customer segments have vastly different costs to serve
- When price is a key driver of word-of-mouth growth and competitive advantage
- When you have (or are building) low-cost infrastructure that competitors lack
- When pursuing a volume strategy over margin strategy
- When operating in commodity markets where price is a primary differentiator

## Prerequisites
- Financial systems that can track costs at transaction/customer level
- Engineering capability to build cost allocation infrastructure
- Product analytics to segment customers by behavior
- Clear P&L visibility with cost centers defined
- Commitment to transparency and customer-first approach
- Understanding of your core cost drivers

## Procedure

### Step 1: Map Your Cost Structure
**Objective**: Identify all costs that contribute to serving customers

Break down your P&L into three primary cost categories:

**1. People Costs**
- Customer support teams
- Operations teams
- Verification/KYC teams
- Manual processing teams
- Regional/market-specific teams

**2. Risk Costs**
- Foreign exchange risk (rate movements between quote and settlement)
- Fraud losses
- Credit risk
- Regulatory compliance failures
- Payment failures/chargebacks

**3. Partner/Infrastructure Costs**
- Banking partner fees
- Payment processor fees
- Third-party service costs (KYC, verification)
- Network/interchange fees
- Infrastructure provider costs

Create a comprehensive cost map:
```
Total Costs = People Costs + Risk Costs + Partner Costs
```

**Expected Output**: Complete list of cost categories with monthly/annual totals

### Step 2: Build Cost Allocation Engine
**Objective**: Trace every cost back to the transaction or customer that generated it

**Design the allocation system**:
- Create unique identifiers for every transaction/customer
- Tag every cost with the route/segment that generated it
- Build automated allocation for recurring costs
- Create manual allocation process for ad-hoc costs

**Allocation methodology by cost type**:

**People Costs (Cost of Poor Quality)**:
- Track support contacts by route/customer segment
- Allocate support team costs based on contact volume by route
- Track operations tasks by product type/geography
- Allocate operations costs based on manual work volume
- Example: If Australian→GBP customers call support, allocate that support cost to AUD/GBP route

**Risk Costs**:
- Track FX exposure by transaction
- Allocate realized FX losses to routes where exposure originated
- Track fraud by customer segment/geography
- Allocate fraud losses to high-risk segments

**Partner Costs**:
- Directly allocate fees to specific transactions
- Allocate fixed costs proportionally by volume or value
- Track verification costs by market requirements
- Example: If Brazilian businesses require 20 documents for verification, allocate verification team cost to Brazilian business segment

**Implementation approach**:
```
For each bill received:
1. Identify what activity generated the cost
2. Trace activity to customer segment/route/transaction
3. Allocate cost to that dimension
4. Aggregate to calculate cost per segment
```

### Step 3: Calculate True Cost to Serve by Segment
**Objective**: Understand the actual unit economics for each customer segment

**Segment dimensions to analyze**:
- Geography/route (USD→EUR, GBP→AUD, etc.)
- Customer type (consumer vs. business)
- Transaction size bands (under $100, $100-1K, $1K-10K, $10K+)
- Frequency (one-time, occasional, regular)
- Channel (web, mobile, API)

**Calculate for each segment**:
```
Cost per Transaction =
  (Allocated People Costs + Allocated Risk Costs + Allocated Partner Costs)
  / Number of Transactions in Segment
```

**Analyze the distribution**:
- Identify which 20% of customers generate 80% of costs
- Understand why certain segments are expensive:
  - Higher support contact rates?
  - More manual verification required?
  - Higher risk/fraud exposure?
  - Expensive partner infrastructure?
  - Regulatory requirements?

**Expected Output**: Cost per transaction for every customer segment, with clear understanding of cost drivers

### Step 4: Set Prices Based on Cost Plus Margin
**Objective**: Price each segment to cover costs and contribute target margin

**Pricing formula**:
```
Price = (Cost per Transaction) × (1 + Target Margin %)
```

**Pricing decisions**:
1. **High-cost segments**: Price to cover actual costs
   - Don't subsidize expensive segments with cheap segments
   - If Brazilian business verification costs $50, they should pay for it
   - This creates incentive to drive down costs over time

2. **Low-cost segments**: Pass savings to customers
   - If you've automated a route and dropped costs 50%, reduce price
   - This drives volume and word-of-mouth growth
   - Creates competitive advantage

3. **Target margin**: Set consistent margin across segments
   - Wise uses target margins that enable 20% EBITDA
   - Could be 20-30% gross margin depending on business model
   - Ensure margin covers fixed costs and growth investment

**Price change frequency**:
- Review quarterly or when costs change significantly
- Communicate price reductions proactively
- Handle price increases with grandfathering or gradual implementation

### Step 5: Identify and Address Cost Outliers
**Objective**: Systematically reduce costs for expensive segments

**For each high-cost segment, ask**:
1. **Why is this expensive?**
   - Manual work required?
   - Regulatory friction?
   - Expensive infrastructure?
   - High-risk/fraud?
   - Poor user experience causing support contacts?

2. **Can we automate it?**
   - What would it take to eliminate manual work?
   - Can we build technology to solve this systematically?
   - What's the ROI on automation investment?

3. **Can we change the infrastructure?**
   - Are there cheaper partners available?
   - Can we build direct connections (e.g., to central banks)?
   - Can we lobby for regulatory changes?

4. **Can we improve the experience?**
   - Would better UX reduce support costs?
   - Can we add in-product guidance?
   - Should we restrict access until costs drop?

**Prioritization framework**:
- High-cost, high-volume segments: Top priority (biggest total impact)
- High-cost, low-volume: Lower priority unless strategically important
- Focus on 10x cost reductions, not 10% improvements

**Expected Output**: Prioritized roadmap of cost reduction initiatives by segment

### Step 6: Engineer Away Cost Drivers
**Objective**: Invest engineering resources to systematically reduce costs

**Attack each cost category**:

**People Costs (20% improvement year-over-year typical)**:
- Automate manual operations workflows
- Build self-service support tools
- Improve product clarity to reduce support contacts
- Create intelligent routing to reduce touches
- Example: First eKYC license in Singapore eliminated need for face-to-face verification team

**Risk Costs (50% reduction over multi-year period typical)**:
- Build algorithms to manage FX exposure
- Implement dynamic hedging strategies
- Create fraud detection models
- Limit exposure-generating product features
- Example: Wise halved FX risk costs through exposure management algorithms

**Partner Costs (10x reduction possible with infrastructure changes)**:
- Negotiate better terms at scale
- Build direct infrastructure connections
- Obtain banking licenses or central bank access
- Reduce intermediaries in payment chains
- Example: Getting Bank of England, Singapore, Australia central bank accounts eliminates expensive intermediary banks

**Investment philosophy**:
```
Invest as much cashflow as possible into engineering
to engineer away these three cost categories
```

This creates a flywheel:
1. Lower costs → Lower prices
2. Lower prices → More customers
3. More customers → More volume
4. More volume → Better unit economics
5. Better economics → More to invest in cost reduction

### Step 7: Pass Savings to Customers Continuously
**Objective**: Use cost reductions to drive growth rather than margin expansion

**Decision framework at each cost reduction**:
- "Do we keep this as margin, or pass to customers as lower price?"
- Default answer: Pass to customers
- Maintain target margin percentage, not target margin dollars

**Strategic logic**:
1. Lower prices drive word-of-mouth growth
2. Word-of-mouth has lowest CAC
3. Volume growth drives better unit economics
4. Market share compounds over time
5. In commodity markets, lowest-cost provider wins long-term

**Price reduction communication**:
- Proactively announce price drops to existing customers
- Use price drops as marketing events
- Show comparison graphs vs. competitors
- Enable customers to see and share savings

**Balance with profitability**:
- Maintain minimum margin to stay profitable
- Don't sacrifice sustainability for short-term growth
- But default to customer benefit when in doubt
- Track growth acceleration after each price drop

### Step 8: Handle Price Increases for High-Cost Segments
**Objective**: Raise prices on expensive segments without destroying the experience

**Communication approach**:
1. Be transparent about why costs are higher for that segment
2. Explain the cost drivers clearly
3. Show roadmap for how you plan to reduce costs over time
4. Give advance notice before price increases

**Implementation tactics**:
- Grandfather existing customers when possible
- Phase increases gradually rather than sudden jumps
- Offer alternatives (different product features, lower-cost routes)
- Maintain best-in-market pricing even if increasing

**Strategic considerations**:
- Will price increase drive too much churn?
- Is this segment strategically important despite being expensive?
- Should we restrict access until we can offer at better cost?
- Can we bundle with other products to offset?

### Step 9: Build Conviction for Low-Price Strategy
**Objective**: Organizational alignment that low price drives long-term value

**Test the price-growth relationship**:
- When you drop prices, measure growth impact
- Track word-of-mouth attribution before/after price drops
- Measure NPS changes correlated with price changes
- Calculate customer lifetime value by price point

**Build the narrative**:
```
Strategic Bet: If we have the lowest cost platform, and it's
really fast and high quality, the world's volume will switch
to us. Incrementally optimizing price is slower than making
a strategic commitment to being the cheapest.
```

**Avoid the testing trap**:
- Don't split test every price change for statistical significance
- A/B testing price is difficult: 10% price drop needs >10% volume increase same-day to "win"
- But word-of-mouth growth accumulates over months/years
- Build conviction through customer feedback, not short-term experiments

**Get organizational buy-in**:
- Show long-term CAC savings from word-of-mouth vs. paid marketing
- Model the flywheel effect over 3-5 years
- Demonstrate profitability maintained despite low prices
- Celebrate volume growth milestones

### Step 10: Monitor and Iterate
**Objective**: Continuously refine cost allocation and pricing

**Quarterly pricing review**:
- Update cost allocations with latest data
- Recalculate prices for each segment
- Identify new high-cost segments to address
- Review progress on cost reduction initiatives
- Decide on price changes

**Key metrics to track**:
- Cost per transaction by segment (trending down)
- Average price across all routes (trending down)
- Volume growth rate (trending up)
- Word-of-mouth percentage (trending up)
- Profit margin percentage (stable at target)
- NPS by segment (trending up as prices drop)

**System refinement**:
- Improve cost allocation accuracy over time
- Add new dimensions of segmentation
- Automate more of the allocation process
- Build dashboards for real-time visibility

## Expected Outcomes
- Profitability on every transaction despite industry-leading low prices
- Continuous price reduction as costs decrease (e.g., 6% to 0.35% over time)
- 20%+ EBITDA margins maintained
- Price-driven word-of-mouth growth acceleration
- Clear visibility into unit economics by segment
- Data-driven prioritization of cost reduction initiatives
- Sustainable competitive advantage through cost leadership

## Common Pitfalls

**Subsidizing expensive segments indefinitely**
- Don't let high-cost customers hide in blended pricing
- Charge them closer to cost to create urgency to fix
- Otherwise no incentive to reduce costs

**Keeping cost savings as margin expansion**
- In commodity markets, someone will eventually undercut you
- Pass savings to customers preemptively
- Use price leadership to drive word-of-mouth growth

**Over-relying on split testing for price changes**
- Price A/B tests rarely show positive results short-term
- Word-of-mouth accumulates over months
- Build conviction through customer insight and strategic logic

**Insufficient investment in cost reduction**
- The flywheel only works if you continuously engineer away costs
- Dedicate significant engineering resources to infrastructure
- Take multi-year view on ROI

**Poor communication of price changes**
- Customers need to understand the value they're getting
- Highlight savings vs. alternatives explicitly
- Use price drops as growth marketing opportunities

**Not addressing root causes of high costs**
- Don't just accept that certain segments are expensive
- Ask "why is this theoretical limit?" and work backwards
- Tackle regulatory, infrastructure, and technical barriers

## Related SOPs
- word-of-mouth-growth-framework-001.md
- unit-economics-optimization-001.md
- product-led-growth-at-scale-001.md
- cost-reduction-prioritization-001.md

## AI Integration Notes
**Context signals that should trigger this SOP**:
- User asks about pricing strategy, pricing models, or unit economics
- User mentions tight margins or price-sensitive markets
- User wants to reduce prices while maintaining profitability
- User asks about cost allocation or activity-based costing
- User discusses product-led growth or word-of-mouth growth

**How to adapt for different situations**:
- **B2B SaaS**: Allocate support and onboarding costs by customer segment
- **Marketplaces**: Allocate costs to both supply and demand sides
- **Usage-based products**: Allocate infrastructure costs by usage level
- **Early stage**: Start with simpler allocation (80/20 rule)
- **Scale stage**: Build sophisticated allocation engine with automation

**Limitations and edge cases**:
- Requires significant volume to have statistical significance by segment
- Complex cost structures may take 6-12 months to model accurately
- Not suitable for pure luxury positioning (price = signal)
- Regulatory restrictions may limit pricing flexibility in some markets
- May need to maintain minimum prices for brand perception
- Customer perception challenges if prices vary significantly by segment
