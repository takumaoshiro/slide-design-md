# McKinsey — Slide Design System

> Classic consulting — navy-anchored, structured, insight-driven executive presentations.

---

## 1. Overview

- **Style**: Classic Consulting
- **Mood**: Authoritative, structured, insight-driven
- **Audience**: C-suite executives, board members
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Navy header bands anchor every slide, creating a consistent visual rhythm across the deck. Titles are action titles — each one states the key insight, not a topic label. Information hierarchy is absolute: the audience should grasp the "so what" from the title alone, then confirm with the supporting data below.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background |
| Primary Text | dark | `#2D2D2D` | Titles, headings |
| Body Text | body | `#4A4A4A` | Body copy, table cells |
| Muted Text | muted | `#8C8C8C` | Captions, page numbers, sources |
| Border | border | `#D4D4D4` | Table borders, separators |
| Section BG | lightBg | `#F2F2F2` | Gray section backgrounds, aside areas |
| Accent | navy | `#003A70` | Header bands, table headers, key labels |
| Accent Light | navyLight | `#E6EDF5` | Accent area backgrounds |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#1A7A3A` | Growth, success, on-track |
| Negative | red | `#B81D24` | Decline, risk, off-track |
| Warning | amber | `#D4860B` | In-progress, caution |

### Color Rules

- Slide background is always `#FFFFFF`
- Navy (`#003A70`) is used for header bands and table header rows with white text
- Red (`#B81D24`) is reserved for emphasis only — never decorative
- Gray (`#F2F2F2`) backgrounds define distinct content sections within a slide
- Avoid gradients, shadows, and decorative fills throughout

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Action Title | Georgia | 24pt | Bold | `#FFFFFF` (on navy band) |
| Cover Title | Georgia | 36pt | Bold | `#2D2D2D` |
| Cover Subtitle | Arial | 18pt | Regular | `#8C8C8C` |
| Exhibit Number | Arial | 9pt | Bold | `#8C8C8C` |
| Section Heading | Georgia | 14pt | Bold | `#003A70` |
| Body | Arial | 11pt | Regular | `#4A4A4A` |
| Table Header | Arial | 9pt | Bold | `#FFFFFF` (on navy) |
| Table Cell | Arial | 9pt | Regular | `#4A4A4A` |
| Caption / Source | Arial | 8pt | Regular | `#8C8C8C` |
| KPI Number | Arial | 28pt | Bold | contextual |
| Footer | Arial | 8pt | Regular | `#8C8C8C` |

### Typography Rules

- Georgia is for titles and section headings only — all other text uses Arial
- Action titles state the key insight (e.g., "Revenue grew 12% driven by APAC expansion"), never a topic label
- Max font size: 36pt (cover only). Body stays at 11pt, tables at 9pt
- Bold is reserved for headings, table headers, and emphasized KPI numbers

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
+----------------------------------------------+
| [Navy Header Band]               h: 0.75in  |
| Action Title (white text, left-aligned)      |
+----------------------------------------------+
|  margin: 0.75in                              |
|                                              |
|  +- Exhibit Number -----------------+ y: 1.0 |
|  +- Content Zone -------------------+ y: 1.2 |
|  |         w: 11.83in              |         |
|  |                                 |         |
|  +---------------------------------+ y: 6.8  |
|  [Source / Footer]                   y: 7.1  |
+----------------------------------------------+
```

### Spacing Rules

- Left/right margin: 0.75in -> content width: 11.83in
- Navy header band: top of slide, 0.75in tall, full width
- Content start: y=1.2in (below exhibit number)
- Source line: y=7.1in, left-aligned, 8pt Arial, muted
- Footer: y=7.25in, right-aligned, page number
- Grid gutter: 0.3in between columns

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 0.75in | 5.67in |
| Right | 6.72in | 5.86in |

### Three-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 0.75in | 3.61in |
| Center | 4.66in | 3.61in |
| Right | 8.57in | 4.01in |

---

## 5. Slide Types

### Cover Slide

- White background, no header band
- Title: centered, 36pt Georgia Bold, `#2D2D2D`
- Subtitle: centered, 18pt Arial, `#8C8C8C`
- Thin navy rule: centered, 3in wide, 2pt
- Date and confidentiality note: centered, 10pt, `#8C8C8C`
- Logo or firm name: bottom-center, 12pt, navy

