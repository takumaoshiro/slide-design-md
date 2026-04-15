# SoftBank — Slide Design System

> Japanese corporate — silver/gray gradient, authoritative, vision-driven presentations for investors and partners.

---

## 1. Overview

- **Style**: Japanese Corporate / Vision-Driven
- **Mood**: Visionary, authoritative, large-scale
- **Audience**: Investors, partners, press, internal executives
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Silver-to-white gradients convey scale and authority. Dark navy headers anchor each slide with gravitas while light backgrounds keep data readable. Every slide should feel like it belongs in a keynote addressing global investors — bilingual-ready, data-rich, and vision-forward. "Think big. Present bigger."

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background |
| Light Background | lightBg | `#F5F5F5` | Card backgrounds, aside areas |
| Primary Text | navy | `#1B2A4A` | Titles, headings, dark headers |
| Body Text | text | `#333333` | Body copy, table cells |
| Muted Text | muted | `#999999` | Captions, page numbers, notes |
| Silver | silver | `#8C8C8C` | Gradient elements, decorative lines |
| Accent Blue | accent | `#0078D4` | Key metrics, links, highlights |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#008A00` | Growth, success, investment gains |
| Negative | red | `#CC0000` | Decline, risk, losses |

### Color Rules

- Slide backgrounds alternate between `#FFFFFF` and `#F5F5F5` for visual rhythm
- Cover slides use silver-to-white gradient backgrounds
- Dark navy (`#1B2A4A`) is reserved for header bars and cover backgrounds
- Accent blue (`#0078D4`) is used sparingly for key metrics and interactive elements
- Silver (`#8C8C8C`) is for decorative borders, gradient endpoints, and secondary text
- No bright or saturated colors outside of semantic green/red

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Cover Title | Noto Sans JP / Arial | 40pt | Bold | `#FFFFFF` (on navy) |
| Slide Title | Noto Sans JP / Arial | 28pt | Bold | `#1B2A4A` |
| Vision Statement | Noto Sans JP / Arial | 36pt | Bold | `#1B2A4A` |
| Subtitle | Noto Sans JP / Arial | 14pt | Regular | `#999999` |
| Section Heading | Noto Sans JP / Arial | 16pt | Bold | `#0078D4` |
| Body | Noto Sans JP / Arial | 12pt | Regular | `#333333` |
| Table Header | Noto Sans JP / Arial | 10pt | Bold | `#FFFFFF` (on navy) |
| Table Cell | Noto Sans JP / Arial | 10pt | Regular | `#333333` |
| Caption / Note | Noto Sans JP / Arial | 9pt | Regular | `#999999` |
| KPI Number | Arial | 32pt | Bold | contextual |
| Footer | Noto Sans JP / Arial | 8pt | Regular | `#8C8C8C` |

### Typography Rules

- Noto Sans JP is the primary font for Japanese text; Arial for English fallback
- Vision statements can go up to 36pt — they are the centerpiece of strategy slides
- Body text stays within 11-12pt for readability
- Bold is reserved for headings, KPI numbers, and table headers
- Bilingual slides: Japanese title on top, English subtitle below in lighter weight

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [Navy Header Bar]                h: 0.9in    │
│  Title (white) + Subtitle                    │
├──────────────────────────────────────────────┤
│  margin: 0.8in                               │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │         w: 11.73in                  │     │
│  │                                     │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
├──────────────────────────────────────────────┤
│ [Footer: logo, page number]      h: 0.4in   │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Left/right margin: 0.8in, content width: 11.73in
- Navy header bar: top 0.9in with white text
- Content zone: y=1.1in to y=6.9in
- Footer: y=7.1in, logo left-aligned, page number right-aligned
- Card internal padding: 0.3in
- Minimum element gap: 0.2in

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 0.8in | 5.5in |
| Right | 6.8in | 5.73in |

### Three-Column Layout (Portfolio Grid)

