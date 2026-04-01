# AI Prompt Quality Analyzer MVP

## What It Does
The AI Prompt Quality Analyzer is a browser-based tool that evaluates the quality of a user-written prompt using simple rule-based logic. It gives structured feedback across five prompt engineering categories, explains what is working, identifies weak areas, and generates an improved prompt that can be reused in another AI system.

This project was built as a single-file MVP for students and beginner AI users who want practical feedback without needing an API or backend.

## How to Use
1. Open `v4-portfolio.html` in a web browser.
2. Type or paste a prompt into the text area.
3. Click **Analyze Prompt**.
4. Review the overall score and category-by-category results.
5. Read the strengths, weaknesses, and suggestions.
6. Copy the improved prompt and test it in another AI tool.

## Features Implemented
- Single-page web app with embedded HTML, CSS, and JavaScript
- Five-category prompt analysis:
  - Clarity
  - Specificity
  - Role Assignment
  - Constraints
  - Output Format
- Overall prompt score out of 100
- Structured feedback sections:
  - What works
  - What is missing or weak
  - Suggestions for improvement
- Improved prompt generator
- Sample prompt buttons for easy testing
- Character counter
- Copy-to-clipboard button for the improved prompt
- Graceful error handling for empty and very short input
- Responsive layout for desktop and mobile use

## Try It Yourself
Add your GitHub Pages URL here after deployment.

Example:
`https://yourusername.github.io/ai-prompt-quality-analyzer/`

## Browser Testing
This project should be tested in at least two browsers before submission.

Recommended:
- Google Chrome
- Microsoft Edge or Mozilla Firefox

Testing checklist:
- Page loads correctly
- Analyze button works
- Results appear after analysis
- Copy button works
- Empty input is handled gracefully
- Layout remains readable on smaller screens

## What I Learned
This project showed how important it is to evaluate AI-generated code instead of assuming it is correct on the first attempt. Comparing multiple prototype versions made it clear that different tools can satisfy the same requirements in very different ways. Iteration improved both code quality and user experience.

I also learned that prompt engineering concepts can be translated into front-end logic through rule-based checks. Even though this MVP does not use an AI API, it still demonstrates how software can guide users toward stronger prompt design through structured feedback.

## Future Improvements
- Add weighted scoring by category
- Add real-time analysis while typing
- Replace rule-based logic with an actual AI API
- Save prompt history for comparison
- Export results as Markdown or PDF
- Add more tailored prompt templates for education, business, and coding use cases
- Improve natural language detection beyond keyword matching
