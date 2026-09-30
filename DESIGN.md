---
name: Vanguard RFM Analytics
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
  on-surface-variant: '#444651'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#37007e'
  on-tertiary: '#ffffff'
  tertiary-container: '#5200b5'
  on-tertiary-container: '#bc9bff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#eaddff'
  tertiary-fixed-dim: '#d2bbff'
  on-tertiary-fixed: '#25005a'
  on-tertiary-fixed-variant: '#5a00c6'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
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
  metric-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  metric-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-precision, executive-grade data environment engineered specifically for retail and e-commerce leaders, growth strategists, and retention engineers. The product personality is authoritative, calm, and analytical, balancing deep data density with instant visual legibility. It conveys total financial accuracy and statistical confidence without feeling sterile or encumbered by legacy enterprise baggage.

The visual style blends **Corporate Modern** with **Technical Precision**. It prioritizes high-clarity data visualization through subtle architectural planes, clean surface separation, meticulous typographic scale, and purposeful segment tagging. The UI instills trust by presenting complex multi-dimensional customer behavioral data (Recency, Frequency, Monetary value) into immediate, actionable intelligence.

## Colors

The palette is engineered around analytical clarity, intentional status coding, and strict contrast ratios:

- **Primary (`#1E3A8A` / Deep Indigo)**: Used for core navigation, master interactive states, authoritative KPI summaries, and structured brand anchors.
- **Secondary (`#10B981` / Emerald Green)**: Represents growth, positive performance deltas, monetary retention velocity, and healthy customer movement across cohorts.
- **Tertiary (`#7C3AED` / Vivid Violet)**: Designates customer intelligence, automated behavioral segmentation, and RFM algorithmic scoring nodes.
- **Neutral Base (`#0F172A` / Slate 900)**: Serves as the high-contrast foundational anchor for headers and numerical figures.

### Surface & Background Tokens
- **Canvas Base**: `#F8FAFC` (Slate 50) provides a soft, low-glare workspace that reduces fatigue during prolonged data exploration.
- **Card / Surface Container**: `#FFFFFF` pure white surfaces define data containers, analytical panels, and interactive cards.
- **Subtle Surface Layers**: `#F1F5F9` (Slate 100) for nested container backgrounds, table headers, and drop zone rests.
- **Border / Divider Tone**: `#E2E8F0` (Slate 200) for crisp structural segregation.

### RFM Cohort Semantic Palette
- **Champions**: Surface `#ECFDF5`, Text/Border `#059669` (Emerald)
- **Loyal Customers**: Surface `#EFF6FF`, Text/Border `#2563EB` (Cobalt)
- **Potential Loyalists**: Surface `#F5F3FF`, Text/Border `#7C3AED` (Purple)
- **At Risk**: Surface `#FFFBEB`, Text/Border `#D97706` (Amber)
- **Hibernating**: Surface `#F8FAFC`, Text/Border `#64748B` (Slate)
- **Lost**: Surface `#FEF2F2`, Text/Border `#DC2626` (Crimson)

## Typography

Typography relies on a deliberate duo of **Plus Jakarta Sans** and **Inter**.

- **Plus Jakarta Sans** provides structural elegance, modern geometric balance, and high-impact clarity across all KPIs, numerical aggregates, matrix axis titles, and dashboard section headers.
- **Inter** handles high-density tabular records, customer transactional records, micro-labels, metadata, and form inputs. Its tabular numbers feature (`tnum`) must be universally applied across all currency figures, counts, and RFM scores to preserve perfect vertical scanning down tabular columns.

Letter spacing is tightened slightly on large display metrics (`-0.02em`) to ensure numerical cohesion, while uppercase badge labels utilize expanded tracking (`+0.04em`) to maintain sharp legibility at micro scales.

## Layout & Spacing

The design system implements a **fluid 12-column layout** pinned to a maximum container width of `1600px`, designed to preserve dense analytics side-by-side with segmentation scatter-plots and cohort distribution maps.

### Breakpoint Matrix
- **Desktop (`≥ 1280px`)**: Full 12-column grid, persistent collapsible analytical sidebar (260px fixed width), `margin: 2rem`, `gutter: 1.5rem`. KPI cards comfortably array in 4-column clusters.
- **Tablet (`768px - 1279px`)**: 8-column layout, drawer-based navigation, `margin: 1.5rem`, `gutter: 1rem`. Data grids and RFM matrices wrap into dual-pane views.
- **Mobile (`< 768px`)**: 4-column layout, bottom-sheet controls, `margin: 1rem`, `gutter: 0.75rem`. Visualizers downscale to stacked horizontal ratio strips with drill-down links.

