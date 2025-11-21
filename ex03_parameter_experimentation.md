# Exercise 3: Parameter Experimentation

## Objective
Understand how parameters (temperature and top-p) affect output diversity, randomness, and focus of AI responses.

**Tools needed:** OpenAI Playground (recommended) or API access with parameter control

**Important:** You need a tool that lets you adjust temperature and top-p settings. ChatGPT web interface doesn't show these controls - use OpenAI Playground instead!

---

## Part 1: Understanding the Controls

### Quick Reminder:

**Temperature (0.0 - 2.0):**
- Low (0.0 - 0.3) = Predictable, safe, consistent
- Medium (0.7 - 1.0) = Balanced
- High (1.5 - 2.0) = Creative, random, wild

**Top-P (0.0 - 1.0):**
- Low (0.1 - 0.5) = Narrow word choices, focused
- High (0.9 - 1.0) = Wide word choices, diverse

**Rule:** Change ONE parameter at a time, not both!

---

## Part 2: Temperature Experiments

### Experiment A: Same prompt, different temperatures

**The prompt I'll use:**
<!-- TODO: Choose a creative prompt. Example:
"Write a short story about a robot learning to paint"
or
"Describe a sunset in poetic language"
or
"Create a tagline for a coffee shop"
-->

---

### Test 1: Temperature = 0.2 (Cold - Very predictable)

**Settings:**
- Temperature: 0.2
- Top-P: 1.0 (default)

**AI's response:**
<!-- TODO: Paste the response -->

**What I notice:**
<!-- TODO: Observations. Example:
- Very straightforward and simple
- Used common, safe words
- Not very creative or interesting
- Feels a bit boring but clear
- If I run it again, probably get similar response
-->

---

### Test 2: Temperature = 0.9 (Warm - Balanced creativity)

**Settings:**
- Temperature: 0.9
- Top-P: 1.0 (default)

**AI's response:**
<!-- TODO: Paste the response -->

**What I notice:**
<!-- TODO: Observations. Example:
- More interesting word choices
- Some creative descriptions
- Still makes sense and is coherent
- More enjoyable to read than temperature 0.2
- A good balance between boring and crazy
-->

---

### Test 3: Temperature = 1.8 (Hot - Very creative/random)

**Settings:**
- Temperature: 1.8
- Top-P: 1.0 (default)

**AI's response:**
<!-- TODO: Paste the response -->

**What I notice:**
<!-- TODO: Observations. Example:
- Very creative and unusual words
- Some unexpected or weird choices
- Might be confusing or not make perfect sense
- Interesting but maybe too wild
- Each run would probably be very different
-->

---

### Temperature Comparison Table:

| Temperature | Style | Creativity (1-10) | Coherence (1-10) | Best For |
|-------------|-------|-------------------|------------------|----------|
| 0.2 | <!-- TODO: Example: Boring --> | <!-- TODO: 2 --> | <!-- TODO: 10 --> | <!-- TODO: Facts, code --> |
| 0.9 | <!-- TODO: Example: Interesting --> | <!-- TODO: 7 --> | <!-- TODO: 8 --> | <!-- TODO: Stories --> |
| 1.8 | <!-- TODO: Example: Wild --> | <!-- TODO: 10 --> | <!-- TODO: 5 --> | <!-- TODO: Brainstorm --> |

**My conclusion about temperature:**
<!-- TODO: Your takeaway. Example:
Lower temperature is safer and more predictable - good when I need reliability. Higher temperature is more creative but can be too random. Medium around 0.7-1.0 seems best for most tasks.
-->

---

## Part 3: Top-P Experiments

### Experiment B: Same prompt, different top-p values

**The prompt I'll use:**
<!-- TODO: Use same or different creative prompt. Example:
"Complete this sentence in an interesting way: The old library held secrets that..."
-->

**Keep temperature constant at 1.0 for fair comparison!**

---

### Test 1: Top-P = 0.3 (Narrow choices)

**Settings:**
- Temperature: 1.0
- Top-P: 0.3

**AI's response:**
<!-- TODO: Paste the response -->

**What I notice:**
<!-- TODO: Observations. Example:
- Uses common, predictable words
- Sticks to obvious choices
- Safe and clear but not very exciting
- Feels constrained
-->

---

### Test 2: Top-P = 0.7 (Medium diversity)

**Settings:**
- Temperature: 1.0
- Top-P: 0.7

**AI's response:**
<!-- TODO: Paste the response -->

**What I notice:**
<!-- TODO: Observations. Example:
- More variety in word choices
- Some interesting but not weird
- Good balance of creativity and clarity
- Feels more natural
-->

