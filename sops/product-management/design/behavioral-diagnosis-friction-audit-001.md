# Behavioral Diagnosis and Friction Audit Process

## Metadata
- **Source**: Kristen Berman (Irrational Labs) - Lenny's Podcast
- **Domain**: Product Management / Behavioral Design
- **Type**: Process
- **Applicable To**: Product Managers, UX Designers, Researchers, Growth Teams
- **Company Stage**: All stages (especially valuable for established products)
- **Difficulty**: Intermediate to Advanced

## Overview
Behavioral diagnosis is a systematic process for mapping every step users take to complete a desired behavior, identifying the psychological and logistical barriers at each step, and uncovering opportunities for improvement. Think of it as "a journey map on steroids" that focuses on what users actually do versus what they say they will do. This process typically surfaces 10-20 high-impact intervention opportunities per flow analyzed.

## When to Use
- Before building a major new feature (validate it will actually change behavior)
- When a feature isn't driving expected behavior change (diagnose why)
- When optimizing critical conversion funnels
- When user research shows intent but behavior doesn't match
- When you're getting feature requests that may not solve the real problem
- Before making major product investments
- When preparing to redesign core user flows

## Prerequisites
- Defined target behavior (from Three Bs framework)
- Access to user analytics and session recordings
- Ability to take screenshots of product flows
- Understanding of basic psychological concepts (biases, heuristics)
- Time investment: 8-20 hours for thorough diagnosis
- Cross-functional team involvement (PM, Design, Research)

## Procedure

### Step 1: Define the Exact Behavior to Diagnose
Start with precision on what behavior you're analyzing.

**Actions:**
- Use the Three Bs framework to define the specific behavior
- Ensure the behavior is measurable and observable
- Confirm the behavior correlates with business outcomes
- Document why this behavior matters

**Example:**
Instead of "reduce spending" → "User reviews their transactions weekly and identifies 3 subscription charges they no longer use"

**Output:** One-sentence behavior definition that everyone agrees on

### Step 2: Map the Complete User Journey
Create a comprehensive map of every step from initial awareness to behavior completion.

**High-Level Mapping:**
1. Identify major phases (awareness → consideration → decision → action → completion)
2. List 30-50 high-level steps across the journey
3. Include steps BEFORE users reach your product
4. Include steps AFTER first interaction (what happens next?)

**Example for Budget App:**
- Pre-product: User feels financial stress → Searches for solutions → Compares options
- In-product: Downloads app → Creates account → Links bank → Sees spending → ??? → Reduces spend
- Post-action: Maintains new behavior → Feels accomplishment → Continues using

**Detailed Mapping (The Core Process):**
1. Take screenshots of every single screen in the flow
2. Create a deck of 200-300 slides (yes, really) showing each micro-step
3. Include:
   - Every click
   - Every form field
   - Every decision point
   - Every piece of information shown
   - Every wait state or loading screen
   - Every confirmation or error state

**Why This Works:**
- Forces you to see what users actually experience
- Reveals hidden friction you've become blind to
- Shows accumulation of small barriers
- Creates shared understanding across team

**Tools:**
- Screenshot tools (built-in OS tools, Snagit, CloudApp)
- Journey mapping tools (Miro, Figma, FigJam, Whimsical)
- Session recording tools (FullStory, Hotjar, LogRocket)
- User testing videos

### Step 3: Identify Psychologies and Barriers at Each Step
For each step in the journey, identify which psychological forces are at play.

**For Each Screenshot/Step, Ask:**
1. What must the user THINK at this step?
2. What must the user FEEL at this step?
3. What must the user DO at this step?
4. What could prevent them from moving forward?

**Common Psychologies to Look For:**

**Logistical Barriers:**
- Number of form fields
- Required information user may not have
- Time investment required
- Wait times or delays
- Complex instructions
- Steps requiring context switching (leaving app)

**Cognitive Barriers:**
- **Uncertainty Aversion**: User doesn't know what happens next, when, or how
- **Status Quo Effect**: New behavior is harder than current behavior
- **Information Aversion**: User doesn't want to see potentially bad news (e.g., test results, spending totals)
- **Choice Overload**: Too many options create decision paralysis
- **Loss Aversion**: Fear of losing something they have
- **Optimism Bias**: User thinks they'll do it later (procrastination)
- **Cognitive Load**: Too much to think about or remember
- **Social Comparison**: Fear of judgment or not measuring up
- **Hyperbolic Discounting**: Future benefits feel less valuable than present costs

