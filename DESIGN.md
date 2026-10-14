---
name: BudgetJar
colors:
  surface: '#faf9fb'
  surface-dim: '#dbd9dc'
  surface-bright: '#faf9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f6'
  surface-container: '#efedf0'
  surface-container-high: '#e9e7ea'
  surface-container-highest: '#e3e2e4'
  on-surface: '#1b1c1e'
  on-surface-variant: '#404942'
  inverse-surface: '#303032'
  inverse-on-surface: '#f2f0f3'
  outline: '#707971'
  outline-variant: '#bfc9bf'
  surface-tint: '#246b46'
  primary: '#004226'
  on-primary: '#ffffff'
  primary-container: '#0f5b38'
  on-primary-container: '#8ad1a4'
  inverse-primary: '#8fd6a9'
  secondary: '#a0401c'
  on-secondary: '#ffffff'
  secondary-container: '#fe875d'
  on-secondary-container: '#722200'
  tertiary: '#2d394a'
  on-tertiary: '#ffffff'
  tertiary-container: '#445062'
  on-tertiary-container: '#b6c2d8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#aaf2c4'
  primary-fixed-dim: '#8fd6a9'
  on-primary-fixed: '#002110'
  on-primary-fixed-variant: '#005230'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59c'
  on-secondary-fixed: '#390c00'
  on-secondary-fixed-variant: '#802a05'
  tertiary-fixed: '#d7e3f9'
  tertiary-fixed-dim: '#bbc7dd'
  on-tertiary-fixed: '#101c2c'
  on-tertiary-fixed-variant: '#3c4759'
  background: '#faf9fb'
  on-background: '#1b1c1e'
  surface-variant: '#e3e2e4'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 3.5rem
    fontWeight: '400'
    lineHeight: 4rem
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 2.25rem
    fontWeight: '400'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  display-md:
    fontFamily: Newsreader
    fontSize: 2.5rem
    fontWeight: '400'
    lineHeight: 3rem
    letterSpacing: -0.025em
  display-md-mobile:
    fontFamily: Newsreader
    fontSize: 1.75rem
    fontWeight: '400'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 2rem
    fontWeight: '500'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
  tabular-lg:
    fontFamily: Geist
    fontSize: 2rem
    fontWeight: '500'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  tabular-md:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '500'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  label-md:
    fontFamily: Geist
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Geist
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system crafts an environment of quiet financial confidence. Rather than leaning into gamified widgets, neon crypto gradients, or sterile banking dashboards, it takes inspiration from modern editorial volumes (*Kinfolk*, *Cereal*) and precision engineering interfaces (*Linear*, *Apple* hardware launches). 

### Personality & Tone
- **Composed & Grounded:** Relieves financial anxiety through deliberate whitespace, organic ivory tones, and an unhurried visual cadence.
- **Editorial Distinction:** Pairings of literary serif displays with high-density tabular data project intellectual maturity and financial craft.
- **Quiet Luxury:** Sophistication communicated not through ornamental excess, but through translucent materiality, ultra-crisp micro-strokes, and purposeful micro-typography.

### Visual Direction
The interface blends **warm editorial minimalism** with **refined tactile glassmorphism**. Base surfaces mimic fine textured paper or porcelain, layered with frosted optical glass cards featuring inner highlights, delicate single-pixel hairline borders, and mathematically proportioned metric displays.

## Colors

The palette balances foundational warm mineral neutrals with rich botanical and earthy accents to evoke sustainable growth, transparency, and grounded control.

### Color Architecture
- **Primary (`#0F5B38`):** Deep Forest Green. Anchors primary calls to action, committed balance targets, and key monetary progressions. Accompanied by `#18794E` for interactive states and `#E6F4EA` for soft contextual fills.
- **Secondary (`#D96B43`):** Warm Terracotta. Used selectively for variable budgeting, target warnings, non-critical burn rates, and celebratory milestones. Accompanied by `#FAECE6` for tinted containers.
- **Tertiary (`#5E6A7D`):** Muted Slate Lavender. Handles tertiary categorizations, secondary analytical timelines, and contextual metadata. Paired with `#EEF2F6`.
- **Neutral (`#151618`):** Deep Charcoal. Prevents harsh digital contrast against off-white grounds while retaining optical crispness. Secondary body text utilizes `#2A2C30` and tertiary captions use `#5C6068`.
- **Backgrounds & Surfaces:**
  - `Canvas Default`: `#FBF9F5` (Soft warm porcelain)
  - `Canvas Muted`: `#F5F2EB` (Sun-bleached linen)
  - `Canvas Border / Hairline`: `rgba(21, 22, 24, 0.06)`
  - `Glass Overlay`: `rgba(251, 249, 245, 0.72)` with matching border highlights

## Typography

The type system creates an intentional dialogue between human narrative (*Newsreader*), clean communicative prose (*Plus Jakarta Sans*), and numerical discipline (*Geist*).

### Typographic Roles
- **Editorial Headlines (`Newsreader`):** Applied with italic accents for emotional financial anchors (e.g., *Savings Intentions*, *Monthly Horizons*). Rendered with optical sizing enabled (`font-optical-sizing: auto`).
- **Interface & Content Body (`Plus Jakarta Sans`):** Neutral, readable, and ergonomically balanced at small body scales.
- **Financial Balances & Labels (`Geist`):** Monospaced numeric tables ensure all currency columns and micro-metrics align vertically without jitter. Micro-labels always use uppercase styling paired with tracked letter spacing.

