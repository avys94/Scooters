---
name: Taller Urbano Precision
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#e4beba'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#ab8986'
  outline-variant: '#5b403e'
  surface-tint: '#ffb3ad'
  primary: '#ffb3ad'
  on-primary: '#68000a'
  primary-container: '#ff5451'
  on-primary-container: '#5c0008'
  inverse-primary: '#b91a24'
  secondary: '#c8c6c9'
  on-secondary: '#303033'
  secondary-container: '#47464a'
  on-secondary-container: '#b6b4b8'
  tertiary: '#69d8d4'
  on-tertiary: '#003736'
  tertiary-container: '#24a09d'
  on-tertiary-container: '#00302e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#930013'
  secondary-fixed: '#e4e1e5'
  secondary-fixed-dim: '#c8c6c9'
  on-secondary-fixed: '#1b1b1e'
  on-secondary-fixed-variant: '#47464a'
  tertiary-fixed: '#87f4f0'
  tertiary-fixed-dim: '#69d8d4'
  on-tertiary-fixed: '#00201f'
  on-tertiary-fixed-variant: '#00504e'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 4rem
    fontWeight: '700'
    lineHeight: '1.05'
    letterSpacing: -0.04em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 2.75rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: '1.15'
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 1.875rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.45'
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.06em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: '1'
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
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system is engineered for an electric scooter workshop in Málaga, Spain. It balances high-velocity conversion with technical authority and master craftsmanship. The aesthetic merges technical precision with an aggressive urban edge: pure black canvases, mechanical surfaces, and high-impact racing red accents.

The target audience consists of urban commuters, delivery professionals, and performance enthusiasts who depend daily on personal light electric vehicles (PLEVs). The interface communicates urgency, mechanical mastery, and immediate trustworthiness.

### Visual Principles
- **Mechanical Precision:** Visuals mirror CNC-machined components, high-torque electronics, and battery telemetry.
- **Conversion Urgency:** Decisive calls to action, clear service pricing, real-time diagnostic availability, and direct WhatsApp / booking funnels.
- **High-Contrast Legibility:** Zero visual clutter. Deep blacks force high-contrast white technical copy and red interaction targets into sharp focus.
- **Local Grit & Reliability:** Grounded in Málaga's high-density transit context, avoiding generic startup tropes in favor of an industrial workshop standard.

## Colors

The palette operates in strict dark mode, anchored by deep carbon surfaces and high-intensity signal red.

### Palette Architecture
- **Primary (`#EF4444`):** Pure mechanical alert red. Reserved strictly for primary transactional triggers, emergency repairs, active status badges, and critical interactive nodes. Hover states shift toward hyper-saturated scarlet (`#DC2626`).
- **Secondary (`#27272A`):** Industrial zinc structural tone. Used for component shells, secondary interactive tiles, control tracks, and structural containment.
- **Neutral (`#09090B` & `#000000`):** Pitch black foundation. Surface tiers escalate subtly (`#000000` canvas background, `#0E0E11` card backplate, `#18181B` surface container).
- **Text & Overlays:**
  - `text-primary`: `#FFFFFF` for absolute legibility on dark substrates.
  - `text-secondary`: `#A1A1AA` for technical specifications, meta tags, and passive descriptions.
  - `text-muted`: `#71717A` for legal copy, disabled states, and auxiliary measurements.
  - `border-subtle`: `rgba(255, 255, 255, 0.08)` for razor-thin division without visual weight.
  - `border-strong`: `rgba(255, 255, 255, 0.16)` for active hover boundaries and structural frame borders.

## Typography

The type system pairs **Space Grotesk** for headlines, metric callouts, and technical badges with **Inter** for long-form diagnostic copy, guarantee terms, and form labels.

### Rules of Usage
- **All-Caps Accents:** All `label-*` and micro-badges use uppercase with deliberate positive letter-spacing (`0.06em` to `0.1em`) to mimic stamped serial numbers and industrial equipment labeling.
- **Tight Headings:** High-level titles must maintain negative tracking to feel solid, commanding, and punchy.
- **Numbers as Telemetry:** Quantitative data (e.g., "15 Min", "€29", "4.9★", "2.400+ Patinetes") utilizes Space Grotesk tabular figures for strict horizontal balance in pricing cards and comparison grids.

## Layout & Spacing

The layout leverages a disciplined 12-column grid on desktop (`max-width: 1280px`), adapting to a 6-column system on tablet and a single-column stacked layout on mobile.

