# Strategic Friction Application in Product Design

## Metadata
- **Source**: Kristen Berman (Irrational Labs) - Lenny's Podcast
- **Domain**: Product Management / Behavioral Design
- **Type**: Framework + Process
- **Applicable To**: Product Managers, UX Designers, Growth Teams, Trust & Safety Teams
- **Company Stage**: All stages (especially relevant for platforms with user-generated content)
- **Difficulty**: Advanced

## Overview
While most product design focuses on reducing friction to increase conversion, there are critical scenarios where adding friction strategically can improve outcomes. Strategic friction works by slowing users down, inserting reflection moments, or getting users to actively engage with benefits. When applied correctly, it can increase conversion (counterintuitively), reduce harmful behaviors, and improve decision quality.

## When to Use

### Use Case 1: Reducing Harmful or Unwanted Behaviors
- Sharing misinformation on social platforms
- Impulsive purchases users later regret
- Sending angry messages or emails
- Making irreversible decisions (account deletion, large transactions)
- Behaviors that harm user or others when done in "hot" emotional states

### Use Case 2: Increasing Motivation Through Engagement
- Signup flows where users don't understand the benefit
- Complex products that require user customization
- Services with high supply variety (apartments, matching services)
- Products where user needs to see value before committing

### Use Case 3: Improving Decision Quality
- High-stakes choices (medical, financial, legal)
- Decisions users frequently reverse or regret
- Choices requiring personal reflection
- Options where one-size-fits-all is inappropriate

### Use Case 4: Building Commitment and Investment
- Onboarding flows where setup quality determines success
- Communities requiring member fit
- Products with network effects (need quality over quantity)

## Prerequisites
- Clear understanding of current user behavior and drop-off rates
- Ability to run A/B tests to measure impact
- Research on user psychology in this specific context
- Legal/compliance review for changes affecting critical flows
- Analytics to measure both immediate and downstream impacts

## Core Principles

### Principle 1: Hot vs. Cold States
People make different decisions when emotional (hot state) vs. calm (cold state).

**Hot State Characteristics:**
- Emotional arousal (angry, excited, lustful, fearful)
- Impulsive decision-making
- Present-focused
- Less consideration of consequences
- Examples: Seeing misinformation and immediately sharing, impulse buying, angry email

**Cold State Characteristics:**
- Calm, rational
- Consider long-term consequences
- More aligned with stated values
- Reflective decision-making

**Strategic Friction Application:**
Cool down hot states by inserting delays, reflection prompts, or additional steps.

### Principle 2: Question-Driven Engagement
Asking questions activates thinking about a topic even if you weren't before.

**Example:**
- "Have I ever told you about my mother?" → You're now thinking about my mother
- "What kind of apartment do you want?" → You're now thinking about apartment features
- "Do you want us to pay bills immediately or weekly?" → You're now thinking about how fast we pay bills

**Strategic Friction Application:**
Use questions to get users actively engaging with your value proposition.

### Principle 3: Cognitive Processing Depth
Active engagement creates stronger mental models than passive consumption.

**Passive:** Carousel shows you benefits → You scroll past
**Active:** Quiz asks about your needs → You engage with possibilities

**Strategic Friction Application:**
Replace passive benefit communication with active engagement.

### Principle 4: The Speed-Quality Tradeoff
Fast platforms optimize for engagement, which can increase problematic behaviors.

**Example:** TikTok's speed encourages rapid sharing, including misinformation

**Strategic Friction Application:**
Intentionally slow down specific actions to improve quality or reduce harm.

## Procedure

### Step 1: Identify Friction Application Opportunity
Determine if strategic friction is appropriate.

**Diagnostic Questions:**
1. Are users making decisions they later regret?
2. Are users in a "hot" emotional state when taking this action?
3. Do users not understand the benefit before acting?
4. Is speed causing quality or safety problems?
5. Would slowing down improve outcomes without killing behavior entirely?

**Warning Signs You Need Strategic Friction:**
- High refund/return rates
- Support tickets about regretted actions
- Users don't understand value until after signup
- Harmful content spreading rapidly
- One-time decisions with big consequences
- Users saying "I didn't realize X when I did Y"

