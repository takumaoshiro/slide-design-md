# Muji — Slide Design System

> Ultra minimal — natural tones, zen simplicity, maximum whitespace for design-conscious teams.

---

## 1. Overview

- **Style**: Ultra Minimal
- **Mood**: Calm, honest, understated
- **Audience**: Design teams, brand strategists, product managers
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Emptiness as expression. The slide is not filled — it breathes. Content floats in vast whitespace on warm natural tones. Color is almost absent; the Muji red-brown appears only as a whisper — a thin rule, a single word. Typography is featherweight. "The best design is the least design."

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | warmWhite | `#FAF8F5` | Slide background (always) |
| Primary Text | darkBrown | `#3C3126` | Titles, headings |
| Body Text | body | `#5C5347` | Body copy, descriptions |
| Muted Text | muted | `#9E9790` | Captions, page numbers, metadata |
| Accent | brownRed | `#B92C28` | Used extremely sparingly — one element max |
| Border | border | `#E5E0DA` | Hairline separators, table borders |
| Surface | beige | `#F0EDE8` | Card backgrounds, subtle sections |
| Surface Light | lightBeige | `#F5F3F0` | Hover states, secondary surfaces |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | darkBrown | `#3C3126` | Expressed through context, not color |
| Negative | brownRed | `#B92C28` | Decline, risk — used with restraint |
| Neutral | muted | `#9E9790` | Unchanged, stable metrics |

### Color Rules

- Slide background is always warm white `#FAF8F5` — never cold/pure white
- Muji Brown-Red `#B92C28` appears on maximum 1 element per slide
- No bright colors, no saturated tones — everything is muted and earthy
- Semantic meaning conveyed through typography and context, not color coding
- No colored fills, no colored backgrounds on cards (use `#F0EDE8` beige only)
- Borders are hairline (0.5px) in `#E5E0DA` — barely visible

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Slide Title | Noto Sans JP / Helvetica Neue | 28pt | Light (300) | `#3C3126` |
| Cover Title | Noto Sans JP / Helvetica Neue | 36pt | Light (300) | `#3C3126` |
| Subtitle | Noto Sans JP / Helvetica Neue | 14pt | Light (300) | `#9E9790` |
| Section Heading | Noto Sans JP / Helvetica Neue | 18pt | Regular (400) | `#3C3126` |
| Body | Noto Sans JP / Helvetica Neue | 12pt | Light (300) | `#5C5347` |
| Table Header | Noto Sans JP / Helvetica Neue | 10pt | Regular (400) | `#3C3126` |
| Table Cell | Noto Sans JP / Helvetica Neue | 10pt | Light (300) | `#5C5347` |
| Caption / Note | Noto Sans JP / Helvetica Neue | 9pt | Light (300) | `#9E9790` |
| KPI Number | Noto Sans JP / Helvetica Neue | 36pt | Light (300) | `#3C3126` |
| KPI Label | Noto Sans JP / Helvetica Neue | 10pt | Light (300) | `#9E9790` |

### Typography Rules

- Default weight is Light (300) — Regular (400) is the heaviest used
- Bold (700) is never used — emphasis through size difference and spacing, not weight
- One typeface family only: Noto Sans JP with Helvetica Neue fallback
- Generous line-height: 1.8 for body, 1.4 for headings
- Letter-spacing: +1% on all text for openness
- Titles are sentence case or lowercase — never uppercase

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│                                              │
│  margin: 1.5in (top/bottom)                  │
│  margin: 1.2in (left/right)                  │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │         w: 10.93in                  │     │
│  │                                     │     │
│  │   60%+ of this area is whitespace   │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
│                                              │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Margins are intentionally large: 1.2in sides, 1.5in top/bottom
- Content occupies less than 40% of slide area — whitespace is the design
- Title-to-content gap: 0.6in minimum
- Element gap: 0.4in minimum
- Hairline separator: 0.5px, `#E5E0DA`, used sparingly
- No decorative lines, no accent bars, no visual noise

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 1.2in | 4.8in |
| Gap | — | 1.33in (generous) |
| Right | 7.33in | 4.8in |

---

## 5. Slide Types

### Cover Slide

