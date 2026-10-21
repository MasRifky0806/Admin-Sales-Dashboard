---
name: Astra OLXmobbi Intelligence
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#444750'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#747781'
  outline-variant: '#c4c6d1'
  surface-tint: '#3f5d9a'
  primary: '#00173e'
  on-primary: '#ffffff'
  primary-container: '#002b66'
  on-primary-container: '#7794d5'
  inverse-primary: '#aec6ff'
  secondary: '#00696b'
  on-secondary: '#ffffff'
  secondary-container: '#7bf5f8'
  on-secondary-container: '#007072'
  tertiary: '#300f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#501f00'
  on-tertiary-container: '#f26e0e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#aec6ff'
  on-primary-fixed: '#001a43'
  on-primary-fixed-variant: '#254581'
  secondary-fixed: '#7bf5f8'
  secondary-fixed-dim: '#5cd8db'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#004f51'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783200'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
  metric-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes a high-performance, executive-grade digital dashboard ecosystem for automotive retail leadership and dealership sales networks. The visual philosophy blends the institutional authority, stability, and corporate heritage of Astra with the agile, digital-first marketplace precision of OLX.

The operational aesthetic is **Corporate / Modern High-Precision**—a synthesis of high-density data legibility, refined structural alignment, and focused technical clarity. The interface projects reliability, liquidity velocity, and transactional confidence. Micro-interactions are immediate and crisp, reducing cognitive friction during high-frequency automotive appraisals, pipeline audits, inventory aging reviews, and regional KPI evaluations.

## Colors

The palette balances institutional grounding with sharp operational cues:

- **Primary (`#002B66` / Deep Astra Blue):** Anchors core chrome, navigation panels, formal KPI headers, and verified dealer endorsement markers.
- **Secondary (`#00A5A8` / OLX Dynamic Cyan-Teal):** Serves as the primary operational accent for interactive controls, digital inventory velocity indicators, active filtering states, and verified digital signatures. Its high-illumination counterpart (`#23E5DB`) is reserved for high-contrast focus rings and target highlights in dense charts.
- **Tertiary (`#F97316` / Automotive Amber-Orange):** Functions as the alerting and performance impulse token—highlighting conversion drop-offs, wholesale auction turnarounds, SLA breaches, and critical inventory aging (60+ days).
- **Neutral (`#0F172A` / Slate 900):** Provides deep, high-legibility typographic contrast against cool slate surfaces (`#F8FAFC` base surface, `#F1F5F9` nested surface containers), avoiding true dead blacks to retain optical softness.

## Typography

The typographic hierarchy pairs **Plus Jakarta Sans** for structural headers and numerical metrics with **Inter** for data tables, form inputs, metadata labels, and system status indicators.

Tabular figures (`font-variant-numeric: tabular-nums`) must be enabled on all metric tokens, table cells, and financial values to ensure vertical numerical alignment across rapid data updates and multi-row sales ledgers.

## Layout & Spacing

The layout is built on an adaptive 12-column fluid grid system pinned inside a max-width bounds of 1600px for large operational screens, dropping to a 4-column layout below 768px.

- **Desktop (1200px+):** 12-column grid, 24px (`1.5rem`) gutters, 32px (`2rem`) margins. Navigation occupies a fixed 260px primary sidebar with a persistent 64px executive header bar.
- **Tablet (768px - 1199px):** 8-column grid, 20px gutters, 24px margins. Navigation collapses to an icon rail (72px) with flyout drawer menus.
- **Mobile (< 768px):** 4-column grid, 16px (`1rem`) gutters, 16px (`1rem`) margins. Metrics stack vertically into single-column priority cards.

## Elevation & Depth

Visual hierarchy uses a refined hybrid of **low-contrast architectural outlines** and **subtle, tinted ambient depth**. Heavy dropshadows are explicitly avoided to preserve clean visual scanning across dense analytical grids.

- **Surface Level 0 (Canvas Base):** `#F8FAFC` (Slate 50). Completely flat, acts as the neutral sheet backdrop.
- **Surface Level 1 (Card/Container):** `#FFFFFF` with a crisp 1px border styled with `rgba(15, 23, 42, 0.08)` and an ambient shadow: `0 1px 3px 0 rgba(0, 43, 102, 0.04), 0 1px 2px -1px rgba(0, 43, 102, 0.02)`.
- **Surface Level 2 (Interactive Floating / Active Filter Hover):** `#FFFFFF` with border `rgba(0, 165, 168, 0.35)` and shadow `0 4px 6px -1px rgba(0, 43, 102, 0.08), 0 2px 4px -2px rgba(0, 43, 102, 0.04)`.
- **Surface Level 3 (Modals / Flyouts / Command Palettes):** `#FFFFFF` with border `rgba(15, 23, 42, 0.12)` and elevation `0 20px 25px -5px rgba(0, 43, 102, 0.12), 0 8px 10px -6px rgba(0, 43, 102, 0.06)`.
- **Astra Corporate Header Bar:** `#002B66` with solid edge definition and no shadow, using an inline bottom stroke of `rgba(255, 255, 255, 0.1)`.

## Shapes

The design system employs a **Soft (`1`)** shape language (`4px` base radius, `8px` container radius, `12px` large surfaces). This maintains an enterprise-grade, clean-edged industrial aesthetic suited for corporate reporting, inspection checklists, and analytical data charts. Full pill radii are strictly reserved for operational status badges and numerical counter tags.

## Components

### Buttons
- **Primary Action (Transactional/Export):** Background `#002B66`, text `#FFFFFF`, border-radius `4px`, padding `8px 16px`. Hover state shifts to `#001D47`. Focus ring uses `#23E5DB` at 2px offset.
- **Secondary Action (Filter/Drilldown):** Background `#FFFFFF`, text `#002B66`, border 1px solid `rgba(0, 43, 102, 0.2)`. Hover background `#F1F5F9`.
- **Accent Action (Instant Bid/Approve):** Background `#00A5A8`, text `#FFFFFF`, font-weight 600. Hover state shifts to `#008B8E`.

### Cards & KPI Tiles
- Built with pure white backgrounds `#FFFFFF`, 1px solid border `#E2E8F0`, and `rounded-lg` (8px).
- Internal layout features a dedicated top utility row (kicker label in `label-sm` uppercase slate, accompanied by an Astra/OLX status icon), a middle metric row featuring `metric-display` in `#0F172A`, and a bottom trend footer showing a delta badge (green for sales growth, tertiary amber `#F97316` for inventory turn slowdowns).

### Input Fields & Select Controls
- Input heights standardized to 36px for dense grid alignment.
- Background `#FFFFFF`, 1px solid `#CBD5E1`, internal text in `body-md` Slate 900. Placeholder color `#94A3B8`.
- Focus state triggers border `#00A5A8` with a 2px outer glow of `rgba(0, 165, 168, 0.15)`.

### Chips & Status Badges
- Height 22px, border-radius `9999px` (pill), horizontal padding `8px`, typography `label-sm`.
- **Dealership Certified:** Background `rgba(0, 43, 102, 0.08)`, text `#002B66`, border 1px solid `rgba(0, 43, 102, 0.16)`.
- **In Inspection:** Background `rgba(0, 165, 168, 0.1)`, text `#007577`.
- **Inventory Over-Age / High Action:** Background `rgba(249, 115, 22, 0.1)`, text `#C2410C`.

### Data Grid & Tables
- Table header row background `#F8FAFC`, bottom border 2px solid `#E2E8F0`, typography `label-sm` in `#64748B`.
- Row height fixed at 44px with 1px border-bottom `#F1F5F9`. Hover state `#F8FAFC`.
- Numeric columns right-aligned with monospace numeric spacing enabled.

### Corporate Endorsement Lockup
- Persistent Astra corporate endorsement displayed alongside OLXmobbi logo marks: "Member of Astra" subtext rendered in `label-sm` tracking `+0.05em` using Deep Astra Blue (`#002B66`) on light surfaces or `#93C5FD` on dark primary nav surfaces.