### Structure & Density
- **Section Rhythm:** Major landing sections separate across `space-3xl` (96px) on desktop and `space-2xl` (64px) on mobile to produce defined breaks between conversion arguments (Hero -> Direct Booking -> Problem Breakdown -> Pricing -> Reviews -> FAQ).
- **Tight Component Packing:** Interactive modules and diagnostic selectors favor dense, high-efficiency vertical spacing (`space-sm` to `space-md`) to ensure critical pricing and timeframes remain above the fold on mobile viewports.
- **Full-Width Canvas Bleed:** Background containers utilize deep contrast bands spanning 100vw, while inner content binds cleanly to grid margins.

## Elevation & Depth

This system avoids soft diffuse shadows or decorative blurs, adopting a mechanical, architectural approach to depth through dark tonal layering and razor-sharp border boundaries.

### Tonal Tiers
1. **Tier 0 (Base Canvas):** `#000000` (Pure Obsidian). Used for document backdrop, hero headers, and full-bleed transitions.
2. **Tier 1 (Surface Rest):** `#0A0A0C` with a crisp `1px solid rgba(255, 255, 255, 0.08)` perimeter border. Used for static service cards and workshop specifications.
3. **Tier 2 (Interactive & Elevated):** `#131316` with `1px solid rgba(255, 255, 255, 0.14)`. Used for dynamic booking modules, diagnostic filters, and floating WhatsApp navigation bars.
4. **Active Trigger Lift:** When hovered or focused, high-intent targets omit heavy blur in favor of a precision border state: `1px solid #EF4444` paired with a directional, dense red halo: `0 0 16px -2px rgba(239, 68, 68, 0.35)`.

## Shapes

The design language uses deliberate micro-radii to project engineering rigor and physical toughness.

### Form Treatment
- **Micro Radius (0.25rem / 4px):** Applied to primary and secondary buttons, input controls, chips, and telemetry badges. Delivers a crisp, modern corner that avoids both retro brutality and generic SaaS softness.
- **Card Radius (0.5rem / 8px):** Structural containers, pricing tables, and diagnostic selector tiles.
- **Zero Radius:** Raw data grids, comparison tables, and terminal-style alert strips retain hard right angles (`0px`) to underline uncompromising utility.

## Components

### Buttons & High-Velocity CTAs
- **Primary CTA:** Background `#EF4444`, text `#FFFFFF`, font `Space Grotesk` 600, uppercase, `letter-spacing: 0.05em`. Radius `0.25rem`. Padding: `0.875rem 1.75rem`. Hover shifts to `#DC2626` with a direct box-shadow: `0 0 20px rgba(239, 68, 68, 0.4)`.
- **Secondary Action:** Background `#18181B`, border `1px solid rgba(255, 255, 255, 0.15)`, text `#FFFFFF`. Hover elevates border to `rgba(255, 255, 255, 0.4)`.
- **WhatsApp Direct Dispatch:** Background `#25D366` with high-contrast `#000000` typography, fixed at bottom-right on mobile viewports for instant one-tap messaging.

### Diagnostic & Service Cards
- Backplate: `#0E0E11` with `1px solid rgba(255, 255, 255, 0.08)`. Radius: `0.5rem`.
- Padding: `1.5rem`.
- Title: `Space Grotesk` 600 in `#FFFFFF`.
- Subtitle & Specs: `Inter` 400 in `#A1A1AA`.
- Price & Turnaround Badge: Inline badge with Space Grotesk tabular figures (e.g., `DESDE 25€` / `EN 30 MIN`) highlighted in `#EF4444`.

### Chips & Filter Tags
- Height: `32px`. Radius: `0.25rem`.
- Inactive: `#18181B` surface, `#A1A1AA` text, `1px solid rgba(255, 255, 255, 0.06)`.
- Active: `#EF4444` background, `#FFFFFF` bold text, no border. Used for scooter models (Xiaomi, Cecotec, Dualtron, SmartGyro) and symptom triage (Frenos, Pinchazos, Batería, Centralita).

### Form Controls & Booking Inputs
- Height: `48px`. Surface: `#09090B`. Border: `1px solid rgba(255, 255, 255, 0.12)`.
- Text: `#FFFFFF`, placeholder `#52525B`. Radius: `0.25rem`.
- Focus state: Border transitions instantly to `#EF4444`, outline `none`.

### Radio & Checkbox Selectors
- Outer frame: `20px x 20px`, surface `#09090B`, border `1px solid rgba(255, 255, 255, 0.2)`. Radius `0.125rem` (checkbox) or circular (radio).
- Checked: Fill `#EF4444` with a centered sharp white glyph or bullet.

### Trust & Proof Banners
- Linear horizontal strip, full width, surface `#070708`, borders top and bottom `1px solid rgba(255, 255, 255, 0.06)`.
- Features real Google Review star ratings (`★ 4.9`), guarantee terms ("Garantía 6 meses por escrito"), and Málaga geographic anchor ("Taller oficial en Calle Carretería / Centro").