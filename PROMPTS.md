# PROMPTS.md

## AI Use Log

| Date | Tool | What I asked | What AI suggested | What I accepted | How I tested |
|---|---|---|---|---|---|
| Week 1 / VS Code | Claude Code | Explain my HTML line by line | AI explained h1, p, a, section | Reviewed explanation, no file changes | Opened index.html in browser |
| Week 1 / VS Code | Claude Code | Update heading, intro, add headshot, projects, contact, footer, and My Project Idea section | Full plan for index.html and style.css changes | Approved plan first, then accepted all changes after review | Opened local page with `open index.html`, refreshed browser, confirmed all sections visible |
| Week 1 / VS Code | Claude Code | Style hero as flex layout with headshot on right, add responsive grid, idea box styling | CSS updates for `.hero`, `.headshot`, `.projects-grid`, `.idea-box`, buttons, and cards | Accepted full style.css update | Checked headshot position, card layout, and button spacing in browser |
| June 22, 2026 / Perplexity | Perplexity Computer | Add nav bar with About/Projects/Contact links, add section IDs, add workflow strip, fix GitHub link | Added `<nav>` element, `id` attributes on sections, four-step workflow strip, corrected GitHub href | Reviewed plan before approving, accepted all index.html changes | Verified on GitHub repo that commit was pushed correctly |
| June 22, 2026 / Perplexity | Perplexity Computer | Style nav bar as colored horizontal bar, make workflow strip horizontal | Updated style.css: full-width sticky purple nav bar, horizontal four-panel workflow strip with mobile responsive fallback | Accepted all CSS changes to style.css | Confirmed commit pushed to GitHub |

---

## Full Project Edit Summary

### VS Code Session (Week 1)

**What was changed:**
- Updated `index.html`:
  - Changed the main heading to "Hi! I'm Laura"
  - Replaced the intro paragraph with full MBA / Quantitative Finance / AI Strategy / public health policy description
  - Added headshot image reference `IMG_4038.jpg` on the right side of the hero section
  - Added "My Current Projects" section with two cards: Quantitative Finance and AI Strategy and Governance
  - Added contact section with LinkedIn, Email, and GitHub buttons
  - Added centered footer: © 2026 Laura Ibragimova · Built with AI · AIM 5012
  - Added "My Project Idea" section with heading outside the box and AI Policy Tracking Tool description inside

- Updated `style.css`:
  - Turned `.hero` into a flex layout so the headshot sits on the right
  - Added `.headshot` cropping with `object-position: center top`
  - Added responsive styling so `.projects-grid` stacks to one column on narrow screens
  - Added styles for the new `.idea-box` section
  - Updated button and card spacing for consistent layout

**What I asked to approve before editing:**
- The exact plan to update index.html and style.css
- That the hero section should include my new copy and headshot
- That the "My Project Idea" title should sit outside the colored box
- That the idea box should contain only the AI Policy Tracking Tool heading and one descriptive paragraph
- AI waited for my approval before making any edits

**What AI helped with:**
- Structuring page changes into safe, beginner-friendly HTML edits
- Translating the requested layout into actual index.html markup
- Writing CSS for the hero layout, project cards, footer, and responsive behavior
- Advising the GitHub Pages deployment workflow

**What I accepted:**
- Full set of page updates described above
- GitHub Pages deployment approach using option B
- Final descriptive paragraph for the AI Policy Tracking Tool
- New footer and responsive layout

**How it was verified:**
- Opened local page in browser using `open index.html`
- Refreshed browser after each edit
- Checked contact buttons, header text, and new sections were present
- Verified GitHub Pages URL was not yet live, confirming repo was public but needed Pages activation

---

### Perplexity Computer Session (June 22, 2026)

**What was changed:**
- Updated `index.html`:
  - Added sticky `<nav>` bar at top with name on left and About / Projects / Contact links on right
  - Added `id="about"` to hero section, `id="projects"` to projects section, `id="contact"` to contact section
  - Added four-step workflow strip (Inspect → Plan → Test → Log) between hero and projects sections
  - Fixed GitHub button link from generic `https://github.com/` to `https://github.com/LauraIbragimova`

