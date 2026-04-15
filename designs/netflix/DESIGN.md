# Netflix — Slide Design System

> Dark entertainment — cinematic black, red accent, content showcase for data-informed storytelling.

---

## 1. Overview

- **Style**: Dark Entertainment
- **Mood**: Cinematic, immersive, data-informed
- **Audience**: Content teams, executives, entertainment industry
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Cinematic dark canvas that mirrors the Netflix viewing experience. Bold red accents punctuate a deep black environment, drawing attention to content and data. Information is presented with the same confidence as a title card — large, clear, and impossible to miss. Every slide should feel like a frame from a story.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | netflixDark | `#141414` | Slide background (always) |
| Deep Black | black | `#000000` | Hero sections, emphasis areas |
| Card | card | `#1F1F1F` | Card backgrounds, content panels |
| Card Hover | cardHover | `#2A2A2A` | Elevated cards, active states |
| Primary Text | white | `#FFFFFF` | Titles, headings, key numbers |
| Body Text | light | `#E5E5E5` | Body copy, descriptions |
| Muted Text | muted | `#808080` | Captions, secondary info, timestamps |
| Accent | netflixRed | `#E50914` | Primary accent, CTAs, highlights |
| Positive | green | `#46D369` | Growth, success, completion |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#46D369` | Growth, success, viewership up |
| Negative | red | `#E50914` | Decline, churn, alert (same as accent) |
| Warning | amber | `#F5A623` | In-progress, caution, mid-tier |

### Color Rules

- Slide background is always `#141414` (Netflix Dark)
- Text is always light on dark — never dark text on light background
- Netflix Red `#E50914` is used sparingly for maximum impact: headings, accent bars, key metrics
- Cards use `#1F1F1F` to create subtle depth against the background
- Avoid large red fills — use thin red accent lines and small highlight areas
- Green `#46D369` is reserved for positive metrics only

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Slide Title | Netflix Sans / Helvetica Neue | 32pt | Bold | `#FFFFFF` |
| Cover Title | Netflix Sans / Helvetica Neue | 44pt | Bold | `#FFFFFF` |
| Subtitle | Helvetica Neue | 14pt | Regular | `#808080` |
| Section Heading | Netflix Sans / Helvetica Neue | 18pt | Bold | `#E50914` |
| Body | Helvetica Neue | 12pt | Regular | `#E5E5E5` |
| Table Header | Helvetica Neue | 10pt | Bold | `#FFFFFF` (on red) |
| Table Cell | Helvetica Neue | 10pt | Regular | `#E5E5E5` |
| Caption / Note | Helvetica Neue | 9pt | Regular | `#808080` |
| KPI Number | Netflix Sans / Helvetica Neue | 28pt | Bold | contextual |
| Footer Text | Helvetica Neue | 8pt | Regular | `#808080` |

### Typography Rules

- Netflix Sans (or Helvetica Neue fallback) for all headings and display text
- Helvetica Neue for body text and data
- Max font size: 44pt (cover title only). Body stays within 12pt
- Bold is reserved for headings, KPI numbers, and table headers
- All text is light-colored on dark backgrounds — never use dark text

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [Red Accent Line]                h: 0.04in   │
├──────────────────────────────────────────────┤
│  margin: 0.8in                               │
│                                              │
│  ┌─ Title ─────────────────────────┐ y: 0.4  │
│  └─────────────────────────────────┘         │
│  ┌─ Subtitle ──────────────────────┐ y: 1.0  │
│  └─────────────────────────────────┘         │
│  ┌─ Content Zone ──────────────────┐ y: 1.3  │
│  │         w: 11.73in              │         │
│  │                                 │         │
│  └─────────────────────────────────┘ y: 7.0  │
│                   [Footer: NETFLIX]  y: 7.1  │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Left/right margin: 0.8in → content width: 11.73in
- Title top: y=0.4in
- Content start: y=1.3in
- Footer: y=7.1in, right-aligned
- Card internal padding: 0.25in
- Card border-radius: 4px
- Minimum element gap: 0.2in

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 0.8in | 5.6in |
| Right | 6.8in | 5.73in |

