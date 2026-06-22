# PROMPTS.md

## AI Use Log

| Date | What I asked | What AI suggested | What I changed | What I learned |
|---|---|---|---|---|
| Week 1 | Explain my HTML line by line | AI explained h1, p, a, section | I changed my heading and intro | h1 is the main heading |

## Reflection notes

- One part of the code I understand:
- One part that still feels unclear:
- One thing I changed myself:



## Prompt 1 — Default Week 1 Prompt

```text
I am a beginner. Explain this code first. Then suggest one small change. Do not rewrite everything.
```

---

## Prompt 2 — Customize My Page

```text
I am making a simple About Me webpage.

Here is my HTML:

[paste your HTML here]

Help me customize it for myself.

Please suggest:
1. One change to the heading.
2. One change to the introduction paragraph.
3. One new section I could add.

Keep the suggestions simple and explain what each change does.
```

---

## Prompt 3 — Add a New Section

```text
I want to add a new section to my About Me webpage.

The section should be called "My project idea".

Please show me only the HTML for this new section.

Constraints:
- Keep it beginner-friendly.
- Use the same style pattern as my existing card section.
- Explain where I should paste it.
```

---

## Prompt 4 — Improve My Link Button

```text
I have a link button in my webpage.

Here is the code:

[paste the link code here]

Please explain:
1. What the href does.
2. What target="_blank" does.
3. How I can change the button text.
4. How I can safely use a placeholder link if I do not have my real link yet.
```

---

## Prompt 5 — Help Me Understand CSS

```text
I am a beginner learning CSS.

Here is my style.css:

[paste CSS here]

Please explain:
1. What each selector controls.
2. Which line controls the background color.
3. Which line controls the heading color.
4. One small style change I can safely try.
```

---

# Debugging Prompts

Use these when something breaks.

---

## Prompt 6 — General Debugging Prompt

```text
I am a beginner and my webpage is not working as expected.

Here is what I expected:
[describe expected result]

Here is what actually happened:
[describe actual result or paste error message]

Here is the code I changed last:
[paste code]

Please explain the likely cause first.
Then give me 3 small things to check.
Do not rewrite the whole project.
```

---

## Prompt 7 — CSS Is Not Showing

```text
My HTML page opens, but the CSS style is not showing.

Here is the line in my HTML that connects the CSS file:

[paste link tag]

Here are my file names:
[paste file names]

Please help me debug this.

Explain:
1. Whether the CSS file name matches.
2. Whether the href path looks correct.
3. What I should check in the browser.
4. The smallest fix to try first.
```

---

## Prompt 8 — My Link Does Not Work

```text
My link does not work the way I expected.

Here is my link code:

[paste link code]

Please explain:
1. What URL this link goes to.
2. Whether the href is valid.
3. Whether target="_blank" is used correctly.
4. How to test the link safely.
```

---

## Prompt 9 — I Changed Something But Nothing Happened

```text
I changed my HTML or CSS file, but the browser did not change.

Please help me debug.

Here is what I changed:
[paste change]

Here is what I expected:
[describe expected result]

Here is what happened:
[describe actual result]

Give me a beginner-friendly checklist. Include saving the file, refreshing the browser, checking the file name, and checking whether I edited the correct file.
```

---

# Safe CLI Agent Prompts

Use these only if you are using Codex, Claude Code, Antigravity CLI, or another terminal/project-level coding agent.

---

## Prompt 10 — Safe Start for CLI Agent

```text
We are working in one beginner class project folder.

Rules:
- Stay inside this folder.
- Do not access private files outside this folder.
- Do not install packages unless I approve.
- Do not use frameworks.
- Do not use API keys or secrets.
- Do not edit files until you explain your plan.

First, inspect the files and explain what you see.
```

---

## Prompt 11 — Ask for a Plan Before File Changes

```text
Before editing any files, propose a plan.

The plan should include:
1. Which files you want to edit.
2. What changes you want to make.
3. Why each change helps the beginner learning goal.
4. How we will test the result.

Do not edit yet.
```

---

## Prompt 12 — Small Approved Edit

```text
I approve only this small change:

[describe the approved change]

Please edit only the necessary file or files.

After editing:
1. Summarize exactly what changed.
2. Tell me how to test it.
3. Do not make extra improvements unless I ask.
```

---

## Prompt 13 — Review the Diff

```text
Please summarize the file changes like a code review.

Use this format:
1. File changed
2. Lines or sections changed
3. Why the change was made
4. What I should test
5. Anything risky or unclear
```

---

# PROMPTS.md Template

Students can copy this into their project.

```markdown
# PROMPTS.md

## Project
Week 1 First Build — About Me Page

## AI Use Log

### Entry 1
**What I asked:**  
[Write your prompt or summarize it]

**What AI suggested:**  
[Summarize the useful suggestion]

**What I changed:**  
[Explain what you actually changed in your file]

**How I tested it:**  
[Explain how you checked it in the browser]

**What I learned:**  
[Write one thing you understand better now]

---

### Entry 2
**What I asked:**  
[Write your prompt or summarize it]

**What AI suggested:**  
[Summarize the useful suggestion]

**What I changed:**  
[Explain what you actually changed in your file]

**How I tested it:**  
[Explain how you checked it in the browser]

**What I learned:**  
[Write one thing you understand better now]
```

---

# Week 1 Reflection Prompts

Students can use these for the short reflection.

```text
Write a short reflection of about 300 words.

Please answer:
1. What did you build?
2. What did AI help you with?
3. What part of the code can you explain now?
4. What did you test?
5. What is still unclear or confusing?
6. What do you want to improve next week?
```