## Layout & Spacing

A 12-column dynamic grid anchors desktop experiences, collapsing to a single-column stacked hierarchy on mobile devices.

### Layout Rhythm
- **Rhythm Principle:** Consistent 8px baseline unit (`0.5rem`). Generous vertical spacing (`space-xl` and above) surrounds high-level portfolio snapshots to create a sense of breathing room.
- **Breakpoints:**
  - `Mobile`: `< 768px` (4-column flow, 20px outer margin, sticky bottom glass shelf)
  - `Tablet`: `768px – 1024px` (8-column flow, 32px outer margin)
  - `Desktop`: `> 1024px` (12-column flow, max-width 1240px, 48px outer margin)
- **Container Structure:** Nested split views ensure financial ledgers remain aligned alongside contextual summary cards without horizontal overflow.

## Elevation & Depth

Visual hierarchy uses frosted optical depth and stacked porcelain layers instead of heavy black drop shadows.

### Elevation Tiers
1. **Canvas Level (Base):** Flat porcelain tint `#FBF9F5`. No shadow.
2. **Glass Container (Level 1):** Translucent background `rgba(251, 249, 245, 0.75)` with `backdrop-filter: blur(16px)`. Border is a crisp `1px solid rgba(21, 22, 24, 0.06)`. Accompanied by an ambient feather shadow: `0 4px 20px -2px rgba(21, 22, 24, 0.03)`.
3. **Interactive Floating Card (Level 2):** Layered sheet `rgba(255, 255, 255, 0.88)` with `backdrop-filter: blur(24px)`, subtle top inner stroke `inset 0 1px 0 rgba(255, 255, 255, 0.8)`, and directional shadow `0 12px 32px -4px rgba(21, 22, 24, 0.05)`.
4. **Modals & Flyouts (Level 3):** Frosted porcelain backdrop shield `rgba(21, 22, 24, 0.15)` paired with elevated content containers having `0 24px 48px -12px rgba(21, 22, 24, 0.08)`.

## Shapes

Corner radiuses follow geometric discipline calibrated between organic warmth and structured precision.

- **Primary Surfaces & Cards:** `1rem` (16px) standard; `1.25rem` (20px) on large dashboard feature modules.
- **Interactive Controls (Inputs, Buttons):** `0.75rem` (12px) to provide defined tactile affordance.
- **Status Tags & Micro-pills:** Fully rounded pill structure for categorical markers and jar allocation chips.

## Components

### Buttons
- **Primary Action:** Background `#0F5B38`, text `#FFFFFF`, radius `12px`. Hover state shifts to `#18794E` with an inner top highlight `inset 0 1px 0 rgba(255, 255, 255, 0.18)`.
- **Secondary Action:** Translucent porcelain background `rgba(21, 22, 24, 0.04)`, text `#151618`, border `1px solid rgba(21, 22, 24, 0.06)`. Hover state transitions background to `rgba(21, 22, 24, 0.07)`.
- **Ghost/Tertiary:** No background, text `#5C6068`, hover text `#151618` with subtle underline animation.

### Cards & Financial "Jars"
- **Jar Container:** Frosted surface with soft linear fill bar at the bottom edge indicating budget exhaustion. Border is `1px solid rgba(21, 22, 24, 0.06)`.
- **Header:** Features an expressive italic category title (`Newsreader`, medium) next to a compact uppercase budget status label (`Geist`).
- **Metric Row:** Emphasized tabular font (`Geist`, tabular-lg) highlighting current balance against target limit in muted tones.

### Input Fields
- **Default State:** Background `rgba(255, 255, 255, 0.65)`, border `1px solid rgba(21, 22, 24, 0.10)`, text `#151618`, placeholder `#5C6068`.
- **Focus State:** Background `#FFFFFF`, border `1px solid #0F5B38`, paired with a non-intrusive glow ring `0 0 0 3px rgba(15, 91, 56, 0.12)`.
- **Currency Inputs:** Prefixed with static monospaced currency symbols anchored in place while numeric characters enter in tabular format.

### Chips & Badges
- **Category Chips:** Light background matching category tone (`#E6F4EA` for savings, `#FAECE6` for living expenses, `#EEF2F6` for student transit/academic bills), paired with corresponding darkened text. Uppercase typography (`label-sm`).
- **Interactive Filter Chips:** Bordered capsule with `1px solid rgba(21, 22, 24, 0.08)`, transitioning to solid `#151618` with inverted white text upon selection.

### Lists & Ledger Rows
- **Transaction Line:** Minimal border-bottom `1px solid rgba(21, 22, 24, 0.04)`. Left slot contains high-contrast iconography in a soft circular container; center displays transaction entity and category; right slot displays right-aligned monospaced amounts with clear negative (`-`) or credit (`+`) markers.
- **Hover Feedback:** Smooth background transition to `rgba(21, 22, 24, 0.02)`.

### Checkboxes & Segmented Controls
- **Checkboxes:** Rounded squares (6px radius), `1.25rem` dimensions. Checked state fills `#0F5B38` with an off-white inner check icon.
- **Segmented Timeframe Selector:** Contained within a frosted pill bar; active index card slides smoothly using physical spring timing with an ivory-tinted surface and ambient micro-shadow.