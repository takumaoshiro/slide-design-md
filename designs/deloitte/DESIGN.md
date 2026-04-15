# Deloitte — Slide Design System

> Professional services — green accent, structured, insight-led presentations for enterprise audiences.

---

## 1. Overview

- **Style**: Professional Services
- **Mood**: Trustworthy, structured, insightful
- **Audience**: Enterprise clients, regulators, senior management
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Clean white canvas anchored by Deloitte Green as the singular accent color. Every slide leads with an insight — titles are conclusions, not labels. Structure creates trust: consistent headers, numbered sections, and sourced data. The design earns credibility through restraint, letting content and analysis speak with authority.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background (always) |
| Primary Text | black | `#000000` | Titles, headings |
| Body Text | body | `#333333` | Body copy, table cells |
| Muted Text | muted | `#767676` | Captions, footnotes, page numbers |
| Accent | deloitteGreen | `#86BC25` | Section headings, header bars, highlights |
| Dark Green | darkGreen | `#43B02A` | Secondary accent, chart elements |
| Teal | teal | `#0076A8` | Tertiary accent, links, supporting data |
| Light BG | lightBg | `#F2F2F2` | Card backgrounds, aside areas |
| Border | border | `#D0D0D0` | Table borders, separators |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#86BC25` | Growth, success, on-track |
| Negative | red | `#DA291C` | Decline, risk, off-track |
| Warning | amber | `#ED8B00` | In-progress, caution, monitor |

### Color Rules

- Slide background is always `#FFFFFF`
- Deloitte Green `#86BC25` is the primary accent — used for header bars, section titles, and key highlights
- Table headers get green fill (`#86BC25`) with white text
- Every slide has a green accent bar at the top (h: 0.06in, full width)
- Body text is `#333333` — never pure black for body copy
- Color in data is purposeful: green for positive, red for negative, teal for neutral/reference
- No decorative color fills or gradients

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Slide Title | Open Sans / Arial | 24pt | Bold | `#000000` |
| Cover Title | Open Sans / Arial | 36pt | Bold | `#000000` |
| Subtitle | Open Sans / Arial | 13pt | Regular | `#767676` |
| Section Heading | Open Sans / Arial | 14pt | Bold | `#86BC25` |
| Body | Open Sans / Arial | 11pt | Regular | `#333333` |
| Table Header | Open Sans / Arial | 10pt | Bold | `#FFFFFF` (on green) |
| Table Cell | Open Sans / Arial | 10pt | Regular | `#333333` |
| Caption / Footnote | Open Sans / Arial | 8pt | Regular | `#767676` |
| KPI Number | Open Sans / Arial | 28pt | Bold | contextual |
| Source Line | Open Sans / Arial | 7pt | Italic | `#767676` |

### Typography Rules

