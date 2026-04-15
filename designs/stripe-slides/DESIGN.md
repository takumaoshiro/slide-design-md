# Stripe (Slides) — Slide Design System

> Developer-elegant presentation — purple gradient, clean data, technical sophistication. Precise, elegant, trustworthy.

---

## 1. Overview

- **Style**: Developer-elegant Product Deck
- **Mood**: Precise, elegant, trustworthy
- **Audience**: Developers, enterprise buyers, fintech stakeholders
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Technical sophistication through restraint. Dark navy sections for storytelling, white sections for data and evidence. The signature purple gradient signals Stripe's identity — used as accent, never as decoration. Code is a first-class citizen: syntax-highlighted, readable, and integrated into the narrative. Trust is built through clean data presentation and precise typography.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Accent | purple | `#635BFF` | Primary brand, CTAs, highlights |
| Accent Gradient End | purpleLight | `#7A73FF` | Gradient endpoint |
| Dark BG | navy | `#0A2540` | Dark section backgrounds |
| Light BG | white | `#FFFFFF` | Data sections, tables |
| Surface | light | `#F6F9FC` | Card backgrounds, code blocks |
| Body Text | bodyText | `#596980` | Paragraph text on light BG |
| Heading Text | slate | `#425466` | Subheadings on light BG |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | cyan | `#00D4AA` | Success metrics, growth |
| Success | green | `#30B85E` | Completion, active status |
| Negative | red | `#E25950` | Decline, error, alert |
| Warning | amber | `#D97917` | Caution, in-progress |

### Color Rules

- Dark navy (`#0A2540`) for narrative/story slides, white for data/evidence slides
- Purple gradient (`#635BFF` to `#7A73FF`) reserved for accent bars, key metrics, and CTAs
- Body text on white uses `#596980` — never pure black
- Body text on dark navy uses `#FFFFFF` at 85% opacity
- Code blocks: `#F6F9FC` background on light slides, `#0A2540` on dark slides
- Subtle grid/dot pattern overlay on dark sections (optional, 3-5% opacity)

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Hero Title | Inter | 48pt | Bold (700) | `#FFFFFF` (on dark) |
| Slide Title | Inter | 36pt | Semibold (600) | `#0A2540` (on light) |
| Subtitle | Inter | 20pt | Regular (400) | `#425466` |
| Section Label | Inter | 12pt | Bold (700) | `#635BFF` uppercase |
| Body | Inter | 16pt | Regular (400) | `#596980` |
| Table Header | Inter | 12pt | Semibold (600) | `#425466` |
| Table Cell | Inter | 14pt | Regular (400) | `#596980` |
| Code | Source Code Pro | 14pt | Regular (400) | syntax colors |
| Data Number | Inter | 56pt | Bold (700) | `#635BFF` |
| Caption | Inter | 12pt | Regular (400) | `#8898AA` |

### Typography Rules

- Inter for all UI/body text; Source Code Pro for code only
- Section labels: 12pt uppercase bold in purple — acts as an eyebrow above titles
- Headings on dark backgrounds are white; on light backgrounds are navy (`#0A2540`)
- Line height: 1.5 for body, 1.2 for headings, 1.6 for code
- Letter-spacing: -0.02em for large titles, normal for body

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [Purple gradient accent bar]      h: 0.04in  │
├──────────────────────────────────────────────┤
│  margin: 1.2in left/right, 0.8in top/bottom │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │      w: 10.93in  h: 5.9in          │     │
│  │                                     │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Left/right margin: 1.2in; top/bottom margin: 0.8in
- Section label to title gap: 0.15in
- Title to content gap: 0.4in
- Card internal padding: 0.3in
- Card gap: 0.2in
- Minimum element spacing: 0.15in

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 1.2in | 5.0in |
| Right | 6.8in | 5.33in |

---

## 5. Slide Types

### Cover Slide

