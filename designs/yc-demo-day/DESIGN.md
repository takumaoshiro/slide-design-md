# Y Combinator Demo Day — Slide Design System

> Demo Day pitch — orange accent, fast-paced, metric-driven. 10 slides, 2 minutes, no fluff.

---

## 1. Overview

- **Style**: Demo Day Pitch
- **Mood**: Urgent, metric-driven, no-nonsense
- **Audience**: YC partners, investors, Silicon Valley VCs
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

One metric per slide. Large numbers. Zero decoration. The YC Demo Day format is ruthlessly efficient — you have 2 minutes and 10 slides to prove your startup is worth funding. Orange is the only accent color, used to draw the eye to the single most important number on each slide. White space is not wasted space — it is focus. "Speed over beauty. Clarity over cleverness."

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background (always) |
| Primary Text | black | `#111111` | Titles, key statements |
| Body Text | text | `#333333` | Body copy, descriptions |
| Muted Text | muted | `#888888` | Captions, labels, secondary info |
| Accent | orange | `#F26522` | The ONE accent — key metrics, highlights |
| Accent Light | orangeLight | `#FFF3EB` | Accent area backgrounds |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#16A34A` | Revenue growth, traction up |
| Negative | red | `#DC2626` | Churn, burn rate warning |

### Color Rules

- Background is always pure white `#FFFFFF` — no gradients, no fills
- YC Orange (`#F26522`) is the ONLY accent color. No secondary accents.
- Orange is used for: the key metric on each slide, the team slide header, and CTA
- Green/red appear only for directional indicators (up/down arrows, percentages)
- No background colors on slides except white and `#FFF3EB` for orange-highlighted cards
- Zero decorative elements: no lines, no shapes, no borders unless essential

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Cover Title | Inter | 48pt | Bold | `#111111` |
| Slide Title | Inter | 32pt | Bold | `#111111` |
| Key Metric | Inter | 80pt+ | Bold | `#F26522` |
| Subtitle | Inter | 18pt | Regular | `#888888` |
| Body | Inter | 16pt | Regular | `#333333` |
| Label | Inter | 14pt | Medium | `#888888` |
| Table Header | Inter | 14pt | Bold | `#111111` |
| Table Cell | Inter | 14pt | Regular | `#333333` |
| Caption / Note | Inter | 12pt | Regular | `#888888` |
| CTA Text | Inter | 24pt | Bold | `#F26522` |

### Typography Rules

- Inter is the ONLY font. No exceptions. No serif, no monospace.
- Key metrics are 80pt or larger — they must be readable from the back of the room
- One font size hierarchy per slide: title + metric + label (3 levels max)
- Bold is for titles and numbers only. Body text is always Regular weight.
- No italic. No underline. No ALL CAPS except short labels (e.g., "MRR", "ARR").

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│                                              │
│  margin: 1.2in                               │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │                                     │     │
│  │   [ONE BIG NUMBER]                  │     │
│  │   [label underneath]               │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
│                                              │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Generous margins: 1.2in on all sides — content width: 10.93in
- Vertical centering: key metric is centered vertically on the slide
- Title top: y=0.8in (left-aligned when present)
- No footer on most slides — every pixel goes to the message
- When subtitle exists: 0.3in below the metric number
- Team slide: headshot grid with 0.4in gaps

---

## 5. Slide Types

### Slide 1: Cover

- Company name: 48pt bold, centered, black
- One-line description: 18pt, centered, muted
- YC batch identifier: 14pt, orange, centered (e.g., "W25")
- Nothing else. No logo. No imagery.

### Slide 2: Problem

- Title: "Problem" — 32pt bold, left-aligned
- 1-2 sentences max describing the pain point
- Optional: one large number showing market pain

### Slide 3: Solution

- Title: "Solution" — 32pt bold, left-aligned
- One sentence describing what you built
- Optional: simple product screenshot (no mockups or decorative frames)

### Slide 4: Traction

- THE most important slide
- One giant metric: 80pt+ orange (e.g., "$1.2M ARR")
- Growth rate below: "4x YoY" or "32% MoM"
- Subtitle label: 14pt muted

### Slide 5: Revenue / Business Model

- Revenue metric: 80pt+ orange
- Business model in 1 line: 16pt body text
- Unit economics: simple 2-3 row table

### Slide 6: Market Size

- TAM/SAM/SOM as 3 large numbers
- Each with label below
- Horizontal layout, evenly spaced

### Slide 7: Why Now

- Title: "Why Now" — 32pt bold
- 2-3 bullet points max, 16pt body text

### Slide 8: Team

- Headshot circles in a row (up to 4)
- Name + title below each
- Key credential: 12pt muted (e.g., "Ex-Google, Stanford CS")

### Slide 9: Ask

- "Raising $X" — 80pt+ orange, centered
- Use of funds: 2-3 lines, 16pt body
- Round details: 14pt muted

### Slide 10: Closing / Contact

- Company name: 48pt bold, centered
- Contact email: 18pt, orange
- One-line tagline repeated

### KPI / Metrics Slide (Generic)

- One metric per slide: 80pt+ orange number, centered
- Label below: 14pt muted
- Optional context line: 16pt body text

---

## 6. Component Patterns

### Tables

- Minimal: no borders, no cell backgrounds
- Header: bold black text, bottom border only (2px `#111111`)
- Cells: regular text, bottom border (1px `#E5E5E5`)
- Max 3 columns, max 5 rows — keep it scannable

### Metric Cards

- White background, optional `#FFF3EB` fill for emphasis
- Large number: 80pt+ orange
- Label: 14pt muted, directly below
- No borders, no shadows, no decorations

### Team Headshots

- Circular crop, 1.5in diameter
- Thin border: 2px `#E5E5E5`
- Name: 16pt bold below
- Title: 14pt muted below name

### Charts (use sparingly)

- Simple line or bar only — no pie charts, no 3D
- Orange for primary series, muted gray for secondary
- Minimal axis labels, no gridlines
- Large annotation on the key data point

---

## 7. Do's and Don'ts

### Do

- Put ONE metric per slide — the audience should get it in 2 seconds
- Make key numbers 80pt+ in YC Orange
- Use white space aggressively — empty space creates focus
- Keep to exactly 10 slides for 2-minute pitch
- Make the Traction slide the star of the deck
- Use real numbers, not projections

### Don't

- Add logos, watermarks, or slide numbers
- Use any color besides orange for accents
- Put more than 3 bullet points on any slide
- Add animations, transitions, or builds
- Use stock photos, illustrations, or icons
- Include a "Thank you" slide — end with your ask or contact

---

## 8. Agent Guide

When generating slides with the Y Combinator Demo Day design system:

```
You are creating a YC Demo Day pitch deck using the Y Combinator Demo Day design system.
Key rules:
- 10 slides, 2 minutes. Every slide earns its place or gets cut.
- ONE metric per slide. Key numbers are 80pt+ in YC Orange (#F26522).
- Inter is the only font. White is the only background.
- Zero decoration: no icons, no borders, no gradients, no shadows.
- Traction slide is the most important — lead with real numbers.
- Team slide: headshots + name + one-line credential. That's it.
- The Ask slide: "Raising $X" in giant orange. Use of funds in 2 lines.
- Speed over beauty. Clarity over cleverness.

Refer to the full DESIGN.md for exact hex values, typography specs, and slide sequence.
```
