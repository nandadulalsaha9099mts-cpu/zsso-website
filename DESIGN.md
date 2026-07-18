---
name: Artisanal Liquid Gold
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0d0e0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c5c6cd'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8f9097'
  outline-variant: '#44474d'
  surface-tint: '#b9c7e4'
  primary: '#b9c7e4'
  on-primary: '#233148'
  primary-container: '#0a192f'
  on-primary-container: '#74829d'
  inverse-primary: '#515f78'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#ffb77d'
  on-tertiary: '#4d2600'
  tertiary-container: '#2b1300'
  on-tertiary-container: '#b77232'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is centered on the concept of "Artisanal Elixir"—a premium, high-sensory experience that balances the depth of craftsmanship with the explosive energy of carbonation. It targets a sophisticated audience that values quality and aesthetic pedigree.

The visual style is a fusion of **Corporate Modern** structure and **Glassmorphism**, leveraging the atmospheric lighting of the reference image. The UI should evoke a sense of luxury through high-contrast interplay between dark, nocturnal surfaces and brilliant, liquid-inspired highlights. Expect deep shadows, luminous gradients, and ultra-crisp typography that feels both established and contemporary.

## Colors

The palette is derived directly from the interplay of shadow and light found in premium beverage photography.

- **Primary (Midnight Navy):** A deep, saturated navy used for backgrounds and primary containers, providing a "nocturnal" canvas.
- **Secondary (Burnished Gold):** A refined, muted gold for call-to-actions, iconography, and decorative accents.
- **Tertiary (Amber Sparkle):** A vibrant highlight color used for states (hover, focus) and gradient stops to mimic the warm glow of backlit soda bubbles.
- **Neutral:** Warm-tinted greys and off-whites for high legibility against the dark backgrounds.

Color application should lean heavily into gradients, moving from the primary navy to even darker tones at the edges, with localized glows of amber to simulate cinematic lighting.

## Typography

This design system uses a triple-font strategy to balance elegance with technical precision. 

**Manrope** is used for headlines, providing a modern, balanced, and premium geometric feel. **Hanken Grotesk** serves as the primary body face, chosen for its exceptional readability and sharp, contemporary tone. For labels, metadata, and technical details (like volume or ABV), **Space Grotesk** adds a subtle "crafted" or industrial edge that references artisanal labeling.

High-impact typography should utilize the Gold secondary color, often paired with a subtle drop shadow or "inner glow" to suggest the metallic embossing found on premium beverage cans.

## Layout & Spacing

The layout follows a **fluid grid** model with generous margins to create a high-end, editorial feel. 

- **Desktop:** A 12-column grid with 24px gutters. Content is often centered with significant horizontal padding to focus the user’s eye.
- **Mobile:** A 4-column grid with 16px margins. 
- **Rhythm:** An 8px base unit governs all spacing. Vertical white space should be intentionally large between sections (using `12x` or `16x` units) to maintain an air of luxury and prevent the interface from feeling cluttered.

Components should utilize "safe areas" derived from the golden ratio where possible, especially when positioning text over product imagery.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Glassmorphism**. Surfaces are not just flat colors; they are treated as materials.

1.  **Base Layer:** Midnight Navy (#0A192F).
2.  **Container Layer:** Deep Navy with 40% opacity and a 20px backdrop blur, creating a "frosted glass" effect that allows background glows to peek through.
3.  **Accents:** Thin, 1px strokes in Burnished Gold (#C5A059) at 20-30% opacity to define container edges without heavy shadows.
4.  **Shadows:** When used, shadows are "Ambient Glows"—highly diffused (40-60px blur) with a hint of Amber (#F4A460) to simulate light reflecting off liquid.

## Shapes

The shape language reflects the silhouette of the craft soda can: structurally sound but with softened edges. 

Standard components use a **0.5rem (8px)** corner radius. Large cards and hero images should scale to **1.5rem (24px)** to feel approachable yet substantial. Interactive elements like buttons may use pill-shapes (full rounding) to contrast against the more architectural grid-based layout.

## Components

- **Buttons:** Primary buttons use a solid Gold background with Navy text. Secondary buttons are "Ghost" style with a Gold border and a subtle glass-blur background on hover.
- **Input Fields:** Dark, recessed backgrounds with Gold bottom-borders that animate (expand) on focus.
- **Cards:** Utilize the glassmorphic style described in Elevation. They feature a 1px top-left highlight border to simulate a light source hitting the "glass."
- **Chips/Labels:** Small, pill-shaped elements using Space Grotesk in all-caps. These should have a subtle glow effect if they denote a "Live" or "New" status.
- **Lists:** Separated by thin, low-opacity gold dividers. Hovering over a list item triggers a subtle Amber background glow.
- **Sparkle Effect:** A custom decorative component—small, varying opacity Gold circles—should be used sparingly in the background of hero sections to mimic the carbonation bubbles from the reference image.