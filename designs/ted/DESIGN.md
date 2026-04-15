# TED — Slide Design System

> Speaker-focused presentation — red accent, high contrast, one idea per slide. Passionate, clear, story-driven.

---

## 1. Overview

- **Style**: Speaker-focused Keynote
- **Mood**: Passionate, clear, story-driven
- **Audience**: Conference attendees, general public, thought leaders
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Dark canvas with maximum contrast. Every slide serves a single idea — if it needs a bullet list, it needs more slides. Photography and bold typography do the heavy lifting; the speaker's voice fills in the rest. TED Red is earned — used only for emphasis and identity.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | black | `#000000` | Primary slide background |
| Dark BG | dark | `#1A1A1A` | Alternate slide background |
| Primary Text | white | `#FFFFFF` | Headlines, key text on dark |
| Accent | tedRed | `#E62B1E` | Brand accent, emphasis, speaker identity |
| Muted Text | lightGray | `#CCCCCC` | Supporting text, attributions |
| Secondary | muted | `#888888` | Captions, page indicators |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Emphasis | tedRed | `#E62B1E` | Key word highlight, underline accent |
| De-emphasis | muted | `#888888` | Secondary information |
| Contrast | white | `#FFFFFF` | Primary readable text on dark |

### Color Rules

- Slide background is always dark (`#000000` or `#1A1A1A`) — never white
- TED Red (`#E62B1E`) is reserved for the accent bar, speaker name, and single-word emphasis
- Body text on dark backgrounds uses `#FFFFFF` or `#CCCCCC` — never gray below `#AAAAAA`
- No gradients, no decorative color fills — the image and the word do the work
- Full-bleed photography uses a dark overlay (40-60% black) for text legibility

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Hero Headline | Helvetica Neue | 72pt+ | Bold | `#FFFFFF` |
| Slide Title | Helvetica Neue | 48pt | Bold | `#FFFFFF` |
| Speaker Name | Helvetica Neue | 28pt | Bold | `#E62B1E` |
| Topic Line | Helvetica Neue | 24pt | Light | `#CCCCCC` |
| Body | Helvetica Neue | 28pt | Light | `#FFFFFF` |
| Quote Text | Helvetica Neue | 36pt | Light Italic | `#FFFFFF` |
| Attribution | Helvetica Neue | 18pt | Light | `#888888` |
| Caption / Note | Helvetica Neue | 14pt | Light | `#888888` |
| Data Number | Helvetica Neue | 96pt | Bold | `#FFFFFF` or `#E62B1E` |

### Typography Rules

- Helvetica Neue Bold for headlines and impact moments only
- Helvetica Neue Light for everything else — clarity through weight contrast
- Maximum 2 lines of text per slide — if you need more, split into multiple slides
- No bullet points ever — each idea gets its own slide
- Data numbers are oversized (96pt+) to create visual anchors

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [TED Red accent bar]             h: 0.06in   │
├──────────────────────────────────────────────┤
│                                              │
│  margin: 1.0in                               │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │      w: 11.33in  h: 5.5in          │     │
│  │  (centered, single idea)            │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                                              │
│                        [TED logo]   y: 7.1in │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Content is centered both horizontally and vertically by default
- Left-aligned text anchors at x: 1.0in for narrative slides
- Minimum margin: 1.0in on all sides
- Photography bleeds to all edges (full-bleed)
- Text over photography: 40-60% black overlay required

### Speaker Intro Layout

| Element | Position |
|---------|----------|
| Speaker Name | Center, y: 40% |
| Topic Line | Center, y: 55% |
| TED Logo | Bottom-center, y: 90% |

---

## 5. Slide Types

### Cover Slide (Speaker Intro)

- Black background with TED Red accent bar at top
- Speaker name: centered, 28pt Bold, TED Red
- Topic line: centered below, 24pt Light, `#CCCCCC`
- Optional: TED logo bottom-center, small

### Big Idea Slide

- Dark background (`#000000` or `#1A1A1A`)
- Single headline: centered, 48-72pt Bold, white
- Maximum 6-8 words — the "tweetable moment"
- No subtext, no supporting copy

### Story / Narrative Slide

- Full-bleed photography with dark overlay
- 1-2 lines of text, left or center aligned
- 28pt Light white text over image
- High emotional impact imagery

### Data Slide (Single Stat)

- Dark background
- One number: centered, 96pt Bold, white or TED Red
- One label line: 24pt Light, `#CCCCCC`
- No tables, no charts — just the number that matters

### Quote Slide

- Dark background
- Quote: centered, 36pt Light Italic, white
- Attribution: below, 18pt Light, `#888888`
- Optional: thin TED Red line above attribution

### Closing Slide

- Black background
- "Thank you" or call-to-action: centered, 48pt Bold, white
- Speaker handle/URL: 24pt Light, `#888888`

---

## 6. Component Patterns

### Photography

- Always full-bleed (edge to edge)
- Dark overlay: linear gradient or solid 40-60% black
- High contrast, emotionally resonant imagery
- No clip-art, no icons, no stock-photo feel

### Accent Bar

- Position: top of every slide
- Height: 0.06in (4px at screen resolution)
- Color: TED Red (`#E62B1E`)
- Full width, no gaps

### Data Display

- Single number per slide, oversized (96pt+)
- Context label below in light weight
- Comparison: use two slides in sequence, not side-by-side
- No charts — narrate the data, show only the punchline

### Text Emphasis

- Bold a single word in TED Red for emphasis
- Never bold entire sentences
- Italic reserved for quotes only

---

## 7. Do's and Don'ts

### Do

- One idea per slide — ruthlessly simple
- Use full-bleed photography with dark overlays
- Let the speaker's voice carry the narrative
- Use TED Red sparingly for maximum impact
- Make data human: "1 in 5 people" not "20%"
- Keep text to 2 lines maximum

### Don't

- Use bullet points — ever
- Use white or light backgrounds
- Add logos, watermarks, or decorative elements
- Use clip-art, icons, or illustration
- Put more than one number on a data slide
- Use tables or multi-column layouts
- Add transitions or animations in the design

---

## 8. Agent Guide

When generating slides with the TED design system:

```
You are creating a TED-style speaker presentation using the TED slide design system.
Key rules:
- Dark background always (#000000 or #1A1A1A). Never white.
- One idea per slide. Maximum 2 lines of text. No bullet points ever.
- TED Red #E62B1E for accent bar, speaker name, and single-word emphasis only.
- Helvetica Neue Bold for headlines, Light for everything else.
- Full-bleed photography with 40-60% dark overlay for text legibility.
- Data slides: one big number (96pt+) with one label. No tables, no charts.
- Every slide gets a thin TED Red accent bar at the top.
- Target structure: Speaker Intro → Story slides → Big Idea → Data → Story → Closing.
- "If a slide needs bullet points, it needs more slides."

Refer to the full DESIGN.md for color values, typography specs, and layout details.
```
