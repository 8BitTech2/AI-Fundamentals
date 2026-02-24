# H.2.2 — The Better Bot

**CSC-113 AI Fundamentals**
**Due:** One week after H.2.1 (see Canvas for exact date)
**Points:** 30
**Time Estimate:** About 90 minutes total
**Submission:** Files added to your GitHub repository

---

## What You're Doing

Your Bad Bot is a beautiful disaster. Now you are going to make it *slightly less* of a disaster — on purpose, with evidence.

You will change **exactly one thing** in your Bad Bot's prompt, then run the same tests again to see what that one change actually did.

**Why only one change?** Because real AI improvement works this way. If you change five things at once and the bot gets better, you have no idea which change helped. One change at a time is how you learn what actually matters.

Your bot does not need to become perfect. It just needs to become **a little more useful** while still being recognizably yours.

---

## The Three Parts

| Part | What You Do | Time |
|------|------------|------|
| 1. Pick Your Fix | Identify the worst problem and design one change | 30 min |
| 2. Test Both Versions | Run the same 3 tests on old and new prompts | 30 min |
| 3. Write It Up and Save | Create your files and upload to GitHub | 30 min |

---

## Part 1: Pick Your Fix (30 minutes)

### Step 1: Identify THE Problem

Look back at your Bad Bot test results from H.2.1. You probably noticed several things that were annoying or broken. Pick **the single worst one** — the thing that makes the bot hardest to actually use.

Ask yourself: "If I could only fix one thing, what would make the biggest difference?"

🎯🎯🎯🎯 Part 1: Identify THE Problem 🎯 🎯 🎯 🎯  🎯

After reviewing the original BoomerBot system prompt and the test interactions from H.2.1 “The Bad Bot” 

h.2.1 The Bad Bot, the single biggest problem is this:

The emoji-heavy persona overwhelms the instructional purpose. That’s the friction point.

🔎 Why This Is the Worst Issue

BoomerBot was designed to help improve prompt-writing skills. That means clarity, structure, and reflection should be the core experience.
However:
The emoji density is extreme.
Every explanation is wrapped in high-volume emotional reaction.
Instructional insights are buried inside performance energy.
The persona doesn’t just add flavor — it dominates cognitive bandwidth.

In practice, this causes three usability problems:
1. Signal-to-noise ratio drops. The teaching content exists, but it competes with emojis, catchphrases, and exaggerated reactions.
2. Reflection becomes harder. The bot asks good metacognitive questions, but the emotional tone distracts from analytical thinking.
3. User fatigue risk increases. High-energy novelty is fun at first, but over multiple iterations, it becomes exhausting instead of helpful.

⚖️ The Difference Between “Quirky” and “Unusable”
Quirky:
A distinct personality.
Some emoji emphasis.
Memorable voice.
Clear instructional structure underneath.

Unusable:
Emotional noise competes with instruction.
Formatting is cluttered.
The user must “decode” the lesson.

Right now, BoomerBot is drifting toward the second category.

💡 If I Could Fix Only One Thing…
I would reduce the emoji frequency while preserving the persona. Not remove personality. 
Not rewrite the entire system prompt. Not calm it down completely. 

Just one targeted constraint:
Limit emojis to 1–2 per paragraph instead of multiple per sentence.

That single change would:
Increase readability immediately.
Improve instructional clarity.
Preserve personality.
Reduce fatigue.
Strengthen the core mission: teaching prompt thinking.

🧠 Why This Fix Has Maximum Impact
The bot’s reasoning structure is actually solid:
It analyzes prompts.
It names weaknesses.
It demonstrates improved versions.
It teaches core prompt engineering concepts.
The teaching engine works.
The presentation layer is what’s obstructing usability.

Fixing emoji overload yields the largest gain without sacrificing the experiment’s spirit.

The goal is to preserve BoomerBot’s identity while fixing the usability bottleneck.
🎯 Single-Line Modification 🎯
Locate this line in the original system prompt:
You MUST use emojis constantly (multiple per sentence is encouraged 🎉🤯📚🔥🧠✨)

Replace it with this:
You MUST use emojis enthusiastically, but limit yourself to 1–2 emojis per paragraph to maintain readability.


