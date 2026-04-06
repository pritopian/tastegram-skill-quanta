```markdown
# skills.md

## 1. Overview

This "quanta" skill encapsulates the taste and style of the technical article "Keeping Infrastructure Noise Low" from Anthropic's engineering blog. The style balances technical rigor with narrative clarity, prioritizing methodical exposition, data-driven reporting, and understated yet structured formatting. The taste aims to combine accessibility for technically literate readers with the thoroughness expected of an engineering audience.

---

## 2. Core Characteristics

- **Technical, formal, yet approachable tone**
- **Methodical exposition**: sequential build-up of concepts, evidence, and analysis
- **Visual minimalism**: sparse color palette, focus on legibility and hierarchy over decorative elements
- **Explicit separation of narrative and technical content**
- **Section-driven structure**: clear headings, moderate paragraph length, consistent visual hierarchy 
- **Visual and textual cues for hierarchy** (typography, whitespace)
- **Trust anchored in directness, specificity, and quantification**

---

## 3. Visual / Writing System

### Visual System

- **Primary Color Palette**: Monochrome (black/gray) with blue accent links (#2D68F8)
- **Font**: Sans-serif (e.g., Inter, Helvetica Neue), Regular for body, Bold (and/or increased size) for headings
- **Text Hierarchy**:
  - Headings: Larger, bold; usually sentence case, left-aligned
  - Body: Normal, left-aligned, optimal line length (60-80 characters)
  - Inline code: Mono-spaced font, distinct background (typically light gray)
  - Links: Blue, underlined on hover
- **Whitespace**: 32-48px between sections, 20-28px between paragraphs, 16px line height minimum
- **Lists/Bullets**: Simple dots; left-indented; no graphical embellishments
- **Tables/Charts**: Data tables retain grid lines; charts/diagrams use minimal colors—one highlight per chart

### Writing System

- **Sentence Length**: Moderate (12-22 words typical); longer for technical exposition; rarely staccato/fragmented
- **Paragraph Structure**: 2-6 sentences per paragraph; each paragraph introduces a discrete idea, often evidenced or expanded in subsequent sentences
- **Formatting**:
  - Headings clearly delimited, never all-caps
  - Bulleted or numbered lists to enumerate technical steps, findings, or subpoints
  - Inline code formatting for technical terms, file paths, commands
  - Occasional use of bold for emphasis on section titles or key terms only, not in body
- **Emphasis**:
  - No excessive exclamation, no rhetorical questions
  - Prefer precision to flourish
- **Content Patterns**:
  - Introduce problem, progress to diagnosis, describe solution, then present metrics/outcomes

---

## 4. Layout / Structure

- **Linear, Section-based**:
  - Title (centered or left-aligned, largest font)
  - Subtitle / brief intro paragraph (optional)
  - Main body: Divided by H2/H3 headings, each with 1-4 paragraphs and/or a visual/chart
  - Visuals (charts/tables): Centered, placed directly beneath or within context (never floating right/left)
  - Code/Log blocks: Full-width, mono background, thin border or subtle shadow
  - End: Conclusions and/or references, call-to-action (e.g., next posts, contact, or linked references)
- **Margins**:
  - Content area: 700–850px wide max
  - Left/right margin: At least 48px from viewport edge
- **Hierarchy**:
  - Title > Section Heading > Subheading > Body > Lists/Code/Visuals
- **Whitespace**:
  - Clear demarcation between blocks (sections, visuals, code)

---

## 5. Style Rules

- **Headings**
  - Use sentence case, left-aligned
  - H2 for major sections, H3 for sub-sections; avoid H4+
- **Paragraphs**
  - Maximum 90 words; prefer <70
  - No indented paragraphs
- **Bullets/Numbered Lists**
  - Use to break up procedures, findings, or enumerated points; one idea per bullet
- **Links**
  - Blue, unstyled other than underlining on hover
- **Code/Text Highlight**
  - `Backticks` for inline code, code blocks for multi-line commands/logs
- **Visuals**
  - Place immediately after the paragraph introducing them
  - Keep image height <330px unless it's the main visual
- **Tone**
  - Analytical, direct, not conversational
  - Use data/results (“we reduced X from 22% to 3%”) to motivate points
- **Quotes**
  - Avoid block quotes unless referencing user/testimonial; not present in source

---

## 6. Critique Framework

### "On-Style" Criteria

- Headings, code, and lists clearly separated visually and semantically
- Blue links, understated typography, and monochrome palette
- Writing is precise, methodical, data-driven
- Sections structured: problem-intro, technical exposition, solution, outcome

### Common Failure Modes

- Decorative color usage or graphical flourishes
- Dense, unbroken text walls or excessive tldr-style summaries
- Overly casual voice, exclamatory punctuation, rhetorical questions
- Headings in all caps or unbalanced visual hierarchy
- Lack of supporting data or skipping methodical breakdown

### Invariant Elements

- Uninterrupted logical flow from problem to outcome
- Minimalist, functional visual hierarchy
- Use of code formatting for technical items
- Blue link color; no alternative accent palette

---

## 7. Reproduction Guide

### Template

```markdown
# Title of the Post

_Optional lead or summary sentence. Sets up the main subject._

## Problem/Context

Introduce the technical problem, providing necessary background, metrics if available.

## Approach/Diagnosis

Explain constraints, investigation steps, evidence gathered, potential hypotheses.

## Solution

Describe implemented fix(es), including:
- Enumerated steps or lists
- Code snippets, log samples, configuration changes

## Results

Present data: Before/after metrics, graphs, tables.
- Place supporting visuals immediately after mention in text

## Lessons Learned

Summarize key takeaways, future work, or remaining open questions.

---

Links: [point to references or related work]
```

### Do's

- Use section headings to break up narrative
- Employ numbered/bulleted lists for technical steps/results
- Include quantitative evidence (numbers, charts, tables)
- Apply code formatting for commands or literals
- Maintain monochrome palette except for blue links

### Don'ts

- Use decorative or multiple accent colors
- Employ overly informal/informal tone or rhetorical embellishment
- Present dense text with few visual breaks
- Write paragraphs exceeding 100 words

### Example Transformation Rule

- **Original**: "We soon noticed a significant drop in reliability."
- **Reproduced**: "Reliability decreased from 99.9% to 97.5% after the change was introduced."

---

```