A strict **4px vertical baseline** governs internal padding and margins. Data cards prioritize compact density, reserving the `space-xl` token for major page orchestrations and structural dashboard divisions.

## Elevation & Depth

Visual hierarchy leverages **tonal surfaces with ambient slate-tinted diffusion** rather than heavy drop shadows, reinforcing a light, institutional dashboard feel:

- **Level 0 (Base Canvas)**: Flat `#F8FAFC`, non-elevated.
- **Level 1 (Card & Metric Standard)**: `#FFFFFF` surface bounded by a crisp 1px outline of `#E2E8F0` coupled with an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Level 2 (Hovered Records & Drag-and-Drop Dropzones Active)**: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Popovers, Filter Drawers, and Segment Tooltips)**: `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.03)`.
- **Level 4 (Modals & File Processing Overlays)**: `0 20px 25px -5px rgba(15, 23, 42, 0.10), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

Borders are mandatory on elevated surfaces to ensure distinct physical edge separation between nested analytical blocks.

## Shapes

The design system standardizes on a **Rounded (`2`)** shape architecture, balancing crisp analytical precision with modern ergonomic comfort:

- Standard structural panels, analytic cards, and modal containers use `rounded-lg` (16px / 1rem) for an approachable dashboard frame.
- Interactive controls (buttons, inputs, select menus, search fields) utilize `rounded` (8px / 0.5rem).
- Small badges, customer RFM score chips, and numerical change pills use `rounded-full` (9999px) to visually contrast against the square architecture of tabular and card grids.

## Components

### 1. Metric Cards (KPI Tiles)
- Built on pure white container with a 1px `#E2E8F0` border.
- Layout order: Top row holds the Metric Label (`label-md`, Slate 500) paired with an contextual icon container (32x32px, rounded-md, soft tinted primary or tertiary background). Middle row contains the Primary KPI Value (`metric-xl`, Plus Jakarta Sans, bold, Slate 900). Bottom row pairs a performance delta badge (e.g., emerald green background `+14.2%` with upward trend arrow) against a benchmark timeframe note ("vs previous 30 days").

### 2. Segment Badges & Chips
- Designed with high readability: 6px vertical, 10px horizontal padding, pill shape (`rounded-full`).
- Includes a 6px circular status dot on the leading edge.
- Example: "Champions" badge features `#ECFDF5` background, `#047857` solid dot, and `#065F46` semibold Inter label.

### 3. Interactive Data Tables
- Header row fixed with `#F8FAFC` background, 1px bottom border `#CBD5E1`, text uppercase `label-sm` in Slate 600.
- Numerical columns (Recency days, Frequency orders, Monetary spending) align strictly right using tabular numerals (`font-feature-settings: 'tnum'`).
- Rows feature subtle hover transitions (`background-color: #F8FAFC` over 150ms) and optional sticky selection checkboxes.

### 4. RFM Segment Visualizer Matrix
- A 5x5 heatmap grid plotting Frequency vs Recency with Monetary value indicated via cell opacity or node diameter.
- Each cell features soft borders with interactive hover states that spotlight customer counts and trigger a floating elevation-3 mini-summary popover.

### 5. Drag-and-Drop Upload Zone
- Border: 2px dashed border using `#CBD5E1`, transitioning to solid 2px `#1E3A8A` on drag-over.
- Background: `#F8FAFC` at rest, transitioning to `#EFF6FF` with a subtle primary color pulse on file drag-hover.
- Iconography: Centered 48px upload cloud icon with badge indicators for `.CSV`, `.XLSX`, and `.XLS`. Supports file validation progress bars with instantaneous parse diagnostics (row count, mapped columns).

### 6. Buttons & Inputs
- **Primary Button**: Solid `#1E3A8A` background, white label, 8px radius, subtle active scale effect (`scale: 0.99`).
- **Secondary Button**: `#FFFFFF` background, 1px `#CBD5E1` border, Slate 700 text, hover brings `#F8FAFC`.
- **Form Fields**: 1px `#CBD5E1` border, `#FFFFFF` interior, 40px height, glowing focus ring `0 0 0 3px rgba(30, 58, 138, 0.12)` with `#1E3A8A` border transition.