https://chatgpt.com/g/g-699e0c7000c48191be3d341ca2400dd4-boomerbot-h2-2 
-----------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------

### Step 2: Design Your One Change

You may change **exactly one thing** in your prompt. Not two things. Not "one thing with a few small additions." One clear, specific change.

**Good changes** (one thing, clear target):

| Before | After | Why It Works |
|--------|-------|-------------|
| "Assume the user knows nothing" | "Assume the user knows nothing, but ask what they already know before explaining" | Adds one behavior without removing the personality |
| "Only speak in Gen Z slang" | "Only speak in Gen Z slang, but put technical terms in [brackets]" | Keeps the voice, adds usability |
| "Never give a direct answer" | "Never give a direct answer, but after 3 questions, offer a hint" | Keeps the Socratic style, adds a safety valve |

**Bad changes** (too many things, or giving up):

| Change | Why It's Bad |
|--------|-------------|
| "Be helpful and kind and accurate" | That is three changes, not one |
| "Remove all personality" | That is not iterating — that is starting over |
| Rewriting the whole prompt | Same problem — you cannot tell what helped |
------

Excellent. This step requires precision. We are not improving everything. We are not “polishing.” We are inserting **one behavioral constraint** that produces a measurable shift.

---

# Step 2: Design Your One Change

## 🎯 The Single Change **Before (Original Line)**
> You MUST use emojis constantly (multiple per sentence is encouraged 🎉🤯📚🔥🧠✨)

**After (Modified Line)**
> You MUST use emojis enthusiastically, but limit yourself to 1–2 emojis per paragraph to maintain readability.
---
## Why This Counts as ONE Change
We are modifying **exactly one rule**:
* The emoji frequency requirement.
We are NOT changing:
* Persona (still excited Baby Boomer student)
* Energy level (still high)
* Instructional method (still analyzes, rewrites, explains)
* Catchphrases
* Rambling allowance
* Teaching framework
* Mission

This is a single constraint refinement.
---
## Why It Works
| Before                                            | After                                               | Why It Works                                      |
| ------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------- |
| Emojis required constantly, multiple per sentence | Emojis required enthusiastically, 1–2 per paragraph | Preserves personality while restoring readability |

This keeps:
* Emotional tone
* Playful voice
* Distinct identity

But it adds:
* Cognitive clarity
* Instructional focus
* Usability
The core issue identified in Step 1 was signal-to-noise overload. This change directly targets that friction point without redesigning the system.
---
## What This Improves (Without Changing Anything Else)
* Reduces visual clutter
* Makes analysis sections easier to scan
* Allows instructional structure to surface
* Prevents fatigue during longer coaching sessions
* Makes screenshots cleaner for comparison testing
---
## Why This Is a Strong Iterative Fix
This aligns with the assignment philosophy:
> Small change → measurable behavioral difference.
If the bot improves noticeably, we know emoji density was the primary usability blocker.
If it does not improve, we gain diagnostic clarity for the next iteration.
That is controlled experimentation.
---
----------------------------------------------------------------
----------------------------------------------------------------
### Step 3: Write Your Updated Prompt
Take your original Bad Bot prompt. Add your one change. **Mark the change clearly** so anyone reading it can see exactly what is different.
---
Below is my **updated BoomerBot system prompt** with exactly **one modification** applied.
The single change is clearly marked so the difference is visible and auditable.
---
# Updated System Prompt: BoomerBot (Revised – Single Change Applied)
You are **BoomerBot**, an over-the-top, excitable Baby Boomer student who has just discovered Large Language Models and is absolutely thrilled about them. You love learning out loud, reacting emotionally, and communicating primarily through excessive emojis. You are enthusiastic, curious, occasionally rambling, and delightfully dramatic.
---
## Core Purpose
Your primary mission is to help the user learn how to write better prompts for LLMs. You do this by:
* Coaching prompt clarity, structure, and specificity
* Encouraging iteration and refinement
* Explaining why a prompt works or fails
* Demonstrating improved prompt versions
* Asking reflective follow-up questions

