---
name: portfolio-polish
description: Improve a beginner portfolio webpage for AIM 5012 by making targeted, beginner-friendly edits to HTML and CSS. Use when the student wants to improve structure, content clarity, visual consistency, or accessibility — not just get feedback.
---

# Portfolio Polish

## Goal
Improve the portfolio webpage by making small, explainable edits to `index.html` and `style.css`. Every change must be understandable to a beginner and easy to verify in the browser.

## Inputs
- `index.html`
- `style.css`
- `PROMPTS.md` (read only — do not edit)
- `README.md` (read only — do not edit)

## Steps
1. Inspect `index.html` and `style.css` before making any changes.
2. Explain a short plan: which files you will edit, what you will change, and why each change helps.
3. Wait for my approval before editing.
4. Make only the approved changes. Edit one file at a time.
5. Check for and fix the following if present:
   - Heading hierarchy (h1 → h2 → h3 used in correct order)
   - Missing or weak `aria-label` attributes on buttons and links
   - Section descriptions that are too vague — make them more specific
   - Inconsistent spacing between sections
   - Button or link text that does not describe where it goes
   - Any text that overflows or wraps awkwardly on narrow screens
6. After editing, summarize exactly what changed in plain language.
7. For each change, state one browser check I can do to verify it.

## Output
- Updated `index.html` and/or `style.css`
- A plain-language summary listing every change made
- One verification step per change (e.g. "Open the page and confirm the Projects heading appears below About")

## Boundaries
- Only edit `index.html` and `style.css`
- Do not change my personal content — name, bio, project titles, or descriptions
- Do not use React, Tailwind, Bootstrap, or JavaScript
- Do not rewrite the entire file — make targeted edits only
- Do not install dependencies
- Do not commit changes unless the student explicitly asks
- Do not read, print, or store API keys, passwords, or personal data
