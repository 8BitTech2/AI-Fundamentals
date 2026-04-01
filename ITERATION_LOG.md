# ITERATION_LOG.md

## Baseline
Chosen starting point: `prototype-v1-ChatGPT.html`

## Iteration 1
**Problem**: The analyzer was too generous in a few categories. Role Assignment could be triggered by broad phrases, Output Format could over-score prompts when words like “list” appeared casually, and the “What works” section included moderate items that were not really strengths.

**Prompt**: Improve the rule-based scoring so it relies on more explicit signals for role assignment and output formatting. Also make the strengths section show only true strengths rated Strong.

**Result**: I updated the detection logic to use stricter patterns such as “You are a…”, “Act as a…”, “Format the response…”, and “Present the response in…”. I also changed the summary logic so only Strong categories appear in “What works.” This reduced false positives and made the feedback more honest.

**Status**: ✅ Fixed

Saved as: `v2.html`

## Iteration 2
**Problem**: The improved prompt generator worked, but the rewritten output still felt generic. It added helpful language, but it did not clearly structure the revised prompt into role, context, constraints, and format sections.

**Prompt**: Rewrite the improved prompt generator so it builds a more structured prompt. Keep the original request, but add labeled sections for missing role, context, constraints, output format, and task clarity.

**Result**: The improved prompt generator now creates a cleaner, more reusable revision that preserves the original request and adds labeled guidance only where needed. The output is easier for students to understand and easier to copy into another AI tool.

**Status**: ✅ Fixed

Saved as: `v3.html`

## Iteration 3
**Problem**: After improving the generated prompt, there was no quick way for a user to reuse it. That added friction during testing and made the app feel less complete.

**Prompt**: Add a simple “Copy Improved Prompt” button using plain JavaScript. Show a short status message after copy succeeds or fails.

**Result**: I added a copy button beneath the improved prompt area along with user feedback text. This made the refined version more practical without adding external dependencies or backend logic.

**Status**: ✅ Fixed

Saved as: `v3.html`

## Final Choice
Final working version: `v3.html`

## Notes
The final version keeps the original MVP scope intact:
- Single HTML file
- Embedded CSS and JavaScript
- No external libraries
- Rule-based prompt analysis
- Structured results
- Improved prompt generation

The biggest gains came from tightening the scoring logic and making the improved prompt output more actionable.
