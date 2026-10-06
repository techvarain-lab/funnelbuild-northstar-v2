---
name: Executive Advisory System
colors:
  surface: '#121318'
  surface-dim: '#121318'
  surface-bright: '#38393f'
  surface-container-lowest: '#0d0e13'
  surface-container-low: '#1a1b21'
  surface-container: '#1e1f25'
  surface-container-high: '#292a2f'
  surface-container-highest: '#34343a'
  on-surface: '#e3e1e9'
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e3e1e9'
  inverse-on-surface: '#2f3036'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffffff'
  on-tertiary: '#2b303e'
  tertiary-container: '#dee2f4'
  on-tertiary-container: '#5f6473'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#dee2f4'
  tertiary-fixed-dim: '#c2c6d8'
  on-tertiary-fixed: '#161b28'
  on-tertiary-fixed-variant: '#424655'
  background: '#121318'
  on-background: '#e3e1e9'
  surface-variant: '#34343a'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Inter
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  metric-xl:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: -0.03em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-level executive advisory and institutional consulting: disciplined, uncompromising, and commanding. The aesthetic reflects absolute clarity, institutional stability, and senior discretion. Designed for C-suite operators, private equity partners, and enterprise founders, the visual tone eliminates ornamental excess in favor of razor-sharp typographic discipline, deep spatial rhythm, and architectural layout precision.

The design movement is **Architectural Corporate Minimalism** set on an obsidian baseline. Visual weight is managed via nuanced tonal layering—obsidian deep black foundations, slate-charcoal structural tiers, and precise micro-borders—delivering an atmosphere akin to private boardrooms and high-stakes strategy terminals. Pure white CTAs function as razor-sharp focal anchors, while micro-accents of emerald signal vitality and active operational readiness.

## Colors

The palette relies on absolute obsidian depths paired with cold structural slates and high-contrast typographic hierarchy.

- **Base Canvas (`#090A0F` / `#0D0E12`)**: The foundational void. Clean, matte obsidian ground with zero saturation artifacts, creating extreme visual contrast for typography.
- **Structural Surfaces (`#14161C` / `#1A1D24` / `#222630`)**: Graduated container levels that construct depth through luminance rather than chromatic distraction.
- **Borders & Rules (`#2A2E39` / `#333846`)**: Subdued structural boundaries at 1px thickness to anchor spatial boundaries and data grids cleanly.
- **Typography Matrix**: Stark pure white (`#FFFFFF`) for primary titles, headline figures, and active metrics; cool refined slate (`#94A3B8`) for explanatory prose and analysis; deep muted steel (`#64748B`) for metadata, legalese, and tabular headers.
- **Primary Accent (`#FFFFFF`)**: Pure light used as a focal tool for primary direct-response triggers and intake actions.
- **System Indicator (`#10B981`)**: Dedicated emerald reserved strictly for verified status pings, operational availability dots, and affirmative audit checks.
- **Critical Muted Red (`#EF4444` at low opacity)**: Reserved solely for non-qualifying criteria and exclusionary notes.

## Typography

Typography delivers institutional authority via precise proportions, cold geometric cadence, and negative letter spacing across display scales. 

Headlines utilize aggressive negative tracking (`-0.03em` to `-0.04em`) paired with heavy font weights to create dense, impactful editorial headers. Numerical metrics utilize tabular figures (`font-variant-numeric: tabular-nums`) to ensure absolute vertical alignment across multi-column executive scorecards, audit metrics, and timeline deliverables. Labels and status indicators use uppercase styling with positive letter spacing (`0.06em` to `0.1em`) to maintain sharp legibility at micro scales.

## Layout & Spacing

The layout is rooted in a disciplined 12-column desktop grid with a maximum content boundary of `1280px`. The grid condenses to 6 columns on tablet devices (`768px - 1023px`) and 4 columns on mobile viewports (`<768px`).

Outer canvas rhythm leverages generous vertical section padding (`space-xl` scaled up to `6rem` - `8rem` on desktop displays) to provide breathing room fitting for executive review. Information density remains compact inside analytical cards and tabular zones, preventing excessive page heights. Horizontal alignment is anchored across structural 1px dividing borders.

## Elevation & Depth

Depth is established strictly through tonal layering and low-contrast borders; ambient drop shadows are minimized to avoid decorative clutter.

1. **Surface 0 (Ground Canvas)**: `#090A0F`, seamless, non-reflective base.
2. **Surface 1 (Structural Modules & Cards)**: `#14161C`, framed with a precise `1px solid #2A2E39` perimeter outline.
3. **Surface 2 (Elevated Panels & Inset Inputs)**: `#1A1D24` to `#222630`, accented with `1px solid #333846`.
4. **Hero Vignettes & Spatial Ambient Glow**: Subtle radial focal vignettes beneath key data displays using `#FFFFFF` at `2%` to `4%` opacity with `120px` blur, producing an architectural lens effect rather than a fuzzy drop shadow.

## Shapes

The geometric framework is grounded, precise, and disciplined. 

Structural containers, analysis grids, and pillar cards utilize clean 8px (`rounded-lg`) to 12px (`rounded-xl`) outer corner radiuses, striking a balance between modern product design and architectural permanence. Action controls, buttons, and status indicator pills leverage fully rounded geometries (`9999px`) or tight 6px corners (`rounded-md`) to clearly differentiate interactive triggers from fixed content containers.

## Components

### Action Buttons
- **Primary CTA**: Solid `#FFFFFF` fill with `#090A0F` text, bold `Inter` 14px, pill-shaped (`rounded-full`) or 6px (`rounded-md`), with zero border. On hover, shifts to `#E2E8F0` with a subtle transform state.
- **Secondary / Discrete Trigger**: Semi-transparent `#1A1D24` surface, `1px solid #333846` border, `#FFFFFF` text. On hover, background shifts to `#222630` with border brightening to `#475569`.

### Trust Proof & Statistical Counters
- Constructed inside 4-column balanced grid units.
- Heavy numerical display (`metric-xl`, `#FFFFFF`) over structured uppercase sublabels (`label-md`, `#94A3B8`).
- Integrated vertical dividing rules (`1px solid #2A2E39`) separate data points cleanly.

### Advisory Pillar Cards
- Surface: `#14161C` background with `1px solid #2A2E39` perimeter border.
- Header contains an institutional sequence counter (`01`, `02`, `03` in `#64748B` tabular font) paired with a bold 20px `#FFFFFF` pillar title.
- Content zone utilizes `#94A3B8` for strategic objectives and deliverables.

### Qualifying Criteria Matrix (Dual-Card Framework)
- **Positive Matrix ("This Engagement Is For You")**: Grounded in `#14161C`, framed in subtle slate with an emerald status indicator. Checkmark icons rendered in `#10B981` with clean white body items.
- **Disqualification Matrix ("This Is NOT For You")**: Subtle contrast background `#101216`, faint muted border, list items muted down to `#64748B` with subtle crossed indicators.

### Intake Form Modules
- **Field Elements**: Input surfaces set to `#0D0E12` with `1px solid #2A2E39` border, inset horizontal padding of `1.25rem`. Text appears crisp `#FFFFFF` with `#64748B` placeholders.
- **Focus State**: Clean, direct border brightening to `#FFFFFF` without heavy outer halo rings.
- **Form Submissions**: Full-width high-contrast white button to anchor the intake funnel.

### Status Badges & Indicators
- Compact pills with dark `#1A1D24` fill and subtle `1px solid #333846`.
- Contains a live 6px pulsing emerald (`#10B981`) circular badge dot positioned left of the text for availability or confidential status announcements.