---

### Test 3: Top-P = 1.0 (Maximum diversity)

**Settings:**
- Temperature: 1.0
- Top-P: 1.0

**AI's response:**
<!-- TODO: Paste the response -->

**What I notice:**
<!-- TODO: Observations. Example:
- Most diverse word choices
- Can pick from any possible word
- Most creative freedom
- Sometimes unexpected choices but still good
-->

---

### Top-P Comparison Table:

| Top-P | Word Variety | Focus (1-10) | Surprise Factor (1-10) | Best For |
|-------|--------------|--------------|------------------------|----------|
| 0.3 | <!-- TODO: Low --> | <!-- TODO: 9 --> | <!-- TODO: 2 --> | <!-- TODO: Technical docs --> |
| 0.7 | <!-- TODO: Medium --> | <!-- TODO: 7 --> | <!-- TODO: 5 --> | <!-- TODO: General use --> |
| 1.0 | <!-- TODO: High --> | <!-- TODO: 5 --> | <!-- TODO: 8 --> | <!-- TODO: Creative writing --> |

**My conclusion about top-p:**
<!-- TODO: Your takeaway. Example:
Top-p controls how many word options AI can pick from. Lower means more focused and predictable. Higher means more variety. I didn't see as dramatic a difference as with temperature, but it does matter.
-->

---

## Part 4: Combined Effects (Advanced)

### Experiment C: What happens when you combine them?

**Important:** This is just for observation - remember the rule is to usually change only ONE!

---

### Test: Low temperature + Low top-p (Maximum predictability)

**Settings:**
- Temperature: 0.2
- Top-P: 0.3

**Prompt:**
<!-- TODO: Your prompt -->

**AI's response:**
<!-- TODO: Paste response -->

**Character:**
<!-- TODO: Describe it. Example:
Super safe, boring, very predictable. Like talking to a dictionary. Good for when you need exact facts.
-->

---

### Test: High temperature + High top-p (Maximum creativity)

**Settings:**
- Temperature: 1.8
- Top-P: 1.0

**Prompt:**
<!-- TODO: Same prompt as above for comparison -->

**AI's response:**
<!-- TODO: Paste response -->

**Character:**
<!-- TODO: Describe it. Example:
Wild and creative, maybe too random. Like talking to someone very imaginative but possibly confusing. Good for brainstorming crazy ideas.
-->

---

### Test: Mixed settings

Try one "mixed" combination and see what happens:

**Settings:**
- Temperature: <!-- TODO: Pick one. Example: 0.3 -->
- Top-P: <!-- TODO: Pick opposite. Example: 1.0 -->

**Prompt:**
<!-- TODO: Your prompt -->

**AI's response:**
<!-- TODO: Paste response -->

**What this combination created:**
<!-- TODO: Analyze. Example:
Low temperature but high top-p = predictable choices but from a wide range. Interesting middle ground.
-->

---

## Part 5: Practical Use Cases

### Scenario testing: Choose the right parameters

For each scenario, decide what parameters to use and test it:

---

### Scenario 1: Writing code documentation

**What parameters would you use?**
<!-- TODO: Example:
Temperature: 0.2 (need clarity, no creativity)
Top-P: 1.0 (default)
Why: Code docs need to be clear and accurate, not creative
-->

**Test it with a prompt:**
<!-- TODO: Example prompt: "Explain what this Python function does: def add(a, b): return a + b" -->

**Response:**
<!-- TODO: Paste -->

**Did the parameters work well?**
<!-- TODO: Yes/No and why -->

---

### Scenario 2: Creative marketing tagline

**What parameters would you use?**
<!-- TODO: Example:
Temperature: 1.2 (need creativity)
Top-P: 1.0 (default)
Why: Want unique, catchy ideas
-->

**Test it with a prompt:**
<!-- TODO: Example: "Create 5 catchy taglines for a sustainable clothing brand" -->

**Response:**
<!-- TODO: Paste -->

**Did the parameters work well?**
<!-- TODO: Yes/No and why -->

---

### Scenario 3: Math problem solving

**What parameters would you use?**
<!-- TODO: Example:
Temperature: 0.0 (need exact answer)
Top-P: 1.0 (default)
Why: Only one right answer, no room for creativity
-->

**Test it with a prompt:**
<!-- TODO: Example: "Solve: 125 + 347 = ?" -->

**Response:**
<!-- TODO: Paste -->

**Did the parameters work well?**
<!-- TODO: Yes/No and why -->

---

### Scenario 4: Brainstorming session

