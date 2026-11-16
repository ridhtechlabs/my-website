---
name: Synthetic Horizons
colors:
  surface: '#0d1512'
  surface-dim: '#0d1512'
  surface-bright: '#323b38'
  surface-container-lowest: '#08100d'
  surface-container-low: '#151d1b'
  surface-container: '#19211f'
  surface-container-high: '#232c29'
  surface-container-highest: '#2e3734'
  on-surface: '#dbe5e0'
  on-surface-variant: '#bdcac0'
  inverse-surface: '#dbe5e0'
  inverse-on-surface: '#2a322f'
  outline: '#87948b'
  outline-variant: '#3e4942'
  surface-tint: '#6cdbaa'
  primary: '#b7ffda'
  on-primary: '#003825'
  primary-container: '#79e8b6'
  on-primary-container: '#006848'
  inverse-primary: '#006c4b'
  secondary: '#3fe490'
  on-secondary: '#00391e'
  secondary-container: '#00c777'
  on-secondary-container: '#004c2a'
  tertiary: '#b9ffd7'
  on-tertiary: '#003823'
  tertiary-container: '#84e7b4'
  on-tertiary-container: '#006845'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#89f8c5'
  primary-fixed-dim: '#6cdbaa'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#60fea8'
  secondary-fixed-dim: '#3be18e'
  on-secondary-fixed: '#00210f'
  on-secondary-fixed-variant: '#00522e'
  tertiary-fixed: '#93f6c3'
  tertiary-fixed-dim: '#77daa8'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005235'
  background: '#0d1512'
  on-background: '#dbe5e0'
  surface-variant: '#2e3734'
  bg-abyss: '#030907'
  bg-subtle: '#07140F'
  surface-panel: '#10251B'
  text-primary: '#F3FAF6'
  text-muted: '#A8B9AF'
  border-cyan-glow: rgba(121, 232, 182, 0.15)
  border-subtle: rgba(255, 255, 255, 0.12)
  light-bg: '#F5F8F6'
  light-secondary: '#EAF0EC'
  light-surface: '#FFFFFF'
  light-text-primary: '#10241B'
  light-text-secondary: '#52665B'
  light-border: rgba(16, 36, 27, 0.12)
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 76px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-code:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-telemetry:
    fontFamily: Space Mono
    fontSize: 10px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.12em
spacing:
  gutter: 1.5rem
  margin: 2rem
  gutter-mobile: 1rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system translates the ethos of enterprise-grade Extended Reality (XR), spatial computing, and real-time Unity simulation into an uncompromising visual language. The brand persona is avant-garde, technically rigorous, architectural, and future-forward. It addresses enterprise CTOs, simulation leads, and spatial technology decision-makers who demand mathematical precision paired with daring visual momentum.

The design movement is **Brutalist Spatialism**: an intersection of high-contrast architectural geometry, raw monospaced telemetry, and stark, zero-radius glass surfaces. Eschewing soft consumer skeuomorphism, the aesthetic utilizes sharp orthogonal edges, planar viewport division, and razor-fine borders that mirror CAD viewports and volumetric projection matrices. Visual tension is achieved through deep, void-like chromatic blacks, hyper-saturated emerald energy lines, and sculpted display typography that evokes engineering beyond physical reality.

## Colors

The chromatic architecture is constructed upon high-voltage emerald highlights cutting through low-luminance forest blacks. 

- **Primary (`#79E8B6`)**: An electric emerald-mint highlight representing active photons, coordinate nodes, interactive focus states, and telemetry trackers.
- **Secondary (`#00C878`)**: A deeper, saturated emerald used for functional progress indicators, data vectors, and secondary actions.
- **Tertiary (`#16865B`)**: An anchor forest green tailored for structural mid-tones in dark mode and primary brand focus in light mode.
- **Neutral (`#030907`)**: An ultra-deep obsidian green void serving as the infinite viewport canvas.

### Theme Modes
- **Dark Mode (Default)**: Leverages `#030907` for canvas backdrops and `#10251B` for nested planar panels. Structural divisions rely on translucent borders (`rgba(121, 232, 182, 0.15)` or `rgba(255, 255, 255, 0.12)`).
- **Light Mode**: Re-indexes the spatial stack using `#F5F8F6` canvas, `#FFFFFF` crisp monolithic cards, `#16865B` high-contrast brand focus, and `#10241B` deep forest typography.

## Typography

Typography establishes an intentional tension between human expression and machine output:
- **Headlines (`Syne`)**: Avant-garde, sculptural, and geometric. Scaled aggressively with tight negative tracking, echoing architectural blueprints and futuristic industrial sign systems.
- **Body & Data Telemetry (`Space Mono`)**: Exacting, monospaced, and utilitarian. Gives editorial descriptions, metrics, and interactive triggers the technical gravity of terminal interfaces, CAD coordinates, and game engine scripts.

