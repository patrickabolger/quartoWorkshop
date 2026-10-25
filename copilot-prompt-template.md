# Microsoft Copilot prompt template for a minimal Quarto document

Replace the text in square brackets.

```text
Create a minimal Quarto document for [AUDIENCE] about [TOPIC].
It will be edited and rendered in RStudio.

Output format: [html / docx / pdf / revealjs].
Include: [TITLE], [2–3 SECTIONS], and one short R code block that
uses [BUILT-IN DATA / CODE I PROVIDE].

Requirements:
- Return the complete contents of one .qmd file.
- Put the entire file in one fenced code block.
- Include a valid YAML header.
- Use simple Markdown.
- Use only packages and data named in this prompt.
- Do not invent results or references.
- Keep it short enough to inspect line by line.
- After the code block, give a three-item render checklist.
```

## If it does not render

```text
This Quarto document fails to render. Explain the first error in plain
English, then return the smallest corrected version. Do not add new
packages or features.

[PASTE ERROR]

[PASTE .QMD]
```
