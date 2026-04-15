# {Brand Name} — Slide Design System

> {One-line description: style, mood, intended audience}

---

## 1. Overview

- **Style**: {e.g., Minimal BtoB, Dark Keynote, Startup Pitch}
- **Mood**: {e.g., Professional, Bold, Playful}
- **Audience**: {e.g., Executives, Investors, Engineers}
- **Aspect Ratio**: 16:9 ({width} x {height})

### Design Philosophy

{2-3 sentences describing the visual identity and guiding principles}

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background |
| Primary Text | ink | `#1A1A1A` | Titles, headings |
| Body Text | text | `#333333` | Body copy, table cells |
| Muted Text | muted | `#999999` | Captions, page numbers |
| Accent | accent | `#______` | Section headings, highlights |
| Accent Light | accentBg | `#______` | Accent area backgrounds |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#______` | Growth, success, completion |
| Negative | red | `#______` | Decline, risk, alert |
| Warning | amber | `#______` | In-progress, caution |

### Color Rules

- {Rule 1: e.g., "Slide background is always white"}
- {Rule 2: e.g., "Use accent color only for headings and table headers"}
- {Rule 3: e.g., "Avoid decorative color fills"}

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Slide Title | {font} | {size}pt | Bold | ink |
| Subtitle | {font} | {size}pt | Regular | muted |
| Section Heading | {font} | {size}pt | Bold | accent |
| Body | {font} | {size}pt | Regular | text |
| Table Header | {font} | {size}pt | Bold | white (on accent) |
| Table Cell | {font} | {size}pt | Regular | text |
| Caption / Note | {font} | {size}pt | Regular | muted |
| KPI Number | {font} | {size}pt | Bold | contextual |

### Typography Rules

- {Rule 1: e.g., "Max font size is 36pt (cover title only)"}
- {Rule 2: e.g., "Body text stays within 10-11pt"}
- {Rule 3: e.g., "Bold is reserved for headings and emphasized numbers"}

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: {e.g., 13.33in / 33.87cm}
- **Height**: {e.g., 7.5in / 19.05cm}

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [Top Bar / Accent Line]          h: {height} │
├──────────────────────────────────────────────┤
│  margin-left: {val}                          │
│                                              │
│  ┌─ Content Zone ──────────────────────┐     │
│  │                                     │     │
│  │                                     │     │
│  └─────────────────────────────────────┘     │
│                          margin-right: {val} │
├──────────────────────────────────────────────┤
│ [Footer: page number, logo]      h: {height} │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- {Rule 1: e.g., "Title-to-content gap: 0.3in"}
- {Rule 2: e.g., "Card internal padding: 0.2in"}
- {Rule 3: e.g., "Minimum element spacing: 0.15in"}

---

## 5. Slide Types

### Cover Slide

- {Description of cover layout, background treatment, title placement}

### Section Divider

- {Description of section break slides}

### Content Slide (Text + Visual)

- {Standard content layout with text and supporting visual}

### Data Slide (Table / Chart)

- {Layout for data-heavy slides: tables, charts, KPIs}

### KPI / Dashboard Slide

- {Layout for metric cards, scorecards}

### Closing Slide

- {End slide with CTA or thank-you}

---

## 6. Component Patterns

### Tables

- {Header style, row alternation, border rules}

### Cards / Callout Boxes

- {Corner radius, padding, border, shadow}

### Charts

- {Color mapping, label style, legend placement}

### Icons / Badges

- {Size, style, usage guidelines}

---

## 7. Do's and Don'ts

### Do

- {Do 1}
- {Do 2}
- {Do 3}

### Don't

- {Don't 1}
- {Don't 2}
- {Don't 3}

---

## 8. Agent Guide

When generating slides with this design system:

```
You are creating a presentation using the {Brand Name} slide design system.
Key rules:
- {Condensed rule 1}
- {Condensed rule 2}
- {Condensed rule 3}
- {Condensed rule 4}
- {Condensed rule 5}

Refer to the full DESIGN.md for color values, typography specs, and layout details.
```