**What parameters would you use?**
<!-- TODO: Your choice and reasoning -->

**Test it with a prompt:**
<!-- TODO: Your prompt -->

**Response:**
<!-- TODO: Paste -->

**Did the parameters work well?**
<!-- TODO: Yes/No and why -->

---

## Part 6: Recording Your Observations

### Pattern Recognition:

**When I need facts or accuracy, I should:**
<!-- TODO: Example:
Use low temperature (0.0-0.3) to get consistent, reliable answers
-->

**When I need creativity, I should:**
<!-- TODO: Example:
Use higher temperature (1.0-1.5) to get more interesting and varied responses
-->

**When I need focus, I should:**
<!-- TODO: Example:
Use lower top-p (0.3-0.5) to keep responses on track
-->

**When I need variety, I should:**
<!-- TODO: Example:
Use higher top-p (0.9-1.0) to get diverse word choices
-->

---

## Part 7: Surprise Findings

### What surprised me most:

**Unexpected observation 1:**
<!-- TODO: Example:
I thought high temperature would just make nonsense, but around 1.2 it's actually creative AND makes sense. Only at 1.8+ does it get weird.
-->

**Unexpected observation 2:**
<!-- TODO: Example:
Top-p changes were more subtle than temperature changes. I had to test carefully to see the difference.
-->

**Unexpected observation 3:**
<!-- TODO: Example:
Running the same prompt multiple times with high temperature gave me COMPLETELY different answers each time. With low temperature, almost identical answers.
-->

---

## Part 8: Final Comparison Challenge

### The ultimate test: Same prompt, all settings

**Your test prompt:**
<!-- TODO: Pick something that can be both creative and factual. Example:
"Explain what the moon is"
-->

Run this prompt with 3 different parameter combinations and compare:

**Test A: Safe Mode**
- Temperature: 0.2, Top-P: 1.0
- Response: <!-- TODO -->
- Character: <!-- TODO: Factual, textbook-like -->

**Test B: Balanced Mode**
- Temperature: 1.0, Top-P: 1.0
- Response: <!-- TODO -->
- Character: <!-- TODO: Interesting, clear -->

**Test C: Creative Mode**
- Temperature: 1.6, Top-P: 1.0
- Response: <!-- TODO -->
- Character: <!-- TODO: Poetic, maybe weird -->

**Which version did you like best and why?**
<!-- TODO -->

---

## Summary and Key Learnings

### The Parameter Guide I Will Remember:

| Task Type | Temperature | Top-P | Why |
|-----------|-------------|-------|-----|
| Code/Math | 0.0 - 0.2 | 1.0 | Need exact answers |
| Documentation | 0.3 - 0.5 | 1.0 | Clear and accurate |
| General Chat | 0.7 - 1.0 | 1.0 | Balanced and natural |
| Creative Writing | 1.0 - 1.5 | 1.0 | Interesting and varied |
| Wild Brainstorm | 1.5 - 2.0 | 1.0 | Maximum creativity |

### Most Important Lessons:

**1. Temperature's impact:**
<!-- TODO: Your insight. Example:
Temperature has the biggest impact on output. Small changes make big differences. Stay around 0.7-1.0 for most tasks.
-->

**2. Top-P's role:**
<!-- TODO: Your insight. Example:
Top-p is more subtle but still matters. I'll mostly keep it at default (1.0) and just adjust temperature.
-->

**3. When to experiment:**
<!-- TODO: Your insight. Example:
For creative tasks, it's worth testing different settings. For factual tasks, always use low temperature. No need to experiment there.
-->

**4. The golden rule:**
<!-- TODO: Reminder. Example:
Adjust ONE parameter at a time! Changing both makes it hard to know what's causing what.
-->

---

## My Personal Parameter Cheat Sheet:

**For my most common tasks:**

<!-- TODO: Fill in based on what you do. Example:

When I'm coding: Temperature 0.2
When I'm writing essays: Temperature 0.8
When I need ideas: Temperature 1.3
When I'm solving problems: Temperature 0.3
When I'm being creative: Temperature 1.2

-->

---

**Date completed:** _______________

**I understand how parameters affect AI outputs:** ☐ Yes ☐ No

**I can choose appropriate parameters for different tasks:** ☐ Yes ☐ No

---

## Congratulations! 🎉

You've completed all the prompt-basics exercises!

You now understand:
- ✅ Prompt anatomy and structure
- ✅ How to write effective prompts
- ✅ How to refine vague requests
- ✅ How temperature and top-p control AI behavior

**You're ready to use AI tools more effectively!**