**Annotation Method:**
- Add sticky notes to each screenshot with the psychology label
- Use color coding (red = major barrier, yellow = moderate, green = minor)
- Note which barriers are logistical vs. cognitive
- Identify cumulative effects (multiple small barriers adding up)

**Example - Health App Showing Test Results:**
- Screenshot: "Your test results are ready. Click to view."
- Psychology: Information aversion (user fears bad news)
- Barrier: User may avoid clicking or delay viewing
- Impact: Critical behavior (viewing results) gets blocked

### Step 4: Analyze What Users Actually Do vs. What They Say
Study real user behavior to validate your hypothesis.

**Data Sources:**
- Analytics: Where do users drop off? How long do they spend on each step?
- Session recordings: Watch actual user sessions
- User interviews: Ask about specific steps, not general impressions
- Support tickets: Where do users get confused or stuck?
- Experiment results: What have you already tested in this flow?

**Key Principle:**
Users are bad at predicting their own behavior. The budgeting feature that tested #1 in user interviews may have zero impact on actual spending behavior.

**Validation Questions:**
- Do users complete this step? What % drop off?
- How long does this step take? (If very long, likely high friction)
- Do users contact support at this step?
- What do session recordings show about user confusion or hesitation?

**The Budgeting Example:**
- Users requested budgeting feature in interviews
- Built and tested with 10,000 users
- Result: ZERO change in average spend or spend variability
- Why: Mapping showed budgeting required too many steps (know budget, track progress, adjust behavior multiple times) - cognitive load too high
- Better solution: Defaults and rules of thumb (simpler)

### Step 5: Prioritize Intervention Opportunities
Identify which barriers to address first.

**Prioritization Matrix:**

**Impact Potential:**
- How many users hit this barrier? (Volume)
- How much does this barrier block the behavior? (Severity)
- Is this barrier fixable? (Feasibility)

**Create Ranked List:**
1. High volume + High severity + High feasibility = DO FIRST
2. High impact but low feasibility = Explore alternatives
3. Low volume = Deprioritize unless critical

**Look for Patterns:**
- Are there common psychology types appearing repeatedly?
- Are barriers concentrated in specific phases?
- Which single intervention could remove multiple barriers?

**Output:**
- Top 10 intervention opportunities ranked by expected impact
- Estimated effort for each intervention
- Hypothesis for how each intervention will change behavior

### Step 6: Design and Test Interventions
Create experiments to reduce or eliminate top barriers.

**Intervention Design Principles:**

**For Logistical Barriers:**
- Remove steps entirely (best option)
- Make steps easier (fewer fields, better defaults)
- Save progress (let users come back later)
- Pre-fill information (reduce manual entry)

**For Cognitive Barriers:**
- Make abstract concrete (show specific examples)
- Reduce uncertainty (set clear expectations)
- Simplify choices (fewer, better options)
- Use social proof (show others doing it)
- Create rules of thumb (simple decision heuristics)
- Provide immediate feedback (confirm progress)

**Testing Approach:**
1. Don't test in isolation - use literature review first
2. Run quantitative research before building (test concepts with 1000+ users on platforms like Prolific)
3. Test multiple variations to find best approach
4. Measure the actual behavior, not user preference
5. Run A/B test in product with clear control group
6. Measure both immediate behavior change and long-term outcomes

**De-risking Strategy:**
- Literature review: Has anyone solved this before?
- Concept testing: Which of 5 approaches is most promising?
- Quick prototype: Test with 10 users in-person
- A/B test: Validate with real users at scale

### Step 7: Document and Share Learnings
Make findings actionable for the entire organization.

**Documentation Should Include:**
- Complete journey map with annotated screenshots
- Key psychologies identified at each step
- Top 10 intervention opportunities
- Test results and learnings
- Recommendations for implementation
- What didn't work (anti-patterns)

**Share With:**
- Product team (for implementation)
- Design team (for future pattern library)
- Research team (to validate in future studies)
- Other teams working on similar flows
- Leadership (for strategic insights)

**Create Reusable Assets:**
- Psychology cheat sheet for your product domain
- Template for future behavioral diagnoses
- Pattern library of interventions that worked
- Anti-pattern library of what doesn't work