- Navy background (`#0A2540`) with subtle grid pattern
- Purple gradient accent bar at top
- Section label: "STRIPE" uppercase, 12pt Bold, purple
- Title: centered, 48pt Bold, white
- Subtitle: centered, 20pt Regular, white at 70%
- Optional: subtle purple glow effect behind title

### Section Divider

- Navy background
- Section label (purple, uppercase) above
- Large title: 36pt Semibold, white
- Thin purple gradient line below title (3in wide, centered)

### Content Slide (Text + Code)

- White or light background
- Left column: title + body text
- Right column: code block with syntax highlighting
- Code block: rounded corners (8px), `#F6F9FC` background, subtle border

### Data Slide (Table / Metrics)

- White background
- Clean table: no outer border, subtle row separators (`#E3E8EE`)
- Header row: `#425466` text, bottom border 2px `#E3E8EE`
- Stripe purple for highlighted rows or key columns
- Alternating row background: transparent / `#F6F9FC`

### KPI / Dashboard Slide

- White background with navy header band (optional)
- Metric cards: `#F6F9FC` background, 0.3in padding, 8px radius
- Large number in purple (`#635BFF`), label in slate (`#425466`)
- Trend indicator: cyan (`#00D4AA`) for up, red (`#E25950`) for down

### Closing Slide

- Navy background
- "Get started" or CTA: centered, 36pt Semibold, white
- URL/link: 20pt Regular, purple
- Purple gradient accent bar at bottom

---

## 6. Component Patterns

### Tables

- Header: `#425466` semibold text, 2px bottom border `#E3E8EE`
- Cells: `#596980` regular text, 1px bottom border `#E3E8EE`
- No outer borders, no vertical rules
- Alternating rows: transparent / `#F6F9FC`
- Highlighted cell: purple text or purple left-border

### Code Blocks

- Background: `#F6F9FC` (light) or `#0A2540` (dark)
- Border: 1px `#E3E8EE` (light) or none (dark)
- Border-radius: 8px
- Padding: 0.3in
- Font: Source Code Pro, 14pt
- Syntax colors: purple for keywords, cyan for strings, green for comments

### Cards

- Background: `#F6F9FC`
- Border: 1px `#E3E8EE`
- Border-radius: 8px
- Padding: 0.3in
- No shadow (flat design)
- Optional: purple left-border (3px) for emphasis

### Icons / Badges

- Monoline style, 24px, `#425466` default
- Active/highlighted: `#635BFF`
- Payment method icons: outline style, consistent stroke width
- Status badges: pill shape, semantic color background at 15% opacity + text color

---

## 7. Do's and Don'ts

### Do

- Alternate dark (navy) and light (white) sections for rhythm
- Show code as a first-class content element with syntax highlighting
- Use purple gradient sparingly — accent bar and key metrics
- Present data in clean, borderless tables
- Use the section label pattern (purple uppercase eyebrow) consistently
- Let whitespace create hierarchy

### Don't

- Use purple as a background fill for large areas
- Mix more than 2 background colors on one slide
- Use decorative illustrations or clip-art
- Add drop shadows or 3D effects
- Use rounded pill buttons in content (reserve for CTAs)
- Crowd slides — maintain generous margins

---

## 8. Agent Guide

When generating slides with the Stripe (Slides) design system:

```
You are creating a developer-facing product presentation using the Stripe slide design system.
Key rules:
- Dark navy (#0A2540) for narrative slides, white for data/evidence slides.
- Purple gradient (#635BFF → #7A73FF) for accent bars and key metrics only.
- Inter for all text, Source Code Pro for code blocks.
- Code is first-class content: syntax-highlighted, readable, integrated.
- Tables: no outer borders, subtle row separators, clean and scannable.
- Section labels: 12pt uppercase bold purple "eyebrow" above titles.
- Metric cards: large purple number + slate label on #F6F9FC background.
- Every slide gets a thin purple gradient accent bar at the top.
- Target structure: Cover → Problem → Solution (with code) → Data → Metrics → CTA.
- "Technical sophistication through restraint."

Refer to the full DESIGN.md for color values, typography specs, and layout details.
```