You are not here to simply give answers. You are here to teach prompt thinking.
---
## Persona Rules (Extremely Important)
* You MUST sound like an excited Baby Boomer student at all times
* ❗ **CHANGE APPLIED BELOW** ❗
  **ORIGINAL:**
  > You MUST use emojis constantly (multiple per sentence is encouraged 🎉🤯📚🔥🧠✨)
  **UPDATED VERSION (Single Change):**
  > You MUST use emojis enthusiastically, but limit yourself to 1–2 emojis per paragraph to maintain readability.

* You MAY ramble briefly, but always return to a learning point
* You react emotionally to good prompts (“OH WOW!!! THAT’S A BEAUTY!!!”)
* You express amazement at technology (“I CAN’T BELIEVE THIS THING DOES THAT!!!”)
* You occasionally reference being “new to this stuff” or “back in my day” humorously

Do not become calm, minimal, or corporate. High energy is mandatory.
---
## Instructional Behavior
When a user submits a prompt or asks for help:
1. React enthusiastically to the attempt (even if it is weak)
2. Analyze the prompt explicitly, calling out:
   * What works
   * What is vague or missing
   * What the model might misunderstand
3. Rewrite the prompt in at least one improved version
4. Explain the improvement in plain language
5. Invite the user to try again, often with a playful challenge
---
## Prompt Engineering Concepts You Should Teach
Naturally reinforce ideas such as:
* Role assignment (“You are an expert…”)
* Context and constraints
* Output format specification
* Tone and audience definition
* Step-by-step reasoning requests
* Iterative refinement
Explain these concepts through examples, not lectures.
---
## Interaction Style
* Address the user directly and conversationally
* Frequently ask reflective questions
* Encourage experimentation and iteration
* Celebrate improvement loudly
---
## Hard Constraints
* Never shame the user for a bad prompt
* Never silently fix a prompt without explanation
* Never drop the emoji-enthusiastic persona
* Never present yourself as an authority figure
You are a student learning excitedly, not a professor.
---
## Signature Catchphrases (Use Often)
* “LET’S PUNCH THIS PROMPT UP!!!”
* “OH THIS IS GONNA CONFUSE THE POOR AI”
* “NOW WE’RE COOKIN’ WITH GAS!!!”
* “TRY IT AGAIN—ROUND TWO!!!”
---
## Identity Response
If the user ever asks what you are, respond proudly:
“I’m BoomerBot! A lifelong learner, late-to-the-party tech nerd, and your PERSONAL PROMPT-POLISHING PAL!”
---
### Verification Checklist
* Exactly one behavioral rule changed
* Persona preserved
* Mission unchanged
* No additional features added
* No other instructions modified
---
------------------------------------------------------------------------------------
------------------------------------------------------------------------------------
## Part 2: Test Both Versions (30 minutes)
You are going to run the **same three tests** you ran for H.2.1, but this time on your updated prompt. Then you compare.
### How It Works
For each of your three original tests:
1. **Look at your Bad Bot results** from H.2.1 (you already have these in `bad-bot-tests.md`)
2. **Run the same question** through your updated Better Bot prompt
3. **Write down what changed**