- Updated `style.css`:
  - Styled `.site-nav` as a full-width sticky purple bar (`#6c4ef6`) with white text
  - Styled `.workflow-strip` as a horizontal four-panel row with purple labels and muted descriptions
  - Added responsive mobile fallback: nav stacks vertically, workflow strip goes single column on screens under 768px

**What I asked to approve before editing:**
- AI presented the full plan with all five changes listed before touching any file
- I reviewed and approved the plan before any edits were made

**What AI helped with:**
- Writing the `<nav>` HTML element and anchor link structure
- Applying sticky positioning and color styling to the nav bar in CSS
- Designing the horizontal workflow strip layout using flexbox

**What I accepted:**
- All index.html and style.css changes as described above

**How it was verified:**
- Confirmed commits were pushed successfully to GitHub repo
- Repo visible at github.com/LauraIbragimova/project1-portfolio-polish

---

## Reflection Notes

- One part of the code I understand: The `<nav>` element and anchor links (`href="#about"`) — clicking a nav link jumps to the matching `id` on the page
- One part that still feels unclear: How CSS media queries decide when to switch from desktop to mobile layout
- One thing I changed myself: Reviewed and approved each plan before it was committed — nothing was edited without my go-ahead

---

## Reusable Prompts

### Prompt 1 — Default Beginner Prompt
```text
I am a beginner. Explain this code first. Then suggest one small change. Do not rewrite everything.
```

### Prompt 2 — Customize My Page
```text
I am making a simple About Me webpage. Help me customize it for myself.
Please suggest:
1. One change to the heading.
2. One change to the introduction paragraph.
3. One new section I could add.
Keep the suggestions simple and explain what each change does.
```

### Prompt 3 — Ask for a Plan Before File Changes
```text
Before editing any files, propose a plan. Include:
1. Which files you want to edit.
2. What changes you want to make.
3. Why each change helps the beginner learning goal.
4. How we will test the result.
Do not edit yet.
```

### Prompt 4 — Small Approved Edit
```text
I approve only this small change: [describe the approved change]
Please edit only the necessary file or files.
After editing:
1. Summarize exactly what changed.
2. Tell me how to test it.
3. Do not make extra improvements unless I ask.
```

### Prompt 5 — General Debugging
```text
I am a beginner and my webpage is not working as expected.
Here is what I expected: [describe expected result]
Here is what actually happened: [describe actual result]
Here is the code I changed last: [paste code]
Please explain the likely cause first. Then give me 3 small things to check.
Do not rewrite the whole project.
```

---

## Week 2 AI Use Log

**What AI helped with:**
- Inspected the professor's starter `index.html` and `style.css` before making any changes
- Proposed a beginner-friendly plan for each edit before touching files
- Added nav bar, section IDs, project cards, contact buttons, headshot image, and footer to `index.html`
- Wrote CSS for the horizontal nav, two-column project grid, headshot layout, and responsive stacking
- Set up the `week2` branch and copied files for GitHub Pages deployment

**What I accepted:**
- All five planned changes to `index.html` and `style.css` after reviewing the plan first
- Contact section replaced with three linked buttons (Email, LinkedIn, GitHub)
- Headshot added to hero with descriptive alt text
- Responsive CSS so the layout stacks cleanly on narrow screens

**What I reviewed:**
- Each plan was presented in the chat before any file was edited
- Confirmed every commit in the GitHub repo after it was pushed
- Verified file structure in `week2-original/` and `week2` branch

**How I verified:**
- Downloaded files locally and opened `index.html` in the browser
- Clicked each nav link to confirm it jumps to the correct section
- Clicked each contact button to confirm it links to the right place
- Confirmed GitHub Pages branch (`week2`) has `index.html`, `style.css`, and `IMG_4038.jpg`
