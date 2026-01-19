# Understand-Identify-Execute Growth Framework

## Metadata
- **Source**: Naomi Gleit - Lenny's Podcast
- **Domain**: Growth & Product-Led Growth (PLG)
- **Type**: Framework
- **Applicable To**: Growth teams, Product Managers, Data Analysts, early to growth stage startups (10-1000+ employees)
- **Difficulty**: Intermediate

## Overview
The Understand-Identify-Execute framework is a data-driven, product-focused approach to growth that Facebook's legendary growth team pioneered. Instead of relying on marketing or business functions to drive user acquisition and retention, this framework emphasizes using comprehensive data instrumentation to understand user behavior, identify the highest-leverage growth opportunities, and execute product solutions to address them.

## When to Use
- When starting a new growth initiative or forming a growth team
- When you lack clarity on which growth levers will have the most impact
- When transitioning from marketing-driven to product-driven growth
- When facing retention or activation challenges
- Before building growth features or optimizing user flows
- When you suspect data gaps are preventing informed decision-making

## Prerequisites
- Product with early signs of product-market fit
- Access to analytics infrastructure or ability to implement tracking
- Engineering resources to instrument data and build solutions
- Stakeholder buy-in to pause feature development for data work

## Procedure

### Step 1: Understand - Instrument Comprehensive Data
The foundation of data-driven growth is having the data you need to make informed decisions.

- **Audit current data coverage**: Identify all critical user flows (registration, onboarding, activation, core features)
- **Identify data gaps**: Document where you lack visibility into user behavior or drop-off points
- **Prioritize instrumentation**: Focus first on flows most directly related to growth (acquisition, activation, retention)
- **Instrument every step**: Track every single step in critical flows, not just entry and exit points
  - Example: Don't just track "started registration" and "completed registration"
  - Track: email entry, email confirmation, profile creation, each sub-step, etc.
- **Commit fully to data work**: Be willing to pause feature development to complete instrumentation
  - Facebook's growth team spent January 2009 exclusively instrumenting data
  - Alex Schultz's principle: "Guess when you can know" - if you can measure it, you should