- Warm white `#FAF8F5` background
- Title: centered, 36pt, Light weight, `#3C3126`
- Subtitle: centered, 14pt, Light, `#9E9790`, generous spacing below title
- Optional: single hairline rule (0.5px, 2in wide, `#E5E0DA`)
- Vast empty space above and below — title floats in the center
- No logo, no decorative elements

### Section Divider

- Single word or short phrase, centered
- 28pt, Light weight, `#3C3126`
- 80%+ whitespace — the emptiest slide type
- Optional: tiny page indicator in `#9E9790` at bottom

### Content Slide (Text + Visual)

- Asymmetric layout: text occupies ~35% width, rest is white space or product image
- Product photography: isolated on white/warm background, no busy scenes
- Body text: 12pt, Light, max 3 lines
- Hairline separator between title and body (optional)

### Data Slide (Table / Chart)

- Table borders: hairline `#E5E0DA` only
- Header: `#3C3126` text, regular weight — no colored header fill
- Bottom border on header row slightly heavier (1px vs 0.5px)
- Generous cell padding: 12px vertical minimum
- Key metric in `#B92C28` if emphasis needed (rare)

### KPI / Dashboard Slide

- 3 KPI cards maximum — fewer is better
- Each: large number (36pt, Light, `#3C3126`), label below (10pt, `#9E9790`)
- Cards on `#F0EDE8` beige surface with generous internal padding
- Wide gaps between cards (1in+)
- One KPI can use `#B92C28` for the number if critical

### Closing Slide

- Nearly empty: warm white background
- Single line of text centered: "Thank you" or equivalent
- 18pt, Light, `#9E9790`
- Maximum emptiness — end with calm, not clutter

---

## 6. Component Patterns

### Tables

- Header: `#3C3126` text, Regular weight, no background fill
- Header bottom border: 1px `#E5E0DA`
- Cell borders: 0.5px `#E5E0DA` (bottom only)
- Cell text: Light weight, `#5C5347`
- Generous row height: 0.45in minimum
- No row striping — clean warm white rows

### Cards / Callout Boxes

- Background: `#F0EDE8` (beige)
- No border, no shadow, no accent bar
- No corner radius (sharp corners)
- Internal padding: 0.5in — generous breathing room
- Content sparse: title + 1-2 lines maximum

### Charts

- Line weight: 1px, `#3C3126` for primary series
- `#B92C28` for highlighted series (use once only)
- `#9E9790` for secondary series
- No gridlines, minimal axis — just the data line and labels
- Labels in `#9E9790`, 9pt

### Photography

- Product isolated on warm white or warm neutral background
- Vast negative space around product (product occupies < 40% of image area)
- Natural materials: wood, cotton, paper, earth
- No lifestyle clutter, no busy compositions
- Muted, natural color grading — no post-processing drama

---

## 7. Do's and Don'ts

### Do

- Maintain 60%+ whitespace on every slide
- Use Light (300) weight as the default for all text
- Let negative space communicate sophistication
- Use warm white `#FAF8F5` background consistently
- Keep content sparse: fewer words, more breathing room
- Show products in isolation with generous empty space

### Don't

- Use bold or heavy font weights — Light (300) is the heaviest typical weight
- Add decorative elements: icons, shapes, patterns, illustrations
- Use bright or saturated colors — everything stays earthy and muted
- Fill more than 40% of any slide with content
- Use shadows, gradients, or visual effects of any kind
- Use cold/pure white `#FFFFFF` as background — always warm white `#FAF8F5`
- Use uppercase text — sentence case or lowercase only

---

## 8. Agent Guide

When generating slides with the Muji design system:

```
You are creating an ultra-minimal presentation using the Muji slide design system.
Key rules:
- Warm white #FAF8F5 background always — never cold white #FFFFFF.
- Light (300) font weight for nearly everything. Bold is never used.
- Noto Sans JP / Helvetica Neue only. Sentence case, never uppercase.
- 60%+ whitespace per slide — emptiness is the design.
- Muji Brown-Red #B92C28 for max 1 element per slide, used extremely sparingly.
- No shadows, no gradients, no decorative elements, no icons.
- Hairline borders (0.5px, #E5E0DA) only. No colored fills on table headers.
- Think zen: fewer words, more space, natural calm.

Refer to the full DESIGN.md for exact hex values, typography specs, and layout details.
```