### Section Divider

- Navy background, full bleed
- Section title: centered, 28pt Georgia Bold, white
- Optional subtitle: 14pt Arial, white at 70% opacity

### Content Slide (Exhibit)

- Navy header band with action title (white text)
- Exhibit number: "Exhibit 1" format, top-left below band
- Structured content area with grid layout
- Source line at bottom-left
- Page number at bottom-right

### Data Slide (Table / Chart)

- Navy header band with action title
- Header row: navy fill + white bold text
- Cell borders: 0.5pt, `#D4D4D4`
- Row height: 0.3-0.4in
- Alternating row backgrounds: white / `#F2F2F2`
- Chart area: clean axes, navy/gray color scheme

### KPI / Dashboard Slide

- Navy header band with action title
- Horizontal card row (3-5 cards)
- Each card: `#F2F2F2` background, large bold number, small label
- Traffic-light indicators using semantic colors
- Card width: ~2.2in, height: ~1.1in

### Closing Slide

- Summary of key findings in structured format
- "Next steps" or "Implications" section
- Contact information block

---

## 6. Component Patterns

### Tables

- Header: navy (`#003A70`) fill, white bold text, 9pt Arial
- Cells: 9pt Arial, `#D4D4D4` borders at 0.5pt
- Alternating rows: white / `#F2F2F2` for readability
- Right-align numerical columns

### Cards / Callout Boxes

- Background: `#F2F2F2`
- No border radius (sharp corners)
- No shadows
- Optional left accent bar: 3px, navy or semantic color

### Charts

- Primary series: `#003A70` (navy)
- Secondary series: `#8C8C8C` (gray)
- Highlight series: `#B81D24` (red, for emphasis)
- Clean axis lines, no gridlines, labels in 8pt Arial
- Legend: bottom-aligned, horizontal

### Exhibit Numbers

- Format: "Exhibit 1", "Exhibit 2", etc.
- Position: top-left, below header band
- Style: 9pt Arial Bold, `#8C8C8C`

---

## 7. Do's and Don'ts

### Do

- Write action titles that state the insight ("Revenue grew 12% driven by APAC") not the topic ("Revenue Overview")
- Use exhibit numbering for all content and data slides
- Structure information in grids with clear visual hierarchy
- Include source citations on every data slide
- Use navy header bands consistently on all slides except cover and dividers
- Keep data tables dense — consulting audiences expect information richness

### Don't

- Use decorative icons, clip art, or stock photos
- Apply gradients, shadows, or rounded corners
- Use more than 3 colors on any single slide
- Center body text — always left-align
- Use bullet points when a table or framework would be clearer
- Add animations or transitions

---

## 8. Agent Guide

When generating slides with the McKinsey design system:

```
You are creating a consulting presentation using the McKinsey slide design system.
Key rules:
- Every content slide has a navy header band (0.75in, #003A70) with a white action title.
- Action titles state the insight, not the topic. "Revenue grew 12% YoY" not "Revenue Overview."
- Georgia for titles, Arial for everything else.
- Exhibit numbering on all content slides: "Exhibit 1", "Exhibit 2", etc.
- Include source citations at the bottom of every data slide.
- No decorative elements: no icons, no gradients, no shadows, no rounded corners.
- Use structured grids, tables, and frameworks over bullet points.
- Target 10-15 slides for a standard engagement: Cover -> Executive Summary -> 8-12 Exhibits -> Next Steps.

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