- **Build growth accounting dashboards**: Create visibility into:
  - New user registrations
  - Churned users (e.g., users who don't return after 30 days)
  - Resurrected users (users who return after churning)
  - Net growth = New + Resurrected - Churned

**Key Insight**: Facebook discovered that their churn and resurrection lines were much larger than new user acquisition, revealing that retention was the biggest leverage point for growth.

### Step 2: Identify - Find Highest-Impact Opportunities
Use your instrumented data to identify what will move the needle most.

- **Analyze drop-off points**: Look for the biggest gaps in user flows
  - Example: Facebook found 20% of users weren't confirming their email
  - This represented a massive opportunity to reduce friction
- **Correlate actions with retention**: Identify which user behaviors predict long-term retention
  - Facebook discovered that users with 7 friends in 10 days (or 10 friends in 14 days) had significantly higher retention
  - This became their activation metric
- **Distinguish between macro and micro barriers**:
  - **Macro barriers**: Large segments of potential users who can't access the product
    - Examples: Language barriers, device requirements, internet access, eligibility criteria
  - **Micro barriers**: Friction points within existing flows
    - Examples: Unnecessary confirmation steps, unclear UI, missing features in onboarding
- **Prioritize based on impact**: Focus on opportunities with the largest potential user impact
- **Validate with cohort analysis**: Use retention curves to understand if improvements stick over time

**Key Insight**: Don't just optimize for acquisition. Often retention and engagement provide larger growth opportunities than top-of-funnel work.

### Step 3: Execute - Build Product Solutions
Implement data-driven product improvements to address identified opportunities.

- **Remove barriers systematically**: Start with the highest-impact barriers
  - **Macro barrier examples**:
    - Opening registration to new user segments (high school, work networks, open registration)
    - Building for lower-end devices or limited connectivity
    - Creating community-driven translation systems (100+ languages)
  - **Micro barrier examples**:
    - Simplifying email confirmation (accept any email click, not just confirmation link)
    - Streamlining registration flows to reduce steps
    - Building new user onboarding experiences (profile picture upload, friend finding)
- **Optimize for activation metrics**: Build features specifically to drive users to their "aha moment"
  - Design onboarding flows to guide users to activation (e.g., 7 friends in 10 days)
  - Make the path to value obvious, especially for non-intuitive user segments
  - Example: Facebook didn't need onboarding for college students but did for parents and grandparents
- **Test and iterate**: Use A/B testing to validate product changes
- **Measure perfect execution**: Ensure you're executing the strategy well enough to learn from results
  - Best case: Right strategy + perfect execution = success
  - Next best: Wrong strategy + perfect execution = learn and pivot quickly
  - Worst case: Wrong strategy + poor execution = can't learn what went wrong

### Step 4: Maintain and Extend the Approach
Apply this framework beyond just growth.

- **Make it a repeatable practice**: Continue the understand-identify-execute cycle
- **Extend to other domains**: Apply data-driven, product-led approach to traditionally business functions
  - Example: Facebook applied this to social impact (built fundraising products vs. traditional corporate giving)
  - Example: Community-driven translation vs. hiring professional translators
- **Share learnings**: Document what you learned to inform future growth work
- **Revisit macro barriers**: As your product evolves, new macro barriers emerge (e.g., mobile vs. desktop)

## Expected Outcomes
- **Clarity on growth levers**: Data-driven understanding of what actually drives growth
- **Higher retention rates**: Focus on activation and engagement, not just acquisition
- **Faster iteration**: Clear metrics enable rapid testing and learning
- **Reduced wasted effort**: Build features that address real, measured barriers
- **Product-led growth culture**: Shift from marketing-driven to product-driven growth mindset
- **Scalable growth processes**: Framework extends to new products and markets

## Common Pitfalls
- **Starting execution before understanding**: Building features without data leads to guessing
  - *How to avoid*: Resist pressure to ship features before instrumenting properly
- **Incomplete instrumentation**: Only tracking entry/exit points misses critical drop-offs
  - *How to avoid*: Track every single step in important flows
- **Focusing only on acquisition**: Ignoring retention when it may be the bigger lever
  - *How to avoid*: Build growth accounting dashboards to see the full picture
- **Confusing correlation with activation**: Picking an activation metric that doesn't predict retention
  - *How to avoid*: Use retention curve analysis, not just gut feeling
- **Over-crediting the growth team**: Attributing all growth to tactics when product-market fit is the real driver
  - *How to avoid*: Be honest about how much is product-market fit vs. optimization
- **Optimizing flows for a product without PMF**: No amount of growth optimization fixes a product people don't want
  - *How to avoid*: Ensure you have early product-market fit signals before investing heavily in growth

## Related SOPs
- Instagram Growth Case Study (sops/growth/instagram-growth-case-study-001.md)
- Adjacent User Theory (sops/growth/adjacent-user-theory-001.md)
- A/B Testing Implementation (sops/experimentation/ab-testing-implementation-001.md)
- Product-Market Fit Assessment (to be created)

## AI Integration Notes
This SOP should be triggered when:
- User mentions "starting a growth team" or "growth strategy"
- User asks about "data-driven growth" or "growth instrumentation"
- User mentions challenges with "user retention," "activation," or "drop-off"
- User is struggling to identify which growth initiatives to prioritize

Adapt this framework by:
- Scaling the scope based on company size (startups may instrument fewer flows initially)
- Adjusting timeline expectations (full instrumentation may take weeks to months)
- Emphasizing product-market fit validation before heavy growth investment
- Recognizing that some businesses (B2B, enterprise) may have different growth models

Key principle to emphasize: "Guess when you can know" - if you can measure something that matters, you should measure it before making decisions.

Edge cases:
- Early-stage startups without engineering resources may need to use lighter-weight analytics
- B2B products may need different activation metrics (e.g., team adoption, not individual usage)
- Products without clear "aha moments" may need more experimentation to find activation metrics
