# Google I/O — Slide Design System

> Material Design keynote — colorful, playful, developer-friendly tech presentations.

---

## 1. Overview

- **Style**: Material Design Keynote
- **Mood**: Optimistic, accessible, technical-yet-approachable
- **Audience**: Developers, product teams, tech community
- **Aspect Ratio**: 16:9 (13.33in x 7.5in)

### Design Philosophy

Bold color pops on a clean white canvas. The four Google colors (Blue, Red, Yellow, Green) work as an accent system — never competing, always supporting. Generous whitespace gives content room to breathe. Code is a first-class citizen, rendered with syntax highlighting and monospace type. Rounded corners and soft surfaces reflect Material Design principles.

---

## 2. Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | white | `#FFFFFF` | Slide background (default) |
| Primary Text | nearBlack | `#202124` | Titles, headings |
| Body Text | body | `#5F6368` | Body copy, descriptions |
| Surface | surface | `#F8F9FA` | Card backgrounds, code blocks |
| Border | border | `#DADCE0` | Subtle borders, dividers |

### Accent Colors (Google Four)

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Blue | blue | `#4285F4` | Primary accent, links, active states |
| Red | red | `#EA4335` | Secondary accent, alerts |
| Yellow | yellow | `#FBBC05` | Highlights, warnings |
| Green | green | `#34A853` | Success, positive metrics |

### Extended Palette

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Blue Light | blueBg | `#E8F0FE` | Blue tinted backgrounds |
| Red Light | redBg | `#FCE8E6` | Red tinted backgrounds |
| Yellow Light | yellowBg | `#FEF7E0` | Yellow tinted backgrounds |
| Green Light | greenBg | `#E6F4EA` | Green tinted backgrounds |

### Color Rules

- Default slide background is always `#FFFFFF`
- Use one accent color per slide as the dominant highlight — avoid mixing all four on one slide
- The four-color system appears together only on the cover slide and brand moments
- Code blocks use `#F8F9FA` surface background with `#202124` text
- Never use accent colors for large background fills — keep them as pops

---

## 3. Typography

| Element | Font | Size | Weight | Color |
|---------|------|------|--------|-------|
| Cover Title | Google Sans | 44pt | Bold | `#202124` |
| Slide Title | Google Sans | 32pt | Bold | `#202124` |
| Subtitle | Google Sans | 18pt | Regular | `#5F6368` |
| Section Heading | Google Sans | 20pt | Medium | `#4285F4` |
| Body | Roboto | 16pt | Regular | `#5F6368` |
| Code Inline | Roboto Mono | 14pt | Regular | `#202124` (on surface) |
| Code Block | Roboto Mono | 13pt | Regular | `#202124` (on surface) |
| Table Header | Roboto | 12pt | Medium | `#202124` |
| Table Cell | Roboto | 12pt | Regular | `#5F6368` |
| Caption / Note | Roboto | 11pt | Regular | `#5F6368` |
| KPI Number | Google Sans | 36pt | Bold | contextual |
| Badge / Tag | Roboto | 11pt | Medium | accent (on accent-bg) |

### Typography Rules

- Google Sans is for display text (titles, headings, KPI numbers) only
- Roboto is the workhorse — body, tables, captions
- Roboto Mono for all code: inline snippets and code blocks
- Max font size: 44pt (cover title). Body stays at 16pt
- Generous line-height: 1.5 for body text, 1.3 for headings

---

## 4. Layout Grid

### Slide Dimensions

- **Width**: 13.33in (33.87cm)
- **Height**: 7.5in (19.05cm)

### Margins & Zones

```
+----------------------------------------------+
|  padding-top: 0.8in                          |
|                                              |
|  margin: 1.0in                               |
|                                              |
|  +- Title -----------------------+ y: 0.8   |
|  +- Subtitle --------------------+ y: 1.4   |
|  +- Content Zone ----------------+ y: 1.8   |
|  |         w: 11.33in           |           |
|  |                               |           |
|  +-------------------------------+ y: 6.5   |
|                                              |
|  [Google logo / event tag]         y: 7.0   |
+----------------------------------------------+
```

### Spacing Rules

- Left/right margin: 1.0in -> content width: 11.33in
- Title top: y=0.8in
- Content start: y=1.8in
- Footer area: y=7.0in
- Component spacing: 0.4in between major elements
- Card padding: 0.3in internal
- Corner radius: 8px for cards, 16px for hero elements

### Two-Column Layout

| Column | x | w |
|--------|---|---|
| Left | 1.0in | 5.37in |
| Right | 6.77in | 5.56in |

---

