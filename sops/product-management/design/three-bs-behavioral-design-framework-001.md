# Three Bs Behavioral Design Framework

## Metadata
- **Source**: Kristen Berman (Irrational Labs) - Lenny's Podcast
- **Domain**: Product Management / Behavioral Design
- **Type**: Framework
- **Applicable To**: Product Managers, Designers, Growth Leads, Marketers
- **Company Stage**: All stages
- **Difficulty**: Intermediate

## Overview
The Three Bs framework is a systematic model for driving behavior change in products by focusing on three critical elements: Behavior (the specific action you want users to take), Barriers (obstacles preventing that action), and Benefits (immediate motivations to take action today). This framework has been successfully used at Google, Microsoft, LinkedIn, and hundreds of other companies to increase engagement, conversion, and retention.

## When to Use
- When designing new features or flows to maximize user adoption
- When diagnosing why users aren't taking desired actions in your product
- When optimizing conversion funnels or activation flows
- When setting team goals and aligning on what success looks like
- When conducting product reviews or strategy sessions
- Before building any feature intended to change user behavior

## Prerequisites
- Clear understanding of your product's core value proposition
- Access to user behavior data (analytics, session recordings, etc.)
- Ability to run A/B tests or experiments
- Stakeholder alignment on goals (outcomes you're trying to achieve)

## Procedure

### Step 1: Define the Behavior (First B)
The most critical step is getting "uncomfortably specific" about the exact behavior you want to change.

**Actions:**
- Identify the specific user action (not just an outcome like "retention" or "engagement")
- Get granular enough that team members will argue about the definition
- Specify:
  - What exactly the user does (the action)
  - When they do it (timing/frequency)
  - How many times (volume)
  - Any other relevant constraints

**Example - Good Behavior Definition:**
"Within seven days of somebody starting the Peloton app, they complete two 10-minute workouts with two different instructors."

**Example - Bad Behavior Definition:**
"Users log in more often" (too vague, not specific enough)

**Note:** The only wrong answer is "log in" - it's about what users do AFTER they log in that matters.

**Validation:**
- Can you measure this behavior precisely?
- Does achieving this behavior correlate with long-term retention?
- Does it provide immediate value to the user?
- Are your teammates debating the specifics? (Good sign you're specific enough)

### Step 2: Identify and Reduce Barriers (Second B)
Map all obstacles preventing users from taking the desired behavior, then systematically reduce them.

**Two Types of Barriers:**

**A. Logistical Barriers**
Physical or practical obstacles in the user's way:
- Form fields to complete
- Credit card entry
- Wait times
- Number of clicks/screens
- Information users need to gather
- Account setup requirements

**Actions to Reduce:**
- Remove unnecessary steps
- Pre-fill information when possible
- Reduce form fields to minimum required
- Implement progressive disclosure (ask for information only when needed)
- Use smart defaults
- Save progress so users can resume later

**B. Cognitive Barriers**
Mental obstacles that prevent action:
- **Uncertainty Aversion**: Users don't know what will happen or when
- **Status Quo Effect**: Doing what they did yesterday is easiest (path of least resistance)
- **Information Aversion**: Users don't want to see potentially negative information
- **Optimism Bias**: Users overestimate their ability to do something later
- **Decision Paralysis**: Too many choices or unclear options

**Actions to Reduce:**
- Provide clear expectations (what happens next, when, how long it takes)
- Make choices simple and limited (reduce paradox of choice)
- Use social proof to show others successfully taking the action
- Create rules of thumb or heuristics to simplify decisions
- Make the new behavior feel familiar or similar to existing habits

**Behavioral Diagnosis Process:**
1. Map every single step required to complete the behavior
2. Include steps before they even reach your product
3. Identify which psychology (barrier) affects each step
4. Prioritize barriers with highest impact
5. Design interventions to reduce each barrier

### Step 3: Increase Immediate Benefits (Third B)
Design immediate rewards or motivations that compel users to act TODAY (not eventually).

**Key Insight:** We are all "present biased" - we prioritize our present self over our future self. The long-term benefit isn't enough; you need immediate gratification.

**Common Immediate Benefits to Leverage:**

**Completion Bias**
- Users want to see checkboxes completed
- Progress bars that show advancement
- Visible task completion
- Example: Asana's task completion checkboxes

**Social Desirability Bias**
- Other people see what you've accomplished
- Notifications to teammates when you complete work
- Public sharing of achievements
- Social recognition or status

**Immediate Feedback**
- Instant results or outputs from actions
- Real-time updates
- Confirmation of successful completion

**Progress Toward Goal**
- Visible movement toward a milestone
- Streaks or consecutive day counters
- Achievement unlocks

**Error Reduction**
- Making an error message disappear
- Fixing a problem or warning
- Clearing notifications
- Note: Use sparingly - don't create artificial errors

**Status or Access**
- Unlock new features
- Get priority access
- Join exclusive group
- Recognition/badges

**Right for Wrong**
The concept of giving users an immediate benefit that may not be the "real" reason to do something, but motivates action:
- Real reason: Contributing to democracy by voting
- Immediate benefit: Free pizza at the polling place
- Real reason: Physical health from working out
- Immediate benefit: Instructor shout-out on Peloton

**Implementation:**
1. List all long-term benefits of the behavior
2. For each, identify what immediate benefit could motivate action today
3. Build those immediate benefits into the product experience
4. Test which immediate benefits drive the most behavior change

### Step 4: Validate and Iterate
Once you've designed interventions across all three Bs, test and measure impact.

**Testing Protocol:**
- Run controlled A/B tests with clear control groups
- Measure the specific behavior (not just proxies)
- Look for unintended consequences
- Measure both short-term behavior change and long-term retention
- Document learnings for future application

**Team Alignment:**
- Conduct workshops where teams define the behavior together
- Review the barriers as a cross-functional group
- Brainstorm immediate benefits collaboratively
- Set incentives on the behavior (not just outcomes)

## Expected Outcomes
- 15-25% improvement in conversion or behavior completion (typical range based on case studies)
- Clear team alignment on what success looks like
- Systematic approach to diagnosing behavior change challenges
- Reusable framework for all future product development
- Better understanding of user psychology and decision-making

## Common Pitfalls

**Pitfall 1: Defining vague behaviors**
- Wrong: "Increase engagement"
- Right: "Get users to complete 3 tasks within their first 7 days"
- Solution: Keep making the behavior more specific until teammates argue about it

**Pitfall 2: Only focusing on logistical barriers**
- Wrong: Just removing form fields without considering cognitive barriers
- Right: Address both logistical friction AND psychological obstacles
- Solution: Use the behavioral diagnosis process to identify all barrier types

**Pitfall 3: Relying only on long-term benefits**
- Wrong: "This will help you retire comfortably in 30 years"
- Right: "See your money grow by $X this month"
- Solution: Always pair long-term benefits with immediate gratification

**Pitfall 4: Not testing assumptions**
- Wrong: Assuming budgeting features will reduce spending because users request them
- Right: Test whether budgeting actually changes the behavior before full build
- Solution: Run small experiments to validate hypothesis before major investment

**Pitfall 5: Measuring outcomes instead of behaviors**
- Wrong: Setting KPIs on "retention" or "revenue"
- Right: Setting KPIs on specific behaviors that drive retention/revenue
- Solution: Measure and incentivize the behavior itself for better alignment

**Pitfall 6: Copying tactics without understanding context**
- Wrong: "Gamification worked for Company X, let's add it"
- Right: Understand the psychology, then design for your specific context
- Solution: Always run your own tests; behavior is contextual

## Real-World Examples

### TikTok - Reducing Misinformation Sharing
- **Behavior**: Decrease shares of misinformation videos
- **Barriers Added**: Label on video + "Are you sure?" popup (slowing users down in hot state)
- **Result**: 24% reduction in misinformation shares

### One Medical - Doctor Appointment Booking
- **Behavior**: Set up doctor's appointment during onboarding
- **Barriers Reduced**: Recommended one provider (vs. many choices), suggested appointment times, made it virtual
- **Benefits**: Immediate health question answers, quick setup
- **Result**: 20% increase in appointment bookings during onboarding

### Credit Karma - Recurring Deposits
- **Behavior**: Set up automatic recurring deposits
- **Barriers/Benefits**: Applied Three Bs framework
- **Result**: 18% increase in recurring deposit setup

### Apartment List - Signup Flow
- **Behavior**: Complete signup and create account
- **Barriers Added (Strategic)**: Questions about apartment preferences
- **Benefits**: Users engage with the benefit and understand supply
- **Result**: Increased conversion through strategic friction

## Related SOPs
- Behavioral Diagnosis and Friction Audit Process (002)
- Default Optimization for Behavior Change (003)
- Strategic Friction Application in Product Design (004)
- Right for Wrong Motivation Design (future)
- Signup Flow Optimization Using Questions (future)

## AI Integration Notes

**Context Signals to Trigger This Framework:**
- User mentions: "users aren't converting", "low engagement", "activation problems", "behavior change"
- Designing new features or flows
- Optimizing existing funnels
- Setting product team goals or KPIs
- Diagnosing product problems

**How to Apply:**
1. Always start by asking: "What is the specific behavior you want to change?"
2. If user provides vague behavior (like "engagement"), push for uncomfortable specificity
3. Walk through all three Bs systematically - don't skip any
4. Emphasize testing over assumptions
5. Reference real examples from this SOP when relevant

**Adaptations for Different Contexts:**
- B2B vs. B2C: Same framework applies, but barriers may be organizational/approval-based in B2B
- Early stage vs. growth stage: Early stage should be more hypothesis-driven; growth stage can leverage more data
- High-consideration vs. low-consideration: High-consideration products may need more barrier reduction; low-consideration may benefit from strategic friction

**Limitations:**
- Framework requires ability to run experiments (though qualitative validation also works)
- Works best when you have clear behavioral data
- Requires cross-functional collaboration for best results
- Not a silver bullet - behavior is complex and contextual
