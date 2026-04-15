# Nike — Slide Design System

> Bold athletic — black/white contrast, dynamic energy, brand storytelling for creative directors.

---

## 1. Overview

- **Style**: Bold Athletic
- **Mood**: Bold, dynamic, aspirational
- **Audience**: Brand teams, marketing, creative directors
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Pure contrast. Black canvas, white type, nothing between. Every slide hits like a billboard — one message, maximum impact. Photography does the storytelling; typography does the commanding. Color is earned: Nike Volt appears only when it must. "If it doesn't move you, remove it."

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | black | `#000000` | Slide background (always) |
| Primary Text | white | `#FFFFFF` | Headlines, body copy |
| Accent | volt | `#CCFF00` | Rare highlight — CTAs, key stats only |
| Surface Dark | darkGray | `#1A1A1A` | Card backgrounds, secondary surfaces |
| Muted Text | midGray | `#767676` | Captions, footnotes, metadata |
| Surface Light | lightGray | `#F5F5F5` | Inverted slides (rare), table alt rows |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | volt | `#CCFF00` | Growth, wins, personal bests |
| Negative | white | `#FFFFFF` | Decline shown via white text + context |
| Highlight | volt | `#CCFF00` | Single emphasized metric or CTA |

### Color Rules

- Slide background is always `#000000` — no exceptions
- Body text is always `#FFFFFF` on black
- Nike Volt `#CCFF00` is used for maximum 1 element per slide (a number, a word, a line)
- No gradients, no transparency, no color fills
- If a slide needs a lighter feel, use `#1A1A1A` surface — never white backgrounds
- Semantic meaning through typography weight and scale, not color variation

---

## 3. Typography

| Element | Font | Size | Weight | Color | Transform |
|---------|------|------|--------|-------|-----------|
| Hero Headline | Futura / Arial Black | 80-120pt | Black (900) | `#FFFFFF` | UPPERCASE |
| Slide Title | Futura / Arial Black | 48-60pt | Bold (700) | `#FFFFFF` | UPPERCASE |
| Subtitle | Helvetica Neue / Arial | 24pt | Light (300) | `#767676` | Sentence case |
| Body | Helvetica Neue / Arial | 16-18pt | Regular (400) | `#FFFFFF` | Sentence case |
| Table Header | Helvetica Neue / Arial | 14pt | Bold (700) | `#000000` (on volt) | UPPERCASE |
| Table Cell | Helvetica Neue / Arial | 14pt | Regular (400) | `#FFFFFF` | Sentence case |
| Caption / Note | Helvetica Neue / Arial | 11pt | Regular (400) | `#767676` | Sentence case |
| KPI Number | Futura / Arial Black | 72pt | Black (900) | `#CCFF00` | — |
| KPI Label | Helvetica Neue / Arial | 14pt | Light (300) | `#FFFFFF` | UPPERCASE |

### Typography Rules

- Headlines are ALWAYS uppercase — no exceptions
- Futura / Arial Black is only for headlines and KPI numbers
- Hero headlines can go up to 120pt — oversized type is intentional
- Body text never exceeds 18pt; subtlety in body, power in headlines
- Letter-spacing on headlines: +2% to +5% for breathing room
- Light weight (300) for supporting text creates contrast with heavy headlines

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│                                              │
│  margin: 0.8in                               │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │         w: 11.73in                  │     │
│  │                                     │     │
│  │                                     │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
│                       [Swoosh / Logo] bottom │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Left/right margin: 0.8in minimum — content width: 11.73in
- Full-bleed imagery: edge to edge, no margins
- Text over image: minimum 60% black overlay or solid black region
- Title-to-content gap: 0.5in
- Element gap: 0.3in minimum
- Logo/Swoosh: bottom-right corner, 0.5in from edges

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left (Image) | 0in (bleed) | 6.67in (50%) |
| Right (Text) | 7.0in | 5.53in |

---

## 5. Slide Types

### Cover Slide

- Full black background
- Hero headline: centered, 80-120pt, UPPERCASE, white
- Optional: full-bleed athlete/product photo with text overlay
- Swoosh logo: bottom-center or bottom-right, white
- No subtitle clutter — one line maximum

### Section Divider

- Black background
- Single word or short phrase: 60-80pt, UPPERCASE, white
- Positioned left-aligned or centered
- Vast negative space around text

### Content Slide (Text + Visual)

- Split layout: image left (50%), text right (50%)
- Or: full-bleed image with text overlay on dark region
- Body text: 16-18pt, left-aligned, max 3-4 lines
- Hard geometric crop on images — no rounded corners

### Data Slide (Table / Chart)

- Black background with white/volt data
- Table header: volt background with black text
- Cell borders: 1px `#1A1A1A` (barely visible)
- Key metric highlighted in volt
- Minimal grid lines — data speaks for itself

### KPI / Dashboard Slide

- Horizontal row of 3-4 KPI cards
- Each: large number (72pt, volt), label below (14pt, white, uppercase)
- Cards on `#1A1A1A` surface, separated by black gaps
- One hero KPI can be scaled 1.5x larger than others

### Closing Slide

- Full black, centered Swoosh or "JUST DO IT" tagline
- Optional: single CTA line in volt
- Maximum restraint — end with impact, not information

---

## 6. Component Patterns

### Tables

- Header: volt (`#CCFF00`) fill, black bold text, uppercase, 14pt
- Cells: white text on black, `#1A1A1A` borders at 1px
- No row striping — clean black rows
- Key column or value highlighted in volt

### Cards / Callout Boxes

- Background: `#1A1A1A`
- No border radius (sharp corners only)
- No shadows, no borders
- Internal padding: 0.4in
- Volt left-edge accent line (optional, 3px)

### Charts

- White lines/bars on black background
- Volt for the primary/highlighted data series
- Axis labels in `#767676`, 11pt
- No gridlines — minimal axis lines only

### Photography

- Full-bleed, edge-to-edge
- High contrast, dramatic lighting
- Athletes/products in motion preferred
- Hard geometric crops — no rounded masks
- When text overlays: ensure 60%+ of text area is dark

---

## 7. Do's and Don'ts

### Do

- Use pure black `#000000` backgrounds on every slide
- Make headlines massive (80pt+) and UPPERCASE
- Let photography and white space carry the story
- Use Nike Volt sparingly — max 1 accent element per slide
- Maintain hard geometric edges and sharp corners everywhere
- Think billboard: one message, maximum impact

### Don't

- Use white, gray, or colored backgrounds
- Add gradients, shadows, glows, or transparency effects
- Use rounded corners on anything
- Put more than 4-5 lines of body text on a slide
- Use decorative icons, clip art, or illustrations
- Mix multiple accent colors — volt is the only accent
- Use lowercase headlines

---

## 8. Agent Guide

When generating slides with the Nike design system:

```
You are creating a bold brand presentation using the Nike slide design system.
Key rules:
- Black #000000 background always. White #FFFFFF text only.
- Nike Volt #CCFF00 for max 1 accent element per slide (a number, a word, a line).
- ALL CAPS headlines in Futura/Arial Black at 80pt+. Oversized is intentional.
- Helvetica Neue/Arial for body at 16-18pt, light weight for subtitles.
- Full-bleed photography with hard geometric crops. No rounded corners anywhere.
- No gradients, no shadows, no decorative elements. Maximum contrast, minimum clutter.
- Think billboard: 1 message per slide, vast negative space, dramatic impact.

Refer to the full DESIGN.md for exact hex values, typography specs, and layout details.
```