- Open Sans is the primary font (Arial as system fallback)
- Max font size: 36pt (cover title only). Body stays within 11pt
- Bold is reserved for headings, table headers, and KPI numbers
- Titles are insight-led: state the conclusion, not just the topic
- Footnotes and source lines are always present on data slides

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [Green Accent Bar]               h: 0.06in   │
├──────────────────────────────────────────────┤
│  margin: 0.75in                              │
│                                              │
│  ┌─ Title ─────────────────────────┐ y: 0.35 │
│  └─────────────────────────────────┘         │
│  ┌─ Subtitle ──────────────────────┐ y: 0.85 │
│  └─────────────────────────────────┘         │
│  ─── separator line ─────────────── y: 1.1   │
│  ┌─ Content Zone ──────────────────┐ y: 1.2  │
│  │         w: 11.83in              │         │
│  │                                 │         │
│  └─────────────────────────────────┘ y: 6.9  │
│  [Source / Footnote]                 y: 7.0  │
│  [Footer: page # + Deloitte logo]    y: 7.15 │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Left/right margin: 0.75in → content width: 11.83in
- Title top: y=0.35in
- Content start: y=1.2in (below separator)
- Footnote area: y=7.0in
- Footer: y=7.15in with page number and logo
- Card internal padding: 0.2in
- Minimum element gap: 0.15in

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 0.75in | 5.6in |
| Right | 6.65in | 5.43in |

---

## 5. Slide Types

### Cover Slide

- White background with green accent bar at top
- Title: centered, 36pt, black, bold
- Subtitle: centered, 13pt, muted
- Green horizontal rule as decorative separator (3in wide, 2pt)
- Date, client name, and "Confidential" marker below
- Deloitte logo centered at bottom

### Section Divider

- White background, green accent bar at top
- Large section number in green (e.g., "01")
- Section title: left-aligned, 24pt, black, bold
- Green underline accent

### Content Slide (Text + Visual)

- Standard header (green accent bar + insight-led title + separator)
- Two-column layout: findings on left, recommendations on right
- Green left-bar callout boxes for key insights
- Footnoted sources at bottom of every data-driven slide
- Footer: page number + "Deloitte" right-aligned

### Data Slide (Table / Chart)

- Header row: Deloitte Green (`#86BC25`) fill + white text
- Cell borders: 0.5pt, `#D0D0D0`
- Clean white rows — no row striping by default
- Source line below table in italic, 7pt, muted
- Professional data tables with clear column alignment

### KPI / Dashboard Slide

- Horizontal card row (up to 4 cards)
- Each card: `#F2F2F2` background, green top border (3px)
- 28pt bold number + 10pt label below
- Card width: ~2.5in, height: ~1.1in
- Semantic colors for positive/negative/neutral indicators

### Closing Slide

- Summary of key findings and recommended actions
- Two-column: findings vs. next steps
- Green accent elements for emphasis
- Contact information and disclaimer text

---

## 6. Component Patterns

### Tables

- Header: Deloitte Green (`#86BC25`) fill, white bold text, 10pt
- Cells: 10pt Open Sans, `#D0D0D0` borders at 0.5pt
- No row striping — clean white rows
- Source citation below every data table

### Cards / Callout Boxes

- Background: `#F2F2F2`
- Left accent bar: 4px wide, Deloitte Green
- No corner radius (sharp corners for professionalism)
- No shadows — flat design only

### Charts

- Primary data: `#86BC25` (Deloitte Green)
- Secondary data: `#0076A8` (Teal)
- Tertiary: `#43B02A` (Dark Green)
- Negative: `#DA291C` (Red)
- Axis labels in `#767676`, grid lines in `#D0D0D0`
- Always include data labels and legend

### Footnotes & Sources

- Positioned at y=7.0in, left-aligned
- Format: "Source: [Author/Org], [Title], [Year]"
- 7pt italic, `#767676`
- Every data slide must have at least one source

---

## 7. Do's and Don'ts

### Do

- Lead with insight — titles should state conclusions, not topics
- Use green accent bar on every slide for brand consistency
- Include source citations on all data-driven slides
- Use two-column layouts for findings/recommendations pairs
- Apply consistent footer with page number and Deloitte branding
- Keep data tables clean with green headers and white rows

### Don't

- Use dark backgrounds — white is always the canvas
- Add decorative elements, icons, or unnecessary imagery
- Use gradients, shadows, or 3D effects
- Present data without source attribution
- Use more than 3 accent colors on a single slide
- Write descriptive titles instead of insight-led conclusions

---

## 8. Agent Guide

When generating slides with the Deloitte design system:

```
You are creating a professional services presentation using the Deloitte design system.
Key rules:
- White background always. Deloitte Green #86BC25 is the singular accent color.
- Open Sans / Arial for all text. Titles are insight-led conclusions, not labels.
- Every slide gets: green accent bar (top), insight title, separator, page number + "Deloitte" footer.
- Table headers are green (#86BC25) with white text. No row striping.
- Two-column layouts for findings/recommendations. Source citations on every data slide.
- No decorative elements: no icons, no gradients, no shadows. Flat, professional design.
- Target 6-8 slides: Cover → Executive Summary → Findings → Data → Recommendations → Next Steps → Appendix.

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
