---
name: Obsidian Luminescence
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
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e3e1e9'
  inverse-on-surface: '#2f3036'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#b9c8de'
  on-tertiary: '#233143'
  tertiary-container: '#8392a6'
  on-tertiary-container: '#1c2b3c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#d4e4fa'
  tertiary-fixed-dim: '#b9c8de'
  on-tertiary-fixed: '#0d1c2d'
  on-tertiary-fixed-variant: '#39485a'
  background: '#121318'
  on-background: '#e3e1e9'
  surface-variant: '#34343a'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 52px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 42px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
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
  gutter: 1rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system expresses a luxury, dark-cyberpunk aesthetic for an advanced mobile experience. It fuses high-precision technology with sensory elegance: deep obsidian voids, razor-sharp kinetic lighting, and crystalline glass layers. 

### Design Direction & Personality
- **Atmosphere:** Deep obsidian nights punctuated by ionized neon atmospheric glows and surgical chrome accents.
- **Emotion:** Ultra-premium, meditative yet energetic, technologically advanced, and deeply immersive.
- **Style Fusion:** Dark Cyberpunk Luxury meets high-end Glassmorphism and refined Material You mechanics. It rejects retro-grunge cyberpunk in favor of haute-couture digital design: pristine dark glass, fine hairline borders, luminous cyan data visualizations, and intense electric violet energy nodes.

## Colors

The palette is engineered around pure visual hierarchy across dark space, ensuring glowing energy without visual fatigue.

### Palette Structure
- **Base Neutral (`#090A0F`):** Obsidian foundation, absorbing ambient space while keeping the OLED contrast infinite.
- **Secondary Surfaces (`#0D0F17`, `#161926`):** Deep atmospheric obsidian layers used for elevation panels and containers.
- **Primary Electric Violet (`#8B5CF6`, `#7C3AED`):** Sovereign accent indicating primary actions, active state transitions, and meditative core rings.
- **Secondary Luminescent Cyan (`#06B6D4`, `#22D3EE`):** Biometric feedback, real-time indicators, data streams, and high-frequency tactile responses.
- **Metallic / Slate Accents (`#94A3B8`, `#E2E8F0`):** Polished titanium edge highlights and premium typography contrast levels.

## Typography

The type hierarchy utilizes **Plus Jakarta Sans** across all tiers to evoke geometric clarity, premium ergonomics, and effortless readability under ambient neon lighting conditions.

- **Display & Headlines:** Geometric, wide apertures, tracked slightly tighter (`-0.02em`) to assert weight, precision, and technological luxury.
- **Body:** Open, relaxed kerning for maximum legibility against obsidian glass layers.
- **Labels & Micro-data:** Uppercase variants use subtle wide letter-spacing (`+0.05em`) for telemetry data, breath pacing metrics, and state badges.

## Layout & Spacing

The layout is built specifically for high-end Android viewport parameters with dynamic edge gestures and bezel interactions.

- **Grid Architecture:** 4-column fluid layout on mobile, scaling to 8 columns on foldables and tablets. 
- **Margin Model:** Rigid `1.25rem` (20px) outer boundary maintaining safe-area distance from physical curved glass screen edges.
- **Vertical Rhythm:** 8pt modular grid. Breath metrics and floating bio-dials anchor to the center quadrant, using dynamic flex containers to preserve thumb-zone accessibility.

## Elevation & Depth

Depth is established through multi-layer glass physics rather than standard drop shadows.

- **Obsidian Glass Foundations:**
  - Base: `#090A0F` flat field.
  - Surface Tier 1 (Cards, Sheet): `rgba(13, 15, 23, 0.72)` with a 24px backdrop blur and a 1px border of `rgba(255, 255, 255, 0.08)`.
  - Surface Tier 2 (Active elements, Overlays): `rgba(22, 25, 38, 0.85)` with a 32px backdrop blur.
- **Luminescent Edge Lighting:** Key active cards deploy a top-down hair-thin gradient border: `linear-gradient(135deg, rgba(139, 92, 246, 0.5) 0%, rgba(6, 182, 212, 0.3) 50%, rgba(255, 255, 255, 0.05) 100%)`.
- **Neon Aura (Glow):** Ambient glows are diffused widely using blurred radial lights (`blur(40px)` to `blur(80px)`) under 15% opacity behind primary visual anchors such as breath expansion rings.

## Shapes

The shape system employs continuous squircle curves (`roundedness: 2`) reminiscent of polished crystal and luxury industrial hardware.

- Small controls (chips, status pills, sliders) use soft squircle geometry or complete pill radii.
- Surface cards and interactive panels apply refined 16px corner geometry (`rounded-lg`), blending seamlessly with modern Android device corner radii.

## Components

### Buttons
- **Primary Action (Ionic Glow):** Filled with a linear gradient from Electric Violet (`#8B5CF6`) to `#7C3AED`, accented by an outer cyan diffusion glow (`box-shadow: 0 0 20px rgba(139, 92, 246, 0.35)`). Label is crisp titanium white.
- **Secondary (Obsidian Glass):** Background `rgba(255, 255, 255, 0.05)`, border `1px solid rgba(255, 255, 255, 0.12)`, text `#E2E8F0`. Hover and tap state illuminates a subtle cyan rim glow.

### Interactive Chips
- Capsule-shaped with translucent tinted backdrops.
- Inactive state: `rgba(255, 255, 255, 0.04)` with muted slate typography.
- Selected state: Border illuminated in Neon Cyan (`#06B6D4`), inner glow `rgba(6, 182, 212, 0.15)`, and cyan text.

### Inputs & Sliders
- Input fields display dark obsidian sunken wells (`#0D0F17`) with a 1px metallic border that shifts to Electric Violet upon focus.
- Biometric breath frequency sliders feature glowing cyan tracks with an illuminated chrome pill thumb.

### Cards & Dashboards
- Glassmorphic panels featuring translucent obsidian depth, fine luminous borders, and content structured via clean modular padding (`space-lg`).

### Floating Bio-Controllers (Specialized Component)
- Custom circular glass rings hosting dynamic visual breath expansion waves, alternating gently between deep violet contraction phases and vibrant cyan expansion phases.