# Tech Keynote — Slide Design System

> Dark, bold, Apple-inspired — high-impact keynote presentations for product launches and tech talks.

---

## 1. Overview

- **Style**: Dark Keynote
- **Mood**: Bold, cinematic, high-impact
- **Audience**: Engineers, product teams, conference attendees
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Dark canvas, large typography, one idea per slide. Inspired by Apple keynotes and major tech conferences. Let the content breathe — generous whitespace (darkspace), minimal text, maximum visual impact. Every slide should work as a screenshot.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | dark | `#0A0A0A` | Slide background |
| Alt Background | darkAlt | `#141414` | Card/section backgrounds |
| Primary Text | white | `#FFFFFF` | Headlines, key numbers |
| Body Text | light | `#E0E0E0` | Body text, descriptions |
| Muted Text | muted | `#888888` | Captions, secondary info |
| Dim Text | dim | `#555555` | Subtle labels |
| Border | border | `#2A2A2A` | Subtle dividers |

### Accent Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Primary Accent | blue | `#0A84FF` | CTAs, links, highlights |
| Secondary Accent | purple | `#BF5AF2` | Gradients, secondary emphasis |
| Tertiary | teal | `#64D2FF` | Charts, data viz accent |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#30D158` | Success, growth |
| Negative | red | `#FF453A` | Error, decline |
| Warning | orange | `#FF9F0A` | Caution |

### Color Rules

- Background is always `#0A0A0A` (near-black, not pure black)
- White text for headlines, light gray for body — never pure white for body text
- Accent colors appear sparingly: one highlight per slide maximum
- Gradients allowed only for hero moments (blue → purple, subtle)
- No colored backgrounds on content slides

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Hero Title | SF Pro Display / Arial | 72pt | Bold | `#FFFFFF` |
| Slide Title | SF Pro Display / Arial | 44pt | Bold | `#FFFFFF` |
| Subtitle | SF Pro Display / Arial | 24pt | Regular | `#888888` |
| Body | SF Pro Text / Calibri | 20pt | Regular | `#E0E0E0` |
| Code | SF Mono / Consolas | 18pt | Regular | `#E0E0E0` |
| Caption | SF Pro Text / Calibri | 14pt | Regular | `#888888` |
| KPI Number | SF Pro Display / Arial | 96pt | Bold | `#FFFFFF` |
| KPI Label | SF Pro Text / Calibri | 20pt | Regular | `#888888` |

### Typography Rules

- Go big or go home — minimum readable size is 18pt
- One font weight contrast per slide: Bold headline + Regular body
- Never use more than 3 text elements per slide
- Code blocks use monospace font with subtle dark background (`#141414`)

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
│  │         w: 10.93in                  │     │
│  │                                     │     │
│  │    (center-aligned by default)      │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
│                              margin: 1.2in   │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Generous margins: 1.2in on all sides
- Title-to-body gap: 0.6in
- Element spacing: 0.4in minimum
- Content is center-aligned by default
- Let slides breathe — 40% of slide area should be empty

---

## 5. Slide Types

### Cover Slide

- Dark background
- Hero title: centered, 72pt bold white
- Subtitle: centered, 24pt muted
- Optional: subtle gradient line or accent dot

### Section Divider

- Single word or short phrase: centered, 44pt bold white
- Optional muted subtitle below

### Content Slide (Statement)

- One sentence or short paragraph: centered, 44pt bold
- Supporting text below: 20pt, light gray
- No bullet points — rewrite as statements

### Data Slide (Big Number)

- KPI number: centered, 96pt bold white
- Label below: 20pt muted
- Optional: small delta indicator (green/red, 18pt)

### Demo / Screenshot Slide

- Full-bleed or centered screenshot with subtle rounded corners
- Minimal text — let the visual speak

### Code Slide

- Dark card (`#141414`) with code in monospace
- Syntax highlighting with accent colors
- Title above the code block

### Closing Slide

- Key message or CTA: centered, 44pt bold
- URL or handle: 20pt, accent color

---

## 6. Component Patterns

### Cards

- Background: `#141414`
- Border: 1px `#2A2A2A` (optional)
- Corner radius: 12px
- Padding: 0.4in
- No shadow

### Code Blocks

- Background: `#141414`
- Font: SF Mono / Consolas, 18pt
- Padding: 0.3in
- Corner radius: 8px

### Charts

- Use accent palette: blue, purple, teal
- White axis labels
- No gridlines — minimal chart chrome
- Dark background, no chart border

### Progress / Timeline

- Horizontal dots or line
- Active step: accent blue
- Completed: white
- Upcoming: `#555555`

---

## 7. Do's and Don'ts

### Do

- One idea per slide — if it needs a bullet list, split into multiple slides
- Use massive typography for key messages
- Let 40%+ of each slide be empty dark space
- Use screenshots and visuals at full width when possible
- Animate reveals (one element at a time) if presenting live

### Don't

- Use bullet points — rewrite as full statements or split slides
- Put more than 3 text elements on one slide
- Use light/white backgrounds
- Add logos on every slide (cover and closing only)
- Use clip art, stock icons, or decorative borders
- Mix more than 2 accent colors per slide

---

## 8. Agent Guide

When generating slides with the Tech Keynote design system:

```
You are creating a tech keynote presentation using the Tech Keynote design system.
Key rules:
- Dark background (#0A0A0A) always. Near-black, not pure black.
- One idea per slide. No bullet points — rewrite as statements.
- Typography is the design: 72pt for heroes, 44pt for titles, 96pt for big numbers.
- Maximum 3 text elements per slide. 40%+ of slide should be empty space.
- Accent colors (#0A84FF blue, #BF5AF2 purple) used sparingly — one highlight per slide.
- Code slides use monospace on #141414 background.
- No logos on content slides (cover and closing only).

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