| Column | x | w |
|--------|---|---|
| Col 1 | 0.8in | 3.5in |
| Col 2 | 4.8in | 3.5in |
| Col 3 | 8.8in | 3.73in |

---

## 5. Slide Types

### Cover Slide

- Dark navy (`#1B2A4A`) full-bleed background
- Silver-to-navy gradient overlay at bottom
- Title: centered, 40pt, white, bold
- Subtitle: centered, 18pt, silver (`#8C8C8C`)
- Date and event name: centered, 12pt, silver
- Logo: bottom-center, white version

### Section Divider

- Full navy background
- Section title: centered, 28pt, white
- Thin silver line below title (width: 3in, centered)
- Section number in large silver text (60pt, 20% opacity)

### Content Slide (Vision + Text)

- Navy header bar at top with white title
- Content zone below with white/light background
- Large vision statement or key message in 36pt navy
- Supporting bullet points in 12pt body text
- Timeline or roadmap visualization for strategy slides

### Data Slide (Table / Financial)

- Navy header bar at top
- Financial tables with navy headers and white text
- Cell borders: 0.5pt, `#D0D0D0`
- Row height: 0.35in
- Currency and percentage formatting standardized
- YoY comparison columns with green/red semantic coloring

### KPI / Dashboard Slide

- Navy header bar at top
- Horizontal KPI card row (up to 4 cards)
- Each card: white background, subtle border, large number (32pt), label (10pt)
- Investment portfolio grid: 3-column layout with company cards

### Closing Slide

- Dark navy background
- "Thank you" or "Next Steps" centered, 36pt white
- Contact information or summary below in silver
- Logo: bottom-center

---

## 6. Component Patterns

### Tables

- Header: navy (`#1B2A4A`) fill, white bold text, 10pt
- Cells: 10pt, `#D0D0D0` borders at 0.5pt
- Alternating row backgrounds: white / `#F5F5F5`
- Financial figures right-aligned, text left-aligned

### Cards / Callout Boxes

- Background: `#FFFFFF` with 1px `#D0D0D0` border
- Subtle shadow: 0 2px 8px rgba(0,0,0,0.06)
- Corner radius: 4px
- Left accent bar: 4px wide, accent blue or navy

### Portfolio Grid

- 3-column card layout for investment companies
- Each card: logo top, company name, sector tag, key metrics
- Consistent card height within each row

### Timeline / Roadmap

- Horizontal timeline with navy nodes and silver connecting lines
- Milestone labels below each node
- Current position highlighted with accent blue

### Charts

- Bar/line charts use navy, accent blue, and silver palette
- Axis labels: 9pt, muted
- Legend: positioned below chart, 9pt

---

## 7. Do's and Don'ts

### Do

- Use dark navy headers for authoritative framing
- Include large vision statements on strategy slides
- Use silver/gray gradients for elegant visual depth
- Keep financial data clean with proper alignment and formatting
- Support bilingual (JP/EN) content on key slides
- Use portfolio grid layouts for investment overviews

### Don't

- Use bright or saturated colors (keep palette restrained)
- Add decorative icons or playful elements
- Use more than 3 fonts or font sizes per slide
- Overcrowd slides — aim for 1 key message per slide
- Use rounded or bubble-style shapes
- Place text over complex imagery without overlay

---

## 8. Agent Guide

When generating slides with the SoftBank design system:

```
You are creating a vision-driven corporate presentation using the SoftBank design system.
Key rules:
- Dark navy (#1B2A4A) header bars on content slides, full navy on cover/closing.
- Silver (#8C8C8C) to white gradients for elegant visual depth.
- Noto Sans JP / Arial for all text. Vision statements up to 36pt.
- Financial tables: navy headers, right-aligned numbers, green/red for YoY changes.
- Portfolio grid: 3-column card layout with company name, sector, and key metrics.
- Bilingual-ready: Japanese primary, English subtitle where needed.
- Mood is visionary and authoritative — "Think big. Present bigger."

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
