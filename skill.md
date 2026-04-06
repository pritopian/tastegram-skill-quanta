```markdown
# skills.md

## 1. Overview

**Quanta: Anthropic Engineering Blog Post Style**  
This skill encapsulates the distinctive "Quanta" style found on the Anthropic Engineering Blog, as exemplified by the "Managing Infrastructure at Noise: Making Things Just Work" post. The style features a deliberate, technical-yet-approachable tone, systematic blog structure, and clean web layout with clear typographic and visual hierarchy.

---

## 2. Core Characteristics

- Analytical, matter-of-fact, and accessible writing
- Structured, modular blog layout
- Hierarchical use of bold, headers, bullet lists, and callouts
- Light, readable typography
- Ample whitespace and clear content separation
- Occasional, informative images or code snippets
- Consistent metadata presentation (author, date, tags)

---

## 3. Visual / Writing System

### Visual Rules

- **Typography**
  - Primary font: Sans-serif (e.g., Inter, Helvetica, Arial)
  - Header hierarchy: 
    - H1: Large, bold
    - H2: Medium, bold
    - H3: Small, semibold
  - Body: Medium weight, 16-18px, black or #222 color
  - Links: Text color in Anthropic blue (#234BFF), underlined on hover
  - Blockquotes: Left border, light or faded background, slightly indented
  - Inline code: Monospaced font, light background
- **Images/Figures**
  - Centered, max-width: 90% of content area
  - Clear caption below image, smaller font
  - Screenshots/code: High contrast, monospaced, padded
- **Content Containers**
  - Article container max-width: 700-800px, centered
  - Navigation/menu bar with logo and links at top
  - Author/date info at bottom or top of post
  - Section dividers: subtle horizontal rule or increased whitespace
- **Whitespace**
  - 24-32px vertical margin between sections
  - 16-24px padding around paragraphs/images
- **Color Palette**
  - Background: #FFFFFF or off-white
  - Text: #222222 primary, #444444 secondary
  - Accent/links: #234BFF
  - Blockquote/feature callout bg: #F6F8FA
  - Horizontal rules: #EAEAEA

### Writing System

- **Headers**
  - Start with a large, descriptive title
  - Use logical headers (H2/H3) to break content into clear sections
  - Never skip header levels
- **Intro**
  - Short, context-setting introductory paragraph
- **Body**
  - Consistent paragraph lengths (2-5 sentences per paragraph)
  - Frequent use of bullet/numbered lists to clarify points
  - Interspersed blockquotes or callouts for side notes/clarifications
  - Occasional in-paragraph text bolding for emphasis
  - Direct quotes indented or demarcated
- **Code/Technical**
  - Inline technical terms/calls in code font (backticks)
  - Isolated code blocks: triple-backtick syntax, monospace, light gray background
  - Code examples clearly labeled or introduced
- **End Matter**
  - Brief recap or summary
  - Author name, publication date, tags
  - Optional: further reading links

---

## 4. Layout / Structure

### Web Layout

- **Header/Nav**
  - Top bar: Anthropic logo left, main site links right
  - Sticky or always visible
- **Main Content**
  - Single column, centered
  - Max-width: 700-800px
  - Padding: min 24px on mobile, 40px+ on desktop
  - Left-aligned text, ragged right margin
- **Visual Hierarchy**
  - H1 draws first attention (largest element)
  - H2/H3 guide through sections (distinct size/weight)
  - Hero image (if present) located just below title
  - Lists and blockquotes provide substructure and entry points
  - Author/date lines are subdued (lighter text, smaller font)
- **Spacing**
  - Large vertical whitespace between sections
  - Slightly tighter spacing within sections
  - Minimum 16px between paragraphs or adjacent elements

---

## 5. Style Rules

- **Typography**
  - Use Inter or system sans-serif for all text
  - Set H1 at 2.6–3.2em, bold
  - Maintain 16–18px base font size for body
  - Style inline code as `code` (monospace, #F6F8FA bg)
  - Underline links only on hover
- **Composition**
  - Always start with a concise intro or abstract
  - Break content into logical, scannable sections with H2/H3 headers
  - Use bullet lists for triple-or-more item sets
  - Apply blockquotes for quotes, external references, or asides
  - Insert at least one code snippet or image per technical section
  - End with summary, author/date, and tags
- **Colors**
  - Background: #FFFFFF (solid)
  - Main text: #222222
  - Secondary (e.g., author): #808080
  - Link/Accent: #234BFF

---

## 6. Critique Framework

- **On-Style Output**
  - Clean, single-column layout with ample whitespace
  - Clearly defined information hierarchy via headers and spacing
  - Readable, sans-serif typography
  - Balanced mix of narrative, lists, and code/visual examples
  - Accessible tone: friendly but technical; never too casual or too dry
  - Accurate metadata and clear content sections
- **Common Failure Modes**
  - Overly dense paragraphs or walls of text
  - Inconsistent or missing headers
  - Insufficient spacing or visual clutter
  - Incorrect font, size, or color application
  - Missing metadata (author, date, tags)
  - Broken or inconsistent list and code styles
- **Invariants**
  - Header/section progression is strictly logical (no skips)
  - Author/date info present and visually distinct
  - All main colors and font rules adhered to

---

## 7. Reproduction Guide

### Template

```markdown
# {Post Title}

*Author: {Author Name} | {Date} | {Tags}*

---

## {Section Header}

{Short introductory paragraph.}

### {Subsection Header (if needed)}

- Bullet or numbered list items
- Clear explanations
- Technical terms as `inline code`

> Blockquote for quotes/asides.

```code
# Example code block
some_example_function()
```

{Image/figure, centered, caption below.}

---

## Summary

{Brief recap or actionable takeaways.}

---

*Author: {Author Name} | {Date} | {Tags}*
```

### Do's

- Do maintain strict header hierarchy and logical section flow
- Do space out content for readability and scannability
- Do use lists, blockquotes, and code blocks as in-source structure
- Do ensure all metadata is present and styled as secondary

### Don'ts

- Don’t use serif fonts or colored backgrounds
- Don’t allow any section to visually run into the next 
- Don’t omit author/date details
- Don’t overlap images/text or break one-column constraint

### Example Transformation Rules

- Any quoted text → Convert to blockquote with left border and gray bg
- Any technical function/term → Wrap with inline code style
- Any list of three or more → Use markdown bullets, separated by blank lines
- Section headings → Always use H2/H3, never H4+ or skip

---

```
This skill file enables deterministic recreation, critique, or extension of Anthropic’s engineering blog "Quanta" taste.
```