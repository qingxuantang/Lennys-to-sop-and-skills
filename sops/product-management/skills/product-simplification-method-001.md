# Product Simplification Method: Do Half, Ship Half

## Metadata
- **Source**: Scott Belsky - Lenny's Podcast
- **Domain**: Product Management & Product Strategy
- **Type**: Process
- **Applicable To**: Product Managers, Founders, Product Leaders
- **Difficulty**: Intermediate

## Overview
The Product Simplification Method is based on the principle: "Do half the features you want to do, offer half the options you want to offer, focus on half the market you're trying to reach." This comes from hard-won experience that feature bloat dilutes the core value proposition and confuses users. When you force focus on ONE thing, that core metric operates at 10X the velocity.

## When to Use
- Planning MVP scope and deciding which features to include
- Product is too complex with multiple competing value propositions
- Core metrics are stagnating despite adding features
- User feedback mentions confusion or complexity
- Deciding what to include in a product update or redesign
- Feeling pressure to add features to match competitors

## Prerequisites
- Identified core metric that drives business value (e.g., projects published, bookings made, messages sent)
- User analytics showing which features are used and which aren't
- Clear understanding of what your product's primary job is

## Procedure

### Step 1: Identify Your Core Metric
Determine the single metric that matters most:
- What user action drives the most value for your business?
- What behavior creates network effects or viral growth?
- What do power users do most frequently?

Example from Behance: Projects published (drove traffic, engagement, and platform value)

### Step 2: Audit Existing Features
List all current features and categorize:
- **Core**: Directly enables the core metric
- **Supporting**: Helps users succeed at core metric
- **Peripheral**: Nice-to-have, not directly related to core metric
- **Unknown**: You're not sure why it exists

### Step 3: Run Killing Sprees
Systematically remove peripheral features and measure impact:

**Before removing:**
- Measure baseline core metric performance
- Identify users who actively use the feature (likely very few)
- Prepare messaging for the small group affected

**After removing:**
- Measure core metric for 48-72 hours
- Monitor support tickets and complaints
- Track whether core metric improves

**Pattern from Behance:**
- Killed Tip Exchange → project publishing went up
- Killed Groups → project publishing went up again
- Removed portfolio color controls → 24 hours of complaints, then silence, projects went up

### Step 4: Apply "Replace, Don't Just Add" Rule
When adding new features:
- For every feature added, consider what can be removed
- Ask: "What if we replaced Feature X with this new capability?"
- Force the tradeoff conversation rather than endless accumulation

### Step 5: Optimize for Problems You Want to Have
When teams ask what features to include in MVP:

**Don't build (yet):**
- Additional platforms (mobile, web, desktop variations)
- Sharing capabilities
- Advanced customization options
- Integration with other tools

**Do build:**
- Rock-solid signup flow
- Core action completion path
- Account connection/authentication
- Anything preventing core metric execution

Build features that prevent users from reaching "I want more" stage last. Only build what prevents them from getting value first.

### Step 6: Test the Half-Half Principle
When planning new features or updates:
- Write your full feature list
- Cut it in half
- Ship that half
- Measure whether core metric improved

If halving the list feels impossible, you're probably building too much.

### Step 7: Monitor for Feature Creep Patterns
Watch for these warning signs:
- Multiple features solving similar problems
- Features with single-digit percentage usage
- Support burden for features few use
- Onboarding complexity to explain features
- Core metric stagnating despite new features

## Expected Outcomes
- Core metric operates at 10X velocity when singularly focused
- Clearer value proposition for new users
- Reduced cognitive load during onboarding
- Faster product development velocity (less to build and maintain)
- More focused user feedback (about the core experience)
- Easier to optimize and improve core flows

## Common Pitfalls

### Pitfall 1: Hedging With Features
**Mistake**: "We're not sure if users want A or B, so let's build both"

**Why it fails**: Users get confused, nothing gets traction, core metric dilutes

**Solution**: Pick one hypothesis, validate it, then consider the other. Behance launched with groups, tip exchange, portfolios, and snapshots - none got traction until they killed the extras.

### Pitfall 2: Keeping Features "Just in Case"
**Mistake**: "Only a few users use it, but what if they really need it?"

**Why it fails**: Maintain burden, complexity cost, and attention dilution aren't worth it

**Solution**: Remove it. In Behance's experience, 24 hours of complaints then silence. The few power users adapt or weren't actually getting unique value.

### Pitfall 3: Building Too Early For Scale
**Mistake**: Building multi-platform, sharing, advanced features before product-market fit

**Why it fails**: These are problems you WANT to have (users loving the product and demanding more)

**Solution**: Only build what prevents core value. Let users ask for the rest.

### Pitfall 4: Confusing Simplicity With Lack of Ambition
**Mistake**: "We can't just do one thing, we need to be comprehensive"

**Why it fails**: Complexity dilutes execution quality on any single thing

**Solution**: Simple products can have huge ambitions. Instagram was photo filters and sharing - simpler than everything else, yet became a platform.

### Pitfall 5: Not Measuring After Removal
**Mistake**: Removing features without tracking impact on core metrics

**Why it fails**: Can't learn whether simplification is working

**Solution**: Establish baseline, remove feature, measure for 48-72 hours, track both complaints AND core metric movement.

## Decision Framework: What to Cut

Keep if:
- Directly enables core metric
- Prevents catastrophic user failure
- Used by >25% of active users regularly

Consider cutting if:
- Usage <10% of users
- Doesn't connect to core metric
- Duplicates functionality elsewhere
- Requires explanation to understand
- Generates support burden disproportionate to value

Definitely cut if:
- Usage <5% of users
- Hasn't been used in 30+ days by any user
- You can't articulate why it exists
- It's a "hedge" feature you built while uncertain

## Related SOPs
- First Mile Product Experience Framework
- Core Metric Identification and Optimization
- MVP Feature Prioritization Framework

## AI Integration Notes

**Context signals that should trigger this SOP:**
- User discusses feature bloat, product complexity, or feature prioritization
- Questions about MVP scope or what to build first
- Concerns about too many features diluting focus
- Metrics showing feature usage is scattered across many low-use features
- Planning product redesign or simplification initiative

**How to adapt for different situations:**
- **Early-stage startups**: Apply aggressively - ship half of half if possible. Speed of learning matters more than feature completeness.
- **Growth-stage companies**: Use for new product lines or features, harder to remove established features but still valuable to prevent accumulation.
- **Enterprise products**: Core metric may be "workflows completed" rather than single actions. Still apply simplification to each workflow.
- **Platform products**: May have multiple core metrics for different user types. Apply within each user journey separately.

**Limitations and edge cases:**
- Platform products may legitimately need more features to serve different use cases
- Some markets expect feature parity with competitors (enterprise buyers)
- Network effect products may need critical mass of features to reach utility threshold
- B2B products may have contractual obligations to maintain features

**When suggesting this SOP:**
- Be specific about which features to consider cutting based on user's context
- Ask about current feature usage data to ground recommendations
- Encourage experimentation mindset ("try removing X for a week")
- Remind that simplification is reversible if core metric suffers
