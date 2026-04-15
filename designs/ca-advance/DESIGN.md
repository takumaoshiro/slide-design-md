# CA ADVANCE — Slide Design System

> Minimal BtoB — white-base, professional, information-dense corporate reporting slides.

---

## 1. Overview

- **Style**: Minimal BtoB
- **Mood**: Professional, restrained, executive-ready
- **Audience**: Executives, division heads, corporate stakeholders
- **Aspect Ratio**: 16:9 (10in x 5.63in)

### Design Philosophy

White canvas with monochrome typography. Color is earned — used only where it carries meaning (status, metrics, section identity). Information density over decoration. "The less color, the more refined."

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background (always) |
| Primary Text | black | `#1A1A1A` | Titles, headings |
| Body Text | text | `#333333` | Body copy, table cells |
| Subtitle | sub | `#666666` | Subtitles, descriptions |
| Muted Text | muted | `#999999` | Page numbers, captions, notes |
| Border | border | `#D0D0D0` | Table borders, separators |
| Section BG | lightBg | `#F5F5F5` | Card backgrounds, aside areas |
| Accent | accent | `#1B4F8A` | Section headings, table headers, key numbers |
| Accent Light | accentLight | `#E8EFF7` | Accent area backgrounds |

### Semantic Colors

| Role | Name | Hex | BG Hex | Usage |
|------|------|-----|--------|-------|
| Positive | green | `#2E7D32` | `#E8F5E9` | Growth, success, completion |
| Negative | red | `#C62828` | `#FFEBEE` | Decline, risk, alert |
| Warning | amber | `#E65100` | `#FFF3E0` | In-progress, caution |

### Color Rules

- Slide background is always `#FFFFFF`
- Only table headers get accent fill (`#1B4F8A`) with white text
- Color in body text is reserved for meaningful data (status, delta values)
- No decorative color fills — "less color = more refined"
- Every slide has a thin accent line at the top (h: 0.035in, full width)

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Slide Title | Arial Black | 22pt | Bold | `#1A1A1A` |
| Cover Title | Arial Black | 36pt | Bold | `#1A1A1A` |
| Subtitle | Calibri | 11pt | Regular | `#666666` |
| Section Heading | Calibri | 12pt | Bold | `#1B4F8A` |
| Body | Calibri | 10-11pt | Regular | `#333333` |
| Table Header | Calibri | 9-10pt | Bold | `#FFFFFF` (on accent) |
| Table Cell | Calibri | 9-10pt | Regular | `#333333` |
| Caption / Note | Calibri | 8-9pt | Regular | `#999999` |
| KPI Number | Calibri | 22pt | Bold | contextual |
| Logo Text | Calibri | 8pt | Regular | `#999999` |

### Typography Rules

- Arial Black is **only** for slide titles. Everything else uses Calibri
- Max font size: 36pt (cover title only). Body stays within 10-11pt
- Bold is reserved for headings, headers, and emphasized numbers — never in body text

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 10in (25.4cm)
- **Height**: 5.63in (14.29cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│ [Accent Line]                    h: 0.035in  │
├──────────────────────────────────────────────┤
│  margin: 0.7in                               │
│                                              │
│  ┌─ Title ─────────────────────────┐ y: 0.3  │
│  └─────────────────────────────────┘         │
│  ┌─ Subtitle ──────────────────────┐ y: 0.8  │
│  └─────────────────────────────────┘         │
│  ─── separator line ─────────────── y: 1.05  │
│  ┌─ Content Zone ──────────────────┐ y: 1.1  │
│  │         w: 8.6in                │         │
│  │                                 │         │
│  └─────────────────────────────────┘ y: 5.2  │
│               [Footer: "CA ADVANCE"] y: 5.15 │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Left/right margin: 0.7in → content width: 8.6in
- Title top: y=0.3in
- Content start: y=1.1in (below separator)
- Footer: y=5.15in, right-aligned
- Card internal padding: 0.2in
- Minimum element gap: 0.15in

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 0.7in | 4.0in |
| Right | 5.2in | 4.1in |

---

## 5. Slide Types

### Cover Slide

- White background with thin accent line at top
- Title: centered, 36pt Arial Black
- Subtitle: centered, 24pt Calibri, `#666666`
- Decorative separator: centered, 2in wide, accent color, 1.5pt
- Date & recipient: centered, 12pt, `#999999`
- Logo: "CA ADVANCE" centered, 14pt, accent, bold

### Section Divider

- White background, accent line at top
- Section title: left-aligned, 22pt Arial Black
- Optional subtitle below

### Content Slide

- Standard header (accent line + title + separator)
- Content zone below separator (y: 1.1 to 5.2)
- Left-accent-bar cards for structured information
- Footer: "CA ADVANCE" right-aligned

### Data Slide (Table / KPI)

- Header row: accent fill + white text
- Cell borders: 0.5pt, `#D0D0D0`
- Row height: 0.28-0.35in
- KPI cards: colored background with large number + label

### KPI / Dashboard Slide

- Horizontal card row (up to 5 cards)
- Each card: semantic background color, 22pt bold number, 10pt label
- Card width: ~1.55in, height: ~0.85in

### Closing Slide

- Summary + action table format
- Background context + next steps

---

## 6. Component Patterns

### Tables

- Header: accent (`#1B4F8A`) fill, white bold text, 9-10pt
- Cells: 9-10pt Calibri, `#D0D0D0` borders at 0.5pt
- No row striping — clean white rows

### Cards / Callout Boxes

- Background: `#F5F5F5`
- Left accent bar: 0.04in wide, semantic color
- No corner radius (sharp corners only)
- No shadows

### Status Badges

| Status | Color |
|--------|-------|
| Complete / Up | `#2E7D32` |
| In Progress | `#1B4F8A` or `#E65100` |
| Waiting | `#E65100` |
| Next Phase | `#999999` |
| Risk / Down | `#C62828` |

---

## 7. Do's and Don'ts

### Do

- Use white background and let information structure create visual hierarchy
- Organize with tables, cards, and KPI highlights
- Apply color only where it carries meaning (status, delta, section heading)
- Include header structure on every slide (accent line + title + separator)
- Place "CA ADVANCE" footer consistently
- Aim for 1 message per slide

### Don't

- Use dark backgrounds (navy, black)
- Add icons, decorative shapes, gradients, or shadows
- Use large colored fills or bands
- Overuse bold or vary font sizes randomly
- Use rounded rectangles
- Add automatic page numbers (use "CA ADVANCE" text only)

---

## 8. Agent Guide

When generating slides with the CA ADVANCE design system:

```
You are creating a corporate report presentation using the CA ADVANCE design system.
Key rules:
- White background always. Color is only for meaning (status, metrics, headings).
- Accent color #1B4F8A for section headings and table headers only.
- Arial Black for titles, Calibri for everything else.
- Every slide gets: thin accent line (top), title, separator line, "CA ADVANCE" footer.
- No decorative elements: no icons, no gradients, no shadows, no rounded corners.
- Target 5 slides for executive reports: Cover → Context → Data → Plan → Summary.
- Information density over decoration. "Less color = more refined."

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