## Expected Outcomes
- 10-20 high-impact intervention opportunities identified
- Deep understanding of why current behavior isn't happening
- Prevented major investment in features that wouldn't work
- Cross-functional alignment on user psychology
- 15-40% improvement in behavior completion after implementing top interventions
- Reusable process for analyzing any user flow

## Common Pitfalls

**Pitfall 1: Stopping at high-level journey mapping**
- Wrong: Create 5-slide journey map and call it done
- Right: Go deep with 200-300 screenshots showing every micro-step
- Solution: Commit to the time investment - the insights are in the details

**Pitfall 2: Only identifying logistical barriers**
- Wrong: "We need to remove 2 form fields"
- Right: "Users face uncertainty aversion because they don't know how long this will take, PLUS they have to fill 7 fields"
- Solution: Always identify both logistical AND cognitive barriers

**Pitfall 3: Trusting what users say instead of what they do**
- Wrong: Building budgeting because users requested it
- Right: Testing whether budgeting actually changes spending behavior
- Solution: Validate with behavioral data and experiments, not just interviews

**Pitfall 4: Analyzing in isolation**
- Wrong: PM alone does the diagnosis
- Right: Cross-functional team reviews together
- Solution: Workshop the findings with Design, Eng, Research, Marketing

**Pitfall 5: Not testing interventions**
- Wrong: Implement all changes based on diagnosis alone
- Right: Test top interventions before full rollout
- Solution: Build experimentation into the process from the start

**Pitfall 6: Ignoring steps before your product**
- Wrong: Start diagnosis at "user opens app"
- Right: Start at "user first becomes aware they have a problem"
- Solution: Map the complete behavior change journey, including offline steps

## Real-World Examples

### FinTech Budgeting Feature (Failure Case)
- **Situation**: Most requested feature was budgeting
- **Diagnosis**: Mapped all steps required to reduce spending via budgeting
- **Finding**: Required knowing budget, tracking progress, planning adjustments, executing multiple times - too many steps with high cognitive load
- **Result**: Experiment with 10,000 users showed ZERO behavior change
- **Learning**: User requests don't always predict behavior change
- **Better Solution**: Defaults (automatic savings) or rules of thumb (simpler decisions)

### Health App Test Results
- **Diagnosis Step**: "Click to view test results"
- **Psychology**: Information aversion (fear of bad news)
- **Barrier**: Users delay or avoid viewing results
- **Potential Interventions**: Frame positively, show social norm ("95% of users view within 24h"), provide immediate benefit (treatment options available)

### TytoCare Medical Device
- **Situation**: Complex device, unclear value
- **Diagnosis**: Users didn't understand benefits before signup
- **Intervention**: Added quiz asking about medical behavior and tech frequency
- **Psychology**: Active engagement with benefits vs. passive carousel
- **Result**: 53% of quiz completers purchased vs. 37% who didn't complete
- **Learning**: Strategic friction (quiz) can increase conversion when it clarifies value

## Related SOPs
- Three Bs Behavioral Design Framework (001)
- Default Optimization for Behavior Change (003)
- Strategic Friction Application in Product Design (004)
- Behavioral Research and Literature Review Process (future)
- User Interview Best Practices for Behavioral Insights (future)

## AI Integration Notes

**Context Signals to Trigger This Process:**
- User mentions: "feature not getting adoption", "building major feature", "users say they want X but don't use it", "optimizing conversion"
- Before building any complex new feature
- When diagnosing behavior change challenges
- When A/B tests show surprising results

**How to Apply:**
1. Guide user through complete journey mapping (don't let them skip the detail work)
2. Help identify psychological barriers using the framework provided
3. Push user to validate with behavioral data, not just interviews
4. Suggest specific interventions based on barriers identified
5. Recommend testing before full build

**Adaptations:**
- Simple flows (signup): May only need 50-100 screenshots
- Complex flows (enterprise onboarding): May need 300+ screenshots
- Early stage (no analytics): Rely more on user testing and observation
- Established products: Can leverage extensive behavioral data

**Key Questions to Ask:**
- "What behavior are you trying to change specifically?"
- "How many steps does it take for a user to complete this behavior?"
- "What do session recordings show users actually doing?"
- "What have you tested so far?"
- "Which barriers are logistical vs. cognitive?"

**Limitations:**
- Time-intensive process (8-20 hours)
- Requires access to product and data
- Best with cross-functional involvement
- Insights are contextual to specific product