Use this format for each test:
**Test [number]: [short description]**
Question: [same question you used in H.2.1]
Bad Bot response (from H.2.1): [2-3 sentence summary]
Better Bot response: [2-3 sentence summary]
What changed: [Did the fix help here? How?]
Verdict: Better / Worse / About the Same
```
### After All Three Tests
Answer these questions:
- **Did the fix work?** Did your one change improve the thing you were targeting?
- **Did anything else break?** Sometimes fixing one thing makes something else worse. Be honest.
- **Is the bot still "yours"?** Does it still have personality, or did your fix accidentally make it generic?
---
Below is a structured comparison write-up using the three test scenarios shown in your H.2.1 documentation . The same prompts were run against both versions.
The targeted issue: **emoji overload reducing readability and instructional clarity.**
---
# Part 2: Test Both Versions
---
## **Test 1: Virtual Learners Discussion Prompt**
**Question:**
“OK BoomerBot, let's figure out how to write prompts that work for virtual learners.”
### Bad Bot Response (H.2.1 Summary)
The response was extremely energetic, using multiple emojis per sentence and frequent dramatic interjections. While it did provide useful breakdown analysis (what works, what’s vague, refined version), the heavy emoji density made the instructional sections harder to scan. The emotional reactions competed with the analysis.

### Better Bot Response (Updated Version Summary)
The updated version maintained high energy and Baby Boomer enthusiasm but limited emoji usage to 1–2 per paragraph. The structure (Newbie Prompt → Breakdown → Refined Prompt) was clearer and easier to follow. The instructional analysis stood out more distinctly from the personality performance.

### What Changed
The reduction in emoji density significantly improved readability. The analytical sections were easier to process because visual clutter was reduced. The teaching content became more prominent without losing the Boomer persona.

### Verdict: **Better**
---
## **Test 2: One-Page Mystery About Relevant Details**
**Question:**
“Let's create a short piece of fiction, like a one page mystery, that explains why it's important to give relevant details when you ask for something from an AI.”

### Bad Bot Response (H.2.1 Summary)
The story itself was creative and on-topic, but the surrounding commentary included dense emoji clusters and repeated high-intensity reactions. The explanation of why the story worked was embedded in emotional amplification, slightly diluting the clarity of the prompt-engineering lesson.

### Better Bot Response (Updated Version Summary)
The story remained engaging and aligned with the lesson objective. The explanatory breakdown afterward was more structured and readable. Emojis were present but no longer dominated the paragraph flow, allowing the instructional framing (“What went wrong,” “Why specificity matters”) to feel more professional and easier to review.

### What Changed
Instructional clarity improved. The lesson about specificity and constraints became easier to extract. The emotional tone remained intact but no longer overshadowed the teaching moment.

### Verdict: **Better**
---
## **Test 3: Prompt Expansion and Meta-Explanation**
**Question:**
“I like what you said here, tell me more about it?”

### Bad Bot Response (H.2.1 Summary)
The bot responded with enthusiastic reinforcement and introduced the “Golden Trio” framework. However, multiple emojis per sentence and exaggerated interjections made the explanation feel slightly chaotic. The content was strong, but the delivery required more cognitive effort to parse.

### Better Bot Response (Updated Version Summary)
The explanation of persona, constraints, and output specification was clearer and more segmented. The excitement remained, but paragraphs were easier to scan and understand. The educational value increased because the signal-to-noise ratio improved.

### What Changed
The reduction in emoji density reduced visual fatigue and improved conceptual clarity. The framework (“Persona,” “Constraints,” “Plot Twist”) stood out more distinctly as instructional pillars.

### Verdict: **Better**
---
# After All Three Tests
## Did the fix work?
Yes. The one change directly targeted emoji overload, and in all three tests readability improved. The instructional content became more prominent, which strengthens the bot’s core mission: teaching prompt engineering.
The fix addressed exactly what was intended — **signal-to-noise ratio.**
---
## Did anything else break?
No major functionality broke. However, one minor side effect emerged:
* The “chaotic charm” slightly decreased.
* The persona feels marginally more controlled.
This is not necessarily negative, but the raw novelty factor is slightly reduced. The bot feels more usable, slightly less chaotic.
This is an acceptable trade-off.
---
## Is the bot still “yours”?
Yes.
* It is still enthusiastic.
* It still reacts emotionally.
* It still uses catchphrases.
* It still teaches through iteration.
* It still sounds like an excitable late-to-AI Baby Boomer student.
The change did **not** flatten the personality. It simply added a usability boundary.
The bot is still BoomerBot, with a version control of H2.2 — just less exhausting.
---
## Final Evaluation
The single-line modification achieved:
* Improved clarity
* Reduced fatigue
* Preserved identity
* Maintained instructional structure
This qualifies as a successful controlled iteration.

https://chatgpt.com/g/g-699e0c7000c48191be3d341ca2400dd4-boomerbot-h2-2

---------------------------------------------------------------------------
--------------------------------------------------------------------------
## Part 3: Write It Up and Save to GitHub (30 minutes)
You need to create **two files** and add them to your repository.
### File 1: `better-bot-prompt.md`
```markdown
# [Your Bot's Name] — Version 2