All display titles are rendered in sentence case or uppercase depending on context, while system tags, telemetry coordinates, and status markers run strictly in uppercase with extended letter spacing (`0.08em` to `0.12em`).

## Layout & Spacing

The layout is built upon a 12-column architectural matrix that prioritizes structural grids, coordinate alignments, and expansive negative space:

- **Desktop (>= 1200px)**: 12 columns, 1.5rem (`gutter`) column separation, 2rem to 4rem canvas boundary margins. Components align rigidly to horizontal wireframes.
- **Tablet (768px - 1199px)**: 8 columns, 1.25rem gutter, 1.5rem margins. Complex spatial cards collapse to 4 or 8 column spans.
- **Mobile (< 768px)**: 4 columns, 1rem gutter, 1rem canvas margins. Multi-column grids linearize into stark modular stacked blocks.

Horizontal dividing lines, crosshair junction points (`+`), and boundary indicators run uninterrupted to the viewport edge to simulate an infinite coordinate plane.

## Elevation & Depth

Visual hierarchy does not rely on soft, blurred drop shadows. Instead, this design system operates with **Spatial Tonal Layering and Hard Photonic Borders**:

1. **Base Layer (L0)**: `#030907` background canvas featuring faint, low-opacity vector grids (0.04 alpha).
2. **Structural Panels (L1)**: `#07140F` to `#10251B` backgrounds with frosted glass backdrops (`backdrop-filter: blur(20px)`), bound by 1px crisp borders (`rgba(255, 255, 255, 0.12)`).
3. **Hover & Active States (L2)**: Hovered cards and active containers reveal an internal photonic line or a 1px boundary glow in Primary Accent (`#79E8B6`), coupled with an inner gradient wash (`linear-gradient(180deg, rgba(121, 232, 182, 0.08) 0%, transparent 100%)`).
4. **Overlays & Floating Modals (L3)**: Monolithic panels backed by `#030907` at 90% opacity, bordered completely by `#79E8B6` with zero outer shadow, emphasizing raw edge clarity.

## Shapes

The geometry of this design system is absolute: **0px border radius across all interactive elements, containers, and inputs**. 

Curves are banished in favor of brutalist precision, sharp orthogonal angles, and rectilinear planes reminiscent of wireframe models, optical viewports, and silicon architecture. Corner notches, chamfered corner cuts (45-degree angle accents on cards or buttons), and razor-sharp border junctures replace rounded radii, underscoring an unyielding, high-tech industrial aesthetic.

## Components

### Buttons & Interactive Triggers
- **Primary CTA**: Monolithic rectangular block, zero radius. Background `#79E8B6`, typography `#030907` (Space Mono, Bold, uppercase, letter-spacing: 0.08em). On hover, shifts to `#00C878` with a 1px offset accent outline.
- **Secondary / Ghost CTA**: Background transparent, 1px border `rgba(121, 232, 182, 0.4)`, text `#F3FAF6`. On hover, background transitions to `rgba(121, 232, 182, 0.1)` and border transitions to `#79E8B6`.
- **Micro CTAs**: Accompanied by terminal indicators like `[ENTER]` or `->`.

### Glassmorphic Panels & Cards
- **Construction**: 0px radius, background `#10251B` at 60% opacity with `backdrop-filter: blur(20px)`. 1px perimeter stroke using `rgba(255, 255, 255, 0.12)`.
- **Card Accents**: Top-right technical coordinate labels (`[SYS_XR_01]`) in `#A8B9AF` monospaced font. On hover, the border shifts to `#79E8B6` and the top edge receives a 2px energetic highlight.

### Chips & Badges
- **Form**: Rectangular tags, zero radius, border 1px solid `rgba(121, 232, 182, 0.3)`. Background `rgba(7, 20, 15, 0.85)`. 
- **Typography**: Space Mono 10px uppercase with a prepended status square indicator (`■ ACTIVE`).

### Input Fields & Controls
- **Text Inputs**: Flat zero-radius containers, background `#07140F`, bottom border 2px solid `rgba(255, 255, 255, 0.2)`. Focus triggers full border illumination in `#79E8B6` with an accompanying active terminal cursor.
- **Checkboxes & Radios**: Strict square enclosures (16x16px), zero radius. Checked state fills with `#79E8B6` harboring a high-contrast black inner dot or cross.

### Navigation Header
- **Structure**: Floating monolithic bar pinned with 0px corner geometry, suspended above the canvas with a 24px backdrop blur, bordered by `rgba(121, 232, 182, 0.15)`. Contains real-time theme toggles and telemetry status.