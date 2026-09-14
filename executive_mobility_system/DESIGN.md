---
name: Executive Mobility System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-trust, discreet, and refined aesthetic tailored for executive transportation and professional on-demand chauffeur services. The interface blends modern minimalism with tactile, ultra-polished precision: high-contrast dark foundational tones evoke discretion and security, while vibrant jewel-toned functional accents signal verification, safety, and immediacy.

The emotional atmosphere prioritizes absolute calm, control, and reliability. Surfaces are crisp, uncluttered, and structured with clear optical divisions rather than visual noise. Micro-details, such as ultra-fine micro-borders, subtle ambient elevation, and pill-shaped interactive anchors, impart an engineered luxury vehicle cockpit feel.

## Colors

The system employs a disciplined, role-based palette:

- **Obsidian Dark (`#0F172A`)**: The primary structural baseline. Used for high-emphasis text, primary action buttons, dark mode foundational surfaces, and dominant branding anchors.
- **Sapphire Blue (`#2563EB`)**: The interactive dynamic accent. Communicates kinetic actions, primary CTA focus rings, active navigation items, route trajectories, and telematics highlights.
- **Emerald Trust (`#10B981`)**: The certification and status accent. Reserved for driver verification badges, safety ratings, background verification confirmations, and trip status updates.
- **Slate Borders & Micro-lines (`#E2E8F0`)**: Structural dividers and input outlines. Delivers crisp surface definitions without heavy visual weight.
- **Neutral Canvas (`#F8FAFC`) & Pure White (`#FFFFFF`)**: Crisp base canvas and elevated card surfaces, allowing high contrast against text and interactive items.
- **Slate Neutral Text (`#334155`)**: Secondary narrative text, captions, and non-active icons.

## Typography

The type system uses Plus Jakarta Sans across all display, body, and label roles. Its geometric construction and humanist terminals deliver high optical clarity on mobile screens during rapid glance situations.

- **Numerics**: Chauffeur ETA times, price ratings, vehicle license plates, and verification codes require tabular numbers (`font-variant-numeric: tabular-nums`) to prevent horizontal layout shift during dynamic status updates.
- **Hierarchy Rules**: Primary headings utilize negative tracking (`-0.01em` to `-0.02em`) and bold weights to ground the screen. Badges, tags, and micro-labels use uppercase or high-contrast semibold weights with positive tracking (`0.02em` to `0.05em`) for legibility against colored backdrops.

## Layout & Spacing

The system runs on an 8pt layout grid, with a 4pt sub-scale reserved for micro-spacing inside form controls, ratings, and inline status badges.

- **Mobile Canvas**: A single-column adaptive fluid container with `1rem` (16px) standard horizontal margins, keeping critical actions comfortably within the thumb zone.
- **Tablet & Split-view (≥ 768px)**: Fluid 8-column layout with fixed bottom action sheets transforming into side navigation/docked dispatch panels.
- **Desktop Concierge Dispatch (≥ 1024px)**: 12-column fluid grid, `1.5rem` (24px) gutters, and `2rem` (32px) margins with a 420px fixed left panel for ride booking and live telematics map visualization filling remaining space.

## Elevation & Depth

Visual hierarchy is built on crisp surface layering reinforced with subtle ambient shadows and low-contrast borders:

- **Level 0 (Canvas Base)**: Deep neutral `#F8FAFC` flat surface.
- **Level 1 (Card & Module Layer)**: Pure `#FFFFFF` background with a hairline border (`1px solid #E2E8F0`) and an ambient tinted drop shadow: `0 1px 3px rgba(15, 23, 42, 0.04), 0 4px 12px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Interactive Floating Elements / Driver Profile Overlays)**: Surface `#FFFFFF` with `0 6px 20px rgba(15, 23, 42, 0.08)` and border `1px solid #E2E8F0`.
- **Level 3 (Modal Bottom Sheets & Critical Dispatch Alerts)**: Surface `#FFFFFF` with `0 12px 36px rgba(15, 23, 42, 0.14)` and a top edge micro-border `1px solid #E2E8F0`.

## Shapes

The design system embraces a progressive pill-shaped geometry. Interactive trigger surfaces, filter chips, call-to-action buttons, and trust badges utilize full pill radii (`roundedness: 3`, or `9999px` border-radius).

Container cards, modal bottom sheets, and driver profile panels use rounded rectangular corners (`1.5rem` to `2rem`) to maintain structural grounding and maximize screen efficiency.

## Components

### Buttons
- **Primary Action**: Full pill shape, `#0F172A` obsidian background, `#FFFFFF` text, 48px or 56px height, font-weight 600. Active press scale effect: `scale(0.98)`.
- **Accent Action (Booking / Confirmation)**: Full pill shape, `#2563EB` sapphire blue background, `#FFFFFF` text, subtle blue ambient glow shadow.
- **Secondary / Quick Action Buttons (Call / Message)**: Full pill or circular (44x44px) shape with subtle border (`1px solid #E2E8F0`), `#F8FAFC` background, and `#0F172A` icon/text. On hover/focus: `#FFFFFF` fill with sapphire blue border and tint.

### Verified Driver Cards
- Elevated Level 1 surface, `#FFFFFF` fill, `1.5rem` rounded corners, `1px solid #E2E8F0` border, `1rem` internal padding.
- Top row: Chauffeur portrait (56x56px, rounded-full) overlapping an emerald checkmark badge (20x20px), driver full name (`headline-sm`), vehicle model, and plate number in tabular font.
- Middle row: Rating chip (`#F8FAFC` pill, gold star icon, numerical score in bold `#0F172A`, total trips in `#334155`) paired with safety compliance pill (`#ECFDF5` emerald tint, `#10B981` text, saying "Background Verified").
- Bottom row: Inline action cluster featuring dedicated pill action buttons: Sapphire Call button and Slate Message button.

### Form Inputs & Location Selectors
- Pill or `1rem` rounded rectangle shape with 48px height, `#FFFFFF` surface, `1px solid #E2E8F0` resting border.
- Focus state: `1px solid #2563EB` with a `0 0 0 3px rgba(37, 99, 235, 0.12)` halo ring.
- Pickup and Dropoff fields: Feature solid circular destination dot markers (Sapphire for pickup, Obsidian for destination) connected by an ultra-thin vertical slate connector line.

### Trust Chips & Status Badges
- Strict pill silhouette (`border-radius: 9999px`).
- **Verified Status**: Background `#ECFDF5`, text `#065F46`, left-aligned shield or check icon in `#10B981`.
- **Live Trip / En Route Status**: Background `#EFF6FF`, text `#1E40AF`, with a pulsating 6px dot in `#2563EB`.

### Selection Controls (Radio / Checkboxes)
- Checkboxes and radios have a 20px footprint. Checked state fills with `#2563EB` or `#0F172A` and displays an internal white glyph, transitioning with a crisp 150ms spring animation.