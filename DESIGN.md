---
name: Crisis Response & Relief Operations
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#59413a'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#8d7169'
  outline-variant: '#e1bfb6'
  surface-tint: '#ad3203'
  primary: '#a52e00'
  on-primary: '#ffffff'
  primary-container: '#c84518'
  on-primary-container: '#fff5f3'
  inverse-primary: '#ffb59f'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#004ecf'
  on-tertiary: '#ffffff'
  tertiary-container: '#2c68f0'
  on-tertiary-container: '#f8f7ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59f'
  on-primary-fixed: '#3a0a00'
  on-primary-fixed-variant: '#852400'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
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
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
  data-metric:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 28px
    letterSpacing: -0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for life-critical disaster relief, tactical aid coordination, and field operations under adverse conditions. The aesthetic fuses **Tactical Utilitarianism** with **Modern Institutional Command**. It rejects decorative flourishes, focusing on zero latency, instantaneous visual parsing, high contrast under direct sunlight or low-power field displays, and uncompromising operational clarity.

The visual tone is authoritative, compassionate, and dependable. It communicates stability in chaotic environments. Information is presented through structured grid telemetry, strict semantic color mapping, dense inventory modules, and unambiguous operational status signifiers.

## Colors

The palette is anchored by high-visibility hazard cues balanced against grounded slate tones to prevent cognitive fatigue while ensuring high-urgency callouts remain prominent.

- **Primary Alert & Action (`#C84518` / Signal Safety Rust-Amber):** Deployed for high-urgency alerts, SOS dispatches, critical triage markers, and primary system commitments.
- **Secondary Command Navy (`#0F172A` / Slate Navy):** Provides high-contrast anchor chrome, operational navigation bars, and primary data typography.
- **Tertiary Dispatch Blue (`#2563EB`):** Applied to logistical movements, live convoy tracking, transport coordination, and communicative links.
- **Neutral Structure (`#475569` with `#F8FAFC` base):** Surfaces use structured, low-glare slate tiers (`#F8FAFC`, `#F1F5F9`, `#E2E8F0`, `#CBD5E1`) paired with high-contrast text shades (`#0F172A`, `#334155`) to guarantee WCAG AAA legibility.
- **Operational Status Indicators:**
  - Critical / Immediate Hazard: Crimson `#DC2626`
  - High Attention / Depleting Stock: Signal Amber `#EA580C`
  - Stable / Resource Verified: Forest Emerald `#16A34A`
  - Logistical En Route / In Progress: Telemetry Sky `#0284C7`

## Typography

Inter serves as the universal typeface across all viewports and data densities. Its tall x-height, neutral aperture, and robust tabular numeric features ensure zero ambiguity when reading mission-critical quantities (such as rations, medical supplies, and bed counts). 

All telemetry counters, operational metrics, and resource quotas must enable `font-feature-settings: "tnum"` (tabular figures) to prevent jitter during dynamic updates. Tactical micro-labels and triage indicators utilize uppercase transformation with expanded letter-spacing (`0.05em`) to ensure legibility on low-resolution hardware.

## Layout & Spacing

The layout utilizes a structured 12-column responsive grid system optimized for information density:
- **Desktop (1200px+):** 12 columns, 1rem gutters, 1.5rem exterior frame margins. Allows split-screen viewports between live map tactical views and camp capacity data tables.
- **Tablet (768px - 1199px):** 8 columns, 1rem gutters, 1.25rem margins. Collapses multi-pane sidebars into sliding bottom drawers.
- **Mobile (Field Devices < 768px):** 4 columns, 0.75rem gutters, 1rem margins. Full-width touch targets, single-column inventory cards, and stacked incident streams.

Component internals rely on compact padding intervals (`space-xs` through `space-md`) to ensure high density without visual clutter, prioritizing data visibility on single-screen operations.

## Elevation & Depth

Visual hierarchy is communicated via clean tonal separation and low-contrast borders rather than diffuse, decorative drop shadows. In emergency environments, diffuse shadows reduce contrast on degraded screens.

- **Level 0 (Base canvas):** Flat `#F8FAFC` foundation.
- **Level 1 (Cards, metric panels, inventory grids):** Solid `#FFFFFF` fill with a crisp 1px border in `#CBD5E1`.
- **Level 2 (Active selections, pinned camp summaries):** Solid `#FFFFFF` fill with a 1px border in `#94A3B8` and a precise, compact shadow: `0 1px 3px rgba(15, 23, 42, 0.08)`.
- **Level 3 (Command headers, alert banners):** Solid fill with high contrast (e.g., `#0F172A` or `#C84518`) with a sharp bottom boundary border.
- **Level 4 (Disaster modals, dispatch drawers):** Solid white surface overlaying an 80% opacity `#0F172A` backdrop scrim, framed with an elevated border shadow: `0 10px 25px -5px rgba(15, 23, 42, 0.25)`.

## Shapes

The design system enforces a **Soft** geometry (`0.25rem` / 4px base border radius) with specific architectural tiers:
- **Base (Inputs, buttons, list rows, status badges):** `0.25rem` (4px).
- **Cards & Data Modules:** `rounded-lg` (`0.5rem` / 8px).
- **Modals & Command Drawers:** `rounded-xl` (`0.75rem` / 12px).

Rounded geometry is kept minimal and structural to convey discipline, industrial durability, and efficiency. Pill shapes are strictly prohibited except for micro pulse notification dots.

## Components

### Buttons & Quick Actions
- **Primary Action (SOS, Commit Dispatch):** Background `#C84518`, text `#FFFFFF`, font weight 600. Hover `#B03B13`. Active press feedback `#943210`. Focus ring: 2px offset with 2px solid `#C84518`.
- **Secondary Command:** Background `#0F172A`, text `#FFFFFF`. Hover `#1E293B`.
- **Outline / Neutral:** Background `#FFFFFF`, 1px solid `#CBD5E1`, text `#334155`. Hover `#F1F5F9`.
- **Minimum Target:** Field device tap boundaries must never be smaller than 44px vertical height.

### Status Badges & Resource Indicators
- **High Criticality / Depleted:** Background `#FEE2E2`, text `#991B1B`, border 1px solid `#FCA5A5`. Prefix with solid red indicator dot.
- **Warning / Low Reserves:** Background `#FFEDD5`, text `#9A3412`, border 1px solid `#FDBA74`.
- **Optimal / Operating:** Background `#DCFCE7`, text `#166534`, border 1px solid `#86EFAC`.
- **Dispatched / In Route:** Background `#E0F2FE`, text `#075985`, border 1px solid `#7DD3FC`.

### Resource & Camp Counter Cards
- Metric cards feature a dedicated 4px left-hand border color-coded to status.
- Primary numerical values use `data-metric` with tabular numbers.
- Subtitle labels use `label-sm` with text transform uppercase and color `#64748B`.
- Internal dividers use 1px solid `#E2E8F0`.

### Data Grids & Coordination Tables
- Dense row height: 40px for maximum row density.
- Header row: Background `#F1F5F9`, text `#475569`, border-bottom 2px solid `#CBD5E1`.
- Row states: Alternating zebra striping on dense inventory tables (`#FFFFFF` to `#F8FAFC`). Hover states use `#F1F5F9`.

### Input Fields & Emergency Forms
- Border: 1.5px solid `#CBD5E1`, background `#FFFFFF`, text `#0F172A`, border-radius 4px.
- Focus state: Border `#C84518` with 1px outline `#C84518`.
- Urgent/Required field indicators marked with bold rust asterisks.
- Field labels must remain statically visible outside input bounds to prevent context loss in high-stress data entry.