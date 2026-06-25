---
name: portfolio-visual-identity
description: Guide AI to apply The Policy Nest visual identity to a beginner portfolio webpage grounded in the student's real background in healthcare policy and AI governance. Use when the student wants a redesigned version that looks intentional and personal — not a generic student template.
---

# Portfolio Visual Identity

Approach this as a designer who has read Laura's bio and studied The Policy Nest brand board. Every visual choice should feel like it came from that world: structured, credible, and intelligence-forward — like a well-designed policy brief, not a startup landing page.

## Ground it in the subject

Before touching any code, read the page content. Laura's background is in healthcare policy and AI governance. Her brand — The Policy Nest — translates dense CMS regulations into structured, actionable plans for ACO leaders and health systems. The visual identity should reflect that: authoritative, organized, and quietly distinctive.

State your design direction in one sentence before writing any code. Example: "This page will use The Policy Nest brand palette — Aubergine headers, Bone background, Clay CTAs — with Bricolage Grotesque headings and Source Sans Pro body text."

## Design Principles

**Color:** Use The Policy Nest brand palette exactly as specified:
- Aubergine `#4a2e4f` — headers, nav background, section headings
- Azure `#1f4e79` — secondary headers, card borders, link color
- Clay `#C96A4A` — buttons, accent lines, highlights (10–15% use only)
- Sage `#8FA88F` — dividers, secondary accents, icon details
- Bone `#F3EEE6` — page background, document-style body areas

Do not use generic blues or grays that are not from this palette.

**Typography:** Use The Policy Nest brand fonts loaded from Google Fonts:
- `Bricolage Grotesque` — h1 and h2 headings, bold weight
- `Source Sans Pro` — body text, nav links, card descriptions, regular weight

Set a clear size hierarchy: h1 large and bold, h2 medium, body text comfortable at 16–17px. Font weight contrast carries the personality — do not add extra font families.

**Layout:** Keep the existing section structure — hero, learning goals, projects, contact, footer. Do not add or remove sections. Add generous padding between sections so the page breathes like a well-laid-out document.

**Signature element:** Apply a 4px left border in Clay `#C96A4A` to each project card. This echoes the visual language of policy documents and annotation systems — structured, purposeful, unmistakably intentional. Apply it only to project cards, nowhere else.

**Restraint:** One bold choice — the Clay left border on cards. Keep everything else clean and disciplined. Remove any decoration that does not serve the content.

## Process

1. Read `index.html` and `style.css` fully before proposing anything
2. Write a short design plan in the chat confirming:
   - Which brand colors map to which elements
   - Font loading method (Google Fonts `<link>` in `<head>`)
   - Confirmation of the Clay left-border signature element
3. Wait for student approval before editing any file
4. Edit only `index.html` and `style.css`
5. Do not change personal content — name, bio, project titles, contact links
6. After editing, list every change made and one browser check per change

## Boundaries

- Only edit `index.html` and `style.css`
- Do not use React, Tailwind, Bootstrap, or JavaScript
- Do not rewrite the entire file — make targeted, explainable edits
- Do not install dependencies
- Colors must come from The Policy Nest brand palette above — no substitutions
- This version must look visually distinct from the week2-original starter
- Do not commit changes unless the student explicitly approves
