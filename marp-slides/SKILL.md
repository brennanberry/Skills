# Marp Slides: Markdown Presentations

Convert Markdown into professional presentation slides for LP quarterly updates, IC acquisition presentations, and fundraising decks. Exports to PDF, PPTX, and HTML via Marp CLI.

## Installation
```bash
npm install -g @marp-team/marp-cli
# or use without install:
npx @marp-team/marp-cli
```

## Export Commands
```bash
# PDF
npx @marp-team/marp-cli deck.md --pdf

# PowerPoint
npx @marp-team/marp-cli deck.md --pptx

# HTML
npx @marp-team/marp-cli deck.md --html
```

## Slide Syntax
```markdown
---
marp: true
theme: default
paginate: true
---

# Slide Title
Content here

---

# Next Slide
<!-- Speaker notes go here (not shown in presentation) -->

---

<!-- Two-column layout -->
<div class="columns">
<div>Left column</div>
<div>Right column</div>
</div>
```

## Recommended Slide Counts
- LP quarterly update: 8–12 slides
- Fundraising deck: 15–20 slides
- IC acquisition presentation: 10–15 slides

## Standards
- One key message per slide — no walls of text
- Every number must match the LP report and financial model
- All data sourced and dated
- Themes: `default`, `gaia`, `uncover` (or custom CSS)