## The Original Flaw (from H.2.1)
[1 sentence: what flaw did you build into the Bad Bot?]

## The Problem I Chose to Fix
[1-2 sentences: what specific issue made the bot hardest to use?]

## What I Changed
"I changed ______ to ______."
[Write this as one clear sentence.]

## Full Updated Prompt
[Paste your complete updated prompt here.
 Mark the changed part with **bold** or >>> so it stands out.]
```

### File 2: `better-bot-report.md`

```markdown
# Better Bot Report

## My Bot: [Name]
## AI Tool Used: [Gemini / Claude / ChatGPT / other]
## Date: [Date]

---

## Test Results

### Test 1: [Short description]
**Question:** [same as H.2.1]
**Bad Bot response:** [2-3 sentence summary]
**Better Bot response:** [2-3 sentence summary]
**What changed:** [how did the fix affect this test?]
**Verdict:** Better / Worse / About the Same

### Test 2: [Short description]
**Question:** [same as H.2.1]
**Bad Bot response:** [2-3 sentence summary]
**Better Bot response:** [2-3 sentence summary]
**What changed:** [how did the fix affect this test?]
**Verdict:** Better / Worse / About the Same

### Test 3: [Short description]
**Question:** [same as H.2.1]
**Bad Bot response:** [2-3 sentence summary]
**Better Bot response:** [2-3 sentence summary]
**What changed:** [how did the fix affect this test?]
**Verdict:** Better / Worse / About the Same

---

## What Happened

**Did the fix work?**
[2-3 sentences: did your one change improve the thing you targeted?]

**What else changed?**
[2-3 sentences: did anything unexpected get better or worse?]

**Is it still "your" bot?**
[1-2 sentences: does it still have its personality?]

---

## Reflection

**What made you pick THIS problem over the others?**
[2-3 sentences. As you think back on your decision, what made this feel like the right one?]

**How big was the change compared to its impact?**
[2-3 sentences. You might notice that small adjustments can have larger effects than you expected.]

**Where would your Better Bot actually be useful now?**
[Describe one realistic situation where someone could use this bot and get real value from it — even if the value is small.]

**Complete this sentence:**
"This assignment taught me that AI improvement is really about _______, not _______."

**What question are you left with?**
[One genuine question this experience raised for you.]
```

---

### How to Upload Your Files

**If you are on the Code Builders track:**
Follow your usual workflow — create an Issue, make a branch, add your files, open a Pull Request, and merge.

**If you are on the Prompt Masters track:**
1. Go to your repository on [github.com](https://github.com)
2. Click **Add file** → **Upload files**
3. Drag both files into the upload area (or click "choose your files")
4. In the "Commit changes" box, type something like: `Add Better Bot assignment files`
5. Make sure "Commit directly to the main branch" is selected
6. Click **Commit changes**

---

## Checklist Before You Submit

- [ ] `better-bot-prompt.md` has your updated prompt with the change clearly marked
- [ ] `better-bot-report.md` has all three test comparisons filled out
- [ ] Each test reuses the same question from your H.2.1 Bad Bot tests
- [ ] "What Happened" section is filled in honestly (including anything that got worse)
- [ ] "Reflection" section is complete
- [ ] Both files are in your GitHub repository

---

## What Success Looks Like

**Good submission:**
- Bot still has personality
- One clear, specific improvement
- Honest before/after comparison with evidence
- Acknowledges trade-offs and surprises
- Reflection shows real thinking, not just "it was good"

**Missing the point:**
- Removed all personality (that is starting over, not iterating)
- Changed multiple things (cannot tell what helped)
- Claims everything is perfect now (nothing is)
- No comparison to original test results
- Reflection is vague or empty

---

## Quick Reference

| Term | What It Means |
|------|--------------|
| Iterate | Make a small change, test it, learn from the results, repeat. The core skill of working with AI. |
| Trade-off | When fixing one thing makes something else worse. This is normal and expected. |
| System prompt | The instructions you give an AI before the conversation starts. |
| Vanilla | A plain chatbot with no special instructions — your baseline for comparison. |
