# Startup Pitch — Slide Design System

> Modern gradient, investor-facing — clean and confident pitch decks for fundraising and partnerships.

---

## 1. Overview

- **Style**: Modern Pitch
- **Mood**: Confident, clean, forward-looking
- **Audience**: Investors, VCs, potential partners
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Clean white canvas with strategic pops of gradient color. Every slide must answer one question. Data tells the story — wrap metrics in context. Confidence through simplicity, not complexity. Designed to look great both on-screen and as a PDF leave-behind.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background |
| Alt Background | offWhite | `#F8F9FC` | Section/card backgrounds |
| Primary Text | dark | `#1A1A2E` | Headlines, body |
| Body Text | text | `#4A4A68` | Body copy |
| Muted Text | muted | `#9393A8` | Captions, labels |
| Border | border | `#E5E7F0` | Dividers, card borders |

### Accent Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Primary | indigo | `#6366F1` | CTAs, highlights, active states |
| Gradient Start | gradientA | `#6366F1` | Hero elements |
| Gradient End | gradientB | `#8B5CF6` | Hero elements |
| Accent Light | indigoBg | `#EEF2FF` | Accent area backgrounds |

### Semantic Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Positive | green | `#10B981` | Revenue growth, traction |
| Negative | red | `#EF4444` | Churn, risk |
| Warning | amber | `#F59E0B` | Caution, milestones |
| Info | blue | `#3B82F6` | Market data, context |

### Color Rules

- White background by default, `#F8F9FC` for card sections
- Gradient (indigo → violet) reserved for cover slide and hero moments only
- Accent (`#6366F1`) for headings, CTA buttons, and chart highlights
- Semantic colors for metrics only — never decorative
- Maximum 2 colors per slide beyond black/white/gray

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Cover Title | Inter / Calibri | 48pt | Bold | `#1A1A2E` |
| Slide Title | Inter / Calibri | 32pt | Bold | `#1A1A2E` |
| Subtitle | Inter / Calibri | 18pt | Regular | `#9393A8` |
| Body | Inter / Calibri | 16pt | Regular | `#4A4A68` |
| Metric Number | Inter / Calibri | 56pt | Bold | `#6366F1` |
| Metric Label | Inter / Calibri | 14pt | Medium | `#9393A8` |
| Table Header | Inter / Calibri | 12pt | SemiBold | `#1A1A2E` |
| Table Cell | Inter / Calibri | 12pt | Regular | `#4A4A68` |
| Caption | Inter / Calibri | 11pt | Regular | `#9393A8` |

### Typography Rules

- Inter is the primary font. Fall back to Calibri on systems without Inter
- One font family only — hierarchy through size and weight
- Titles: Bold. Body: Regular. Never use italic
- Numbers larger than text — metrics are the hero

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
┌──────────────────────────────────────────────┐
│  margin: 1.0in                               │
│                                              │
│  ┌─ Title ─────────────────────────┐ y: 0.8  │
│  └─────────────────────────────────┘         │
│  ┌─ Subtitle ──────────────────────┐ y: 1.4  │
│  └─────────────────────────────────┘         │
│  ┌─ Content Zone ──────────────────┐ y: 2.0  │
│  │         w: 11.33in              │         │
│  │                                 │         │
│  └─────────────────────────────────┘ y: 6.5  │
│               [Page / Logo footer]   y: 6.8  │
└──────────────────────────────────────────────┘
```

### Spacing Rules

- Margins: 1.0in on all sides
- Title to content: 0.6in gap
- Card gap: 0.3in
- Card padding: 0.4in
- Section spacing: 0.5in

### Grid Columns

| Layout | Columns | Gap |
|--------|---------|-----|
| Metrics row | 3-4 equal cards | 0.3in |
| Two-column | 50/50 or 60/40 | 0.4in |
| Three-column | 33/33/33 | 0.3in |

---

## 5. Slide Types

### Cover Slide

- White or subtle gradient background (indigo → violet, 5% opacity)
- Company name/logo: top-left
- Title: 48pt bold, left-aligned or centered
- One-liner: 18pt, muted color
- Optional: founding date, stage badge

### Problem Slide

- Title: "The Problem" or the problem as a statement
- Large quote or stat highlighting the pain point
- Supporting context in body text

### Solution Slide

- Title: "Our Solution" or value proposition as headline
- Visual: product screenshot or diagram
- 3 key benefit cards below

### Traction / Metrics Slide

- 3-4 metric cards in a row
- Large number (56pt, indigo) + label below
- Optional: delta indicator (▲12% in green)

### Market Slide

- TAM/SAM/SOM visualization
- Market size as hero number
- Source citation in caption

### Business Model Slide

- Revenue streams as cards or simple flow diagram
- Pricing tiers in a comparison table

### Team Slide

- Photo circles (or initials) in a grid
- Name: bold, Role: muted, Previous: caption
- 4-6 key team members

### Ask / Closing Slide

- Funding ask as hero number
- Use of funds as simple bar or card breakdown
- Contact info, indigo accent

---

## 6. Component Patterns

### Metric Cards

- Background: `#F8F9FC`
- Border: 1px `#E5E7F0`
- Corner radius: 8px
- Number: 56pt bold indigo, centered
- Label: 14pt muted, centered below
- Delta: small text, green/red, below number

### Tables

- Header: no fill, bold text, bottom border 2px `#E5E7F0`
- Cells: light bottom border 1px `#E5E7F0`
- Clean, no outer border, no row fill
- Alternating rows: optional `#F8F9FC`

### Buttons / CTAs

- Background: `#6366F1` (indigo)
- Text: white, 14pt bold
- Corner radius: 6px
- Padding: 0.15in vertical, 0.4in horizontal
- Use sparingly — max 1 per slide

### Charts

- Primary data: indigo (`#6366F1`)
- Secondary: violet (`#8B5CF6`)
- Tertiary: blue (`#3B82F6`)
- Gridlines: `#E5E7F0`, 0.5pt
- Labels: muted color, 11pt
- No chart border, white background

### Quotes / Callouts

- Left border: 3px indigo
- Background: `#F8F9FC`
- Quote text: 18pt italic, `#4A4A68`
- Attribution: 12pt, muted

---

## 7. Do's and Don'ts

### Do

- One question answered per slide
- Lead with the metric, then provide context
- Use the 3-second rule: the main point should be clear in 3 seconds
- Include source citations for market data
- Design for PDF readability (no animation-dependent slides)
- Keep to 10-15 slides for a seed deck

### Don't

- Use more than 2 accent colors per slide
- Add decorative graphics or abstract shapes
- Put full paragraphs on slides — max 3 lines of body text
- Use dark backgrounds (the deck should feel open and transparent)
- Include confidential financials without marking them
- Skip the team slide — investors invest in people

---

## 8. Agent Guide

When generating slides with the Startup Pitch design system:

```
You are creating an investor pitch deck using the Startup Pitch design system.
Key rules:
- White background. Clean, confident, modern.
- Indigo (#6366F1) is the accent — use for headings, metrics, and CTAs.
- Metrics are heroes: 56pt bold indigo numbers with muted labels.
- One answer per slide. 3-second rule: main point visible instantly.
- Gradient (indigo→violet) only on cover slide.
- Structure: Cover → Problem → Solution → Traction → Market → Model → Team → Ask.
- Max 3 lines of body text per slide. No paragraphs.
- Design for PDF leave-behind: no animation-dependent content.

Refer to the full DESIGN.md for exact hex values, spacing, and component patterns.
```