## 5. Slide Types

### Cover Slide

- White background with four-color accent bar at bottom (4 equal segments)
- Title: centered, 44pt Google Sans Bold, `#202124`
- Subtitle: centered, 18pt Roboto, `#5F6368`
- Event branding: "Google I/O" in Google Sans, with color accents
- Date and location: 14pt Roboto, `#5F6368`

### Section Divider

- White background
- Large section title: left-aligned, 32pt Google Sans Bold
- Accent color underline (4px, 2in wide) in section's assigned color
- Optional icon or product logo

### Content Slide

- Clean white background
- Title: 32pt Google Sans Bold, left-aligned
- Body text or bullet points below
- Optional product screenshot or illustration (right-aligned)
- Generous whitespace around all elements

### Data Slide (Table / Chart)

- Title: 32pt Google Sans Bold
- Table: rounded corners (8px), `#F8F9FA` header background
- No heavy borders — use surface color and spacing to separate
- Charts: Google color palette, rounded bar corners, clean labels

### Code Slide

- Title: 32pt Google Sans Bold
- Code block: `#F8F9FA` background, 16px rounded corners, 0.5in padding
- Syntax highlighting using accent colors
- Optional annotation callouts with colored lines
- Language tag: top-right of code block, 11pt Roboto, `#5F6368`

### KPI / Dashboard Slide

- Title: 32pt Google Sans Bold
- Card row: 3-4 cards with rounded corners (8px)
- Each card: white background, subtle border, large KPI number in accent color
- Card dimensions: ~2.5in wide, ~1.2in tall

### Closing Slide

- White background with four-color accent bar at bottom
- "Thank you" or CTA: 36pt Google Sans Bold
- Links / resources in 16pt Roboto, blue accent
- QR code optional

---

## 6. Component Patterns

### Tables

- Header: `#F8F9FA` background, `#202124` medium-weight text, 12pt
- Cells: 12pt Roboto, no visible borders — use spacing and alternating surfaces
- Row hover-style alternation: white / `#F8F9FA`
- Rounded container corners (8px)

### Cards

- Background: `#FFFFFF` with 1px `#DADCE0` border
- Corner radius: 8px
- Padding: 0.3in
- Optional colored top-bar (4px) using accent color
- Subtle shadow: 0 1px 3px rgba(0,0,0,0.08)

### Code Blocks

- Background: `#F8F9FA`
- Corner radius: 16px
- Padding: 0.5in
- Font: Roboto Mono 13pt
- Syntax colors: blue for keywords, green for strings, red for errors
- Line numbers: `#5F6368` at 50% opacity

### Badges / Tags

- Background: accent-light color (e.g., `#E8F0FE` for blue)
- Text: accent color (e.g., `#4285F4`)
- Corner radius: 4px
- Padding: 4px 12px
- Font: 11pt Roboto Medium

### Four-Color Accent Bar

- Height: 4px
- Four equal segments: Blue, Red, Yellow, Green (left to right)
- Used on cover and closing slides at the bottom

---

## 7. Do's and Don'ts

### Do

- Use generous whitespace — let content breathe
- Show real code examples with syntax highlighting
- Use one accent color as the dominant color per slide
- Apply rounded corners (8-16px) on all contained elements
- Include product screenshots and UI mockups at actual size
- Use the four-color bar sparingly for brand moments

### Don't

- Fill backgrounds with accent colors — keep them as pops on white
- Mix all four accent colors on a single content slide
- Use serif fonts — the system is entirely sans-serif and monospace
- Apply heavy borders or drop shadows
- Use stock photography — prefer illustrations, icons, and screenshots
- Crowd slides — if it doesn't fit with whitespace, split into two slides

---

## 8. Agent Guide

When generating slides with the Google I/O design system:

```
You are creating a developer keynote presentation using the Google I/O slide design system.
Key rules:
- White background always. Accent colors (Blue #4285F4, Red #EA4335, Yellow #FBBC05, Green #34A853) are pops, not fills.
- Google Sans for titles, Roboto for body, Roboto Mono for code.
- Rounded corners on everything: 8px for cards, 16px for code blocks and hero elements.
- Code is a first-class citizen — use syntax-highlighted code blocks with Roboto Mono.
- One dominant accent color per slide. The four-color bar is for cover/closing only.
- Generous whitespace. If a slide feels crowded, split it.
- Target 15-25 slides for a keynote: Cover -> Agenda -> Problem/Opportunity -> Demo slides -> Code examples -> Metrics -> Closing.

Refer to the full DESIGN.md for exact hex values, typography specs, and component patterns.
```