---

## 5. Slide Types

### Cover Slide

- Full `#141414` background with thin red accent line at top
- Title: centered, 44pt, white, bold
- Subtle red gradient glow behind title area
- Subtitle: centered, 14pt, muted
- Netflix "N" or wordmark centered below subtitle
- Cinematic widescreen feel with generous vertical spacing

### Section Divider

- Dark background, red accent line at top
- Section title: left-aligned, 32pt, white
- Red underline accent (2in wide, 2pt)
- Optional subtitle below in muted color

### Content Slide (Text + Visual)

- Standard header (red accent line + title)
- Dark card panels (`#1F1F1F`) for content grouping
- Left-red-bar cards for structured information
- Content poster grid layouts for visual content
- Footer: "NETFLIX" right-aligned, muted

### Data Slide (Table / Chart)

- Header row: Netflix Red (`#E50914`) fill + white text
- Cell borders: 0.5pt, `#2A2A2A`
- Row background alternates: `#1F1F1F` / `#141414`
- Viewing data visualizations in brand colors

### KPI / Dashboard Slide

- Horizontal card row (up to 4 cards)
- Each card: `#1F1F1F` background, 28pt bold number, 10pt label
- Card width: ~2.5in, height: ~1.2in
- Red top border (3px) on primary KPI card
- Green/red number colors for positive/negative metrics

### Closing Slide

- Dark background with centered "Thank You" or next steps
- Red accent elements for emphasis
- Clean, cinematic framing

---

## 6. Component Patterns

### Tables

- Header: Netflix Red (`#E50914`) fill, white bold text, 10pt
- Cells: 10pt Helvetica Neue, `#2A2A2A` borders at 0.5pt
- Alternating row backgrounds: `#1F1F1F` / `#141414`
- No heavy grid lines — subtle separation only

### Cards / Callout Boxes

- Background: `#1F1F1F`
- Left accent bar: 3px wide, Netflix Red or semantic color
- Border-radius: 4px
- No shadows — depth through color layering

### Charts

- Primary data: `#E50914` (red)
- Secondary data: `#46D369` (green)
- Tertiary: `#808080` (muted)
- Axis labels and legends in `#808080`
- Grid lines in `#2A2A2A`

### Content Posters

- Grid of rectangular cards (poster aspect ratio or 16:9)
- Rounded corners (4px)
- Hover state: `#2A2A2A` background
- Title overlay on bottom with gradient fade

---

## 7. Do's and Don'ts

### Do

- Use dark backgrounds consistently — `#141414` is the canvas
- Let red accents guide the eye to what matters most
- Use large, bold numbers for KPIs that tell a story
- Create depth with card layers (`#1F1F1F` on `#141414`)
- Keep slides cinematic: generous spacing, strong hierarchy
- Use content poster grids for visual storytelling

### Don't

- Use white or light backgrounds
- Overuse red — it loses impact when everywhere
- Add decorative elements, icons, or clip art
- Use thin, low-contrast text that's hard to read on dark
- Mix multiple accent colors beyond the defined palette
- Use rounded rectangles with heavy borders

---

## 8. Agent Guide

When generating slides with the Netflix design system:

```
You are creating a presentation using the Netflix slide design system.
Key rules:
- Dark background always (#141414). All text is light on dark.
- Netflix Red #E50914 for accent lines, section headings, and key highlights only.
- Netflix Sans / Helvetica Neue for headings, Helvetica Neue for body.
- Every slide gets: thin red accent line (top), title, "NETFLIX" footer.
- Cards use #1F1F1F background for depth. No white backgrounds ever.
- Cinematic feel: generous spacing, large KPI numbers, poster-grid layouts.
- Red is earned — use sparingly for maximum impact.

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