**Anti-Patterns (Don't Use Strategic Friction):**
- Users already highly motivated and informed
- Behavior is already difficult to complete
- Adding friction would disproportionately impact power users
- Business model depends on speed/ease (may need to reconsider model)

**Output:** Clear hypothesis: "Adding [specific friction] will [reduce harmful behavior / increase understanding / improve decision quality] by [mechanism]"

### Step 2: Choose the Type of Strategic Friction

**Type A: Time Delays**
Insert waiting period between decision and action.

**When to Use:**
- Hot state decisions (angry email, impulsive purchase)
- Irreversible actions (account deletion, large transactions)
- Decisions that benefit from "sleeping on it"

**Examples:**
- Gmail's "Undo Send" (5-30 second delay)
- 24-hour waiting period for large purchases
- Cooling-off period for contract cancellations

**Implementation:**
- Show countdown timer
- Explain why there's a delay
- Offer immediate alternative if needed (draft instead of send)

**Type B: Confirmation Prompts**
Require explicit confirmation of intent.

**When to Use:**
- Actions in hot emotional states
- Behaviors with negative consequences
- Platform safety issues (misinformation, harmful content)

**Examples:**
- "Are you sure you want to share this?" (TikTok misinformation)
- "This appears to be a large transaction. Confirm?" (financial apps)
- "You're about to send an email that may sound angry. Review?"

**Implementation:**
- Clear, non-judgmental language
- Explain why you're asking
- Make it easy to proceed if they're sure
- Don't overuse (friction fatigue)

**Type C: Active Engagement Questions**
Ask questions that get users thinking about benefits or consequences.

**When to Use:**
- Users don't understand value proposition
- Complex products requiring customization
- High drop-off in signup despite interest
- Products with high supply/variability

**Examples:**
- Apartment List: "What kind of apartment do you want? Studio, 1-bed, 5-bed? Patio, basement, view?"
- Trunk Club: Quiz about style preferences (133% conversion increase)
- TytoCare: Medical device quiz (53% of completers purchased vs. 37% who didn't)

**Implementation:**
- Multiple choice > open text (unless open text is genuinely easy)
- 3-7 questions (not too many)
- Each question should clarify value or fit
- Show progress (question 2 of 5)
- Make it feel helpful, not interrogative

**Type D: Information Display**
Show relevant information before action.

**When to Use:**
- Users lack critical context for good decision
- Reducing information asymmetry
- Highlighting consequences of action

**Examples:**
- Label on misinformation videos: "Unverified information"
- Show total cost before purchase (not just monthly)
- "X% of users who do Y also do Z" (social proof)

**Implementation:**
- Clear, factual information
- Non-judgmental tone
- Doesn't prevent action, just informs
- Can be combined with confirmation prompt

**Type E: Effort Requirements**
Require small amount of work to proceed.

**When to Use:**
- Filtering for commitment/fit
- Quality over quantity scenarios
- Community membership
- Preventing bot/spam behavior

**Examples:**
- Writing why you want to join community
- Completing profile before posting
- Verifying email/phone

**Implementation:**
- Clear value exchange ("This helps us match you better")
- Effort proportional to value
- Don't make arbitrary

### Step 3: Design the Intervention with Care

**Design Principles:**

**A. Proportional Friction**
Match friction level to severity of issue.
- Low stakes → Minimal friction (simple confirmation)
- High stakes → More friction (time delay + confirmation)
- Life-changing → Significant friction (cooling-off period, advisor consultation)

**B. Transparent Intent**
Explain why you're adding friction.
- "We want to help you avoid sharing unverified information"
- "This quiz helps us show you the best apartments"
- "Large transactions require extra confirmation for your security"

**C. Preserve User Agency**
Users should always be able to proceed if they choose.
- Don't block behavior entirely (unless illegal/TOS violation)
- Make it clear they can still take action
- Respect their final decision

**D. Avoid Friction Fatigue**
Too much friction everywhere creates bad experience.
- Apply only to specific high-impact moments
- Don't add friction to every action
- Test whether friction is actually necessary

**E. Non-Judgmental Framing**
Don't shame users for their choice.
- Bad: "Are you SURE you want to share this fake news?"
- Good: "This content is unverified. Share anyway or review first?"

### Step 4: Test Before Scaling

**Pre-Launch Research:**

**Literature Review:**
- Has this intervention been tested in academic research?
- What have other companies done for similar problems?
- What worked and what didn't?
- Use Google Scholar to find relevant studies

**Concept Testing:**
- Create 3-5 variations of your intervention
- Test with 1,000+ users on platforms like Prolific
- Measure behavioral intent, not preference ("Would you share?" not "Do you like this?")
- Compare conditions relatively (A vs. B vs. C)

**Qualitative Testing:**
- Show prototype to 10-15 users
- Watch how they interact with friction
- Ask: Does this feel helpful or annoying?
- Identify confusing or frustrating moments

**A/B Test Structure:**
- Control: Current experience (no friction)
- Treatment: Strategic friction added
- Measure:
  - Primary: Target behavior (shares, purchases, signups)
  - Secondary: User satisfaction, completion rate, time to complete
  - Long-term: Retention, regret indicators (refunds, support tickets)

**Success Criteria:**
Define before testing what would make this worthwhile:
- For reducing harm: X% reduction in unwanted behavior acceptable even with Y% drop in total behavior
- For increasing motivation: X% increase in conversion AND sustained engagement
- For improving decisions: X% reduction in regret indicators (returns, cancellations)

### Step 5: Monitor and Iterate

**Key Metrics:**

**Immediate Impact:**
- Conversion rate (signups, purchases, shares)
- Completion rate through friction point
- Time to complete action
- Drop-off at friction point

**Downstream Impact:**
- Retention (do users who encountered friction stick around?)
- Quality of action (did friction improve decision quality?)
- Regret indicators (returns, cancellations, support tickets)
- User satisfaction scores

**Unintended Consequences:**
- Disproportionate impact on certain user segments?
- Created new problems elsewhere?
- Users finding workarounds?
- Frustrated power users?

**Iteration Opportunities:**
- Adjust friction level (more or less)
- Test different friction types
- Refine messaging/explanation
- Apply to different user segments differently
- Add friction only in specific contexts (first-time users, high-risk situations)

## Expected Outcomes

### For Reducing Unwanted Behaviors:
- 15-40% reduction in target behavior (e.g., TikTok misinformation sharing down 24%)
- Minimal impact on wanted behaviors
- Maintained or improved platform health metrics

### For Increasing Engagement/Conversion:
- 30-150% increase in conversion (e.g., Trunk Club quiz: +133%, TytoCare: +43%)
- Higher quality users (more engaged, better fit)
- Improved long-term retention

### For Improving Decision Quality:
- 20-50% reduction in regret indicators (refunds, cancellations)
- Higher user satisfaction
- Fewer support tickets

## Common Pitfalls

**Pitfall 1: Adding friction everywhere**
- Wrong: "Strategic friction works! Let's add it to every flow!"
- Right: Apply surgically to specific high-impact moments
- Solution: Start with one critical flow, measure impact, then expand thoughtfully

**Pitfall 2: Using friction as punishment**
- Wrong: Making friction feel like you're scolding the user
- Right: Framing friction as helpful, protective, or clarifying
- Solution: Use neutral, supportive language; explain the "why"

**Pitfall 3: Not testing first**
- Wrong: Add friction based on intuition alone
- Right: Test multiple variations before launch
- Solution: Use concept testing, run A/B tests, measure actual behavior

**Pitfall 4: Ignoring user segments**
- Wrong: Same friction for everyone
- Right: Different friction for different contexts (new users vs. power users, high-risk vs. low-risk)
- Solution: Segment users and apply friction appropriately

**Pitfall 5: Measuring only conversion, not quality**
- Wrong: "Conversion dropped 5%, so friction failed"
- Right: "Conversion dropped 5%, but retention up 20% and refunds down 30%"
- Solution: Measure downstream outcomes, not just immediate conversion

**Pitfall 6: Using open text fields as friction**
- Wrong: "What apartment are you looking for?" (open text)
- Right: "What apartment are you looking for? [Studio] [1-bed] [2-bed]" (multiple choice)
- Solution: Make friction easy to complete (dropdown, multiple choice)

**Pitfall 7: Blocking behavior entirely**
- Wrong: Prevent users from taking action they want
- Right: Add friction but still allow action
- Solution: Preserve user agency - they can always proceed after friction

## Real-World Examples

### TikTok - Reducing Misinformation Shares
- **Problem**: Misinformation spreading rapidly on platform
- **Behavior Target**: Reduce shares of unverified content
- **Intervention**:
  1. Label on video: "Unverified information"
  2. Popup when clicking share: "Are you sure?"
- **Psychology**: Cooling down hot state, reminding of accuracy values
- **Result**: 24% reduction in misinformation shares
- **Key Insight**: Slowing people down in fast platform reduced harmful behavior

### Apartment List - Signup Flow
- **Problem**: Users not understanding supply/value during signup
- **Behavior Target**: Increase signup conversion
- **Intervention**: Questions about apartment preferences (studio/1-bed/5-bed, patio/basement/view)
- **Psychology**: Active engagement with benefits vs. passive carousel
- **Result**: Increased conversion (specific % not disclosed)
- **Key Insight**: Strategic friction can INCREASE conversion when it clarifies value

### Trunk Club - Style Quiz
- **Problem**: Users not understanding personalization value
- **Behavior Target**: Increase purchase conversion
- **Intervention**: Quiz about style preferences during signup
- **Psychology**: Engagement with customization benefits
- **Result**: 133% increase in conversion
- **Key Insight**: Adding steps can dramatically improve conversion if steps engage user with value

### TytoCare - Medical Device
- **Problem**: Complex device, unclear value proposition
- **Behavior Target**: Increase purchase conversion
- **Intervention**: Quiz about medical behavior and tech usage
- **Psychology**: Active consideration of use cases
- **Result**: 53% of quiz completers purchased vs. 37% who didn't complete
- **Key Insight**: Questions can clarify fit and increase qualified conversions

### Financial App - Form Field Removal
- **Problem**: Form fields creating friction
- **Behavior Target**: Increase conversion
- **Intervention**: Removed open text field question
- **Psychology**: Reduced cognitive load
- **Result**: 40% increase in page-over-page conversion
- **Key Insight**: Not all questions work - open text is particularly hard

### Email - Angry Email Prevention
- **Problem**: Users sending angry emails they regret
- **Behavior Target**: Reduce regretted sends
- **Intervention**: Detection of angry tone + prompt: "This may sound angry. Review before sending?"
- **Psychology**: Cooling down hot state
- **Result**: Reduced regretted emails, minimal impact on legitimate sends

## Related SOPs
- Three Bs Behavioral Design Framework (001)
- Behavioral Diagnosis and Friction Audit Process (002)
- Default Optimization for Behavior Change (003)
- Signup Flow Optimization (future)
- Trust and Safety Product Design (future)

## AI Integration Notes

**Context Signals to Trigger This Framework:**
- User mentions: "users sharing misinformation", "impulse buying", "high refund rate", "users don't understand value", "hot state decisions"
- Social platforms, marketplaces, financial products
- High drop-off in signup but strong intent
- Regret indicators (returns, cancellations, angry support tickets)

**How to Apply:**
1. First determine if strategic friction is appropriate (diagnostic questions)
2. Help user choose right type of friction for their context
3. Emphasize testing before launch (concept testing, A/B testing)
4. Reference relevant examples (TikTok for harm reduction, Trunk Club for engagement)
5. Warn about common pitfalls (friction fatigue, judgmental framing)

**Adaptations for Context:**
- Social platforms: Focus on harm reduction and quality
- E-commerce: Focus on reducing regretted purchases
- Financial: Focus on decision quality and security
- B2B: May need different friction for admins vs. end users
- Early stage: Use qualitative testing if can't run large A/B tests

**Key Questions to Ask User:**
- "Are users making decisions they later regret?"
- "Are they in a hot emotional state when acting?"
- "Do they understand the value before taking action?"
- "What's the consequence if they make a bad decision here?"
- "Have you tested whether friction would help or hurt?"

**Limitations:**
- Counterintuitive - goes against common product wisdom (reduce all friction)
- Requires careful testing - wrong friction kills conversion without benefit
- Risk of friction fatigue if overused
- May frustrate power users if not implemented thoughtfully
- Not appropriate for most flows - use surgically

**When NOT to Suggest:**
- User is already trying to reduce friction in a healthy flow
- No evidence of hot state decisions or regret
- Users are already struggling to complete behavior
- Business model fundamentally depends on speed/ease without consideration
