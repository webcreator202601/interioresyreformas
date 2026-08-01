---
name: Atelier Construct
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#51443c'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#83746b'
  outline-variant: '#d5c3b8'
  surface-tint: '#805533'
  primary: '#6f4627'
  on-primary: '#ffffff'
  primary-container: '#8b5e3c'
  on-primary-container: '#ffe3d1'
  inverse-primary: '#f4bb92'
  secondary: '#5e5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#4d5154'
  on-tertiary: '#ffffff'
  tertiary-container: '#65696c'
  on-tertiary-container: '#e6e9ec'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc5'
  primary-fixed-dim: '#f4bb92'
  on-primary-fixed: '#301400'
  on-primary-fixed-variant: '#653d1e'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#e0e3e6'
  tertiary-fixed-dim: '#c3c7ca'
  on-tertiary-fixed: '#181c1f'
  on-tertiary-fixed-variant: '#43474a'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
  grid-columns: '12'
---

## Brand & Style
The design system is built for a renovation firm that balances artisanal craftsmanship with modern project management. The personality is grounded, meticulous, and inviting—moving away from cold, industrial construction aesthetics toward a "warm-home" philosophy. 

The style utilizes **Modern Tactile Minimalism**. It focuses on high-quality whitespace to suggest cleanliness and precision, while using subtle textures and organic color transitions to evoke the feeling of raw materials like wood, stone, and plaster. The goal is to make the user feel like their renovation is in the hands of a master craftsperson who values both design and structural integrity.

## Colors
The palette is rooted in the materials of the trade. 
- **Warm Wood (Primary):** Used for primary actions and key brand moments, representing stability and craftsmanship.
- **Tile White (Background):** A soft, warm-leaning off-white used for main surfaces to prevent the "sterile" feel of pure #FFFFFF.
- **Slate Grey & Deep Charcoal:** Used for secondary structural elements and typography to provide high-contrast legibility.

Avoid pure black. Use **Deep Charcoal** for all primary text to maintain a sophisticated, softer edge. Backgrounds should favor **Tile White**, with sections of **Warm Wood** or **Slate Grey** used for high-impact content blocks.

## Typography
The system uses a pairing of **Montserrat** for impact and **Inter** for utility. 

**Montserrat** is used for headlines to convey confidence and architectural structure. Tracking should be slightly tightened on larger display sizes to maintain a premium feel. 

**Inter** is utilized for all body copy and UI elements. Its neutral, systematic nature ensures that technical information (measurements, project specs) remains highly legible. For labels and "Overlines," use Inter Bold with uppercase styling and increased letter spacing to create a professional, blueprint-inspired look.

## Layout & Spacing
This design system employs a **12-column fluid grid** with generous internal margins. To emphasize the premium nature of the service, vertical spacing (section gaps) is intentionally oversized, allowing imagery of the renovations to "breathe."

- **Masonry Grids:** For project galleries, use a masonry layout with a consistent 24px gap. This mimics the organic but structured nature of architectural tiling.
- **Content Width:** Narrative content should be constrained to an 8-column centered span within the 12-column grid to ensure readability.
- **Mobile:** Transition to a 4-column grid with 16px margins.

## Elevation & Depth
Depth is achieved through **Tonal Layering** rather than heavy shadows. 

- **Level 0 (Base):** Tile White (#F9F7F2).
- **Level 1 (Cards/Surface):** White (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px rgba(26, 28, 30, 0.04)) and a 1px border of Surface-Border (#E5E1D8).
- **Level 2 (Interaction):** When hovering over interactive elements, increase the shadow spread and slightly shift the element upward (2px) to provide tactile feedback.

Avoid heavy blurs or glassmorphism. The system should feel solid and physical, like a stone countertop or a wooden plank.

## Shapes
The shape language is "Soft-Technical." Elements use a **0.25rem (4px)** base radius. This provides a subtle softening of the UI that feels modern and approachable without losing the precision associated with professional construction and architectural lines. 

- **Buttons & Inputs:** 4px radius.
- **Project Cards:** 8px (rounded-lg) to frame photography effectively.
- **Interactive Sliders:** The handle should be a perfect circle to denote touch-point priority.

## Components
- **Buttons:** Primary buttons use the `warm-wood` background with white text. Secondary buttons use a `deep-charcoal` outline with 1px thickness. High-conversion "Get a Quote" buttons should include a subtle right-arrow icon that translates 4px to the right on hover.
- **Before/After Sliders:** A critical component for conversion. Use a vertical divider line in `slate-grey` with a circular `warm-wood` handle.
- **Cards:** Project cards must feature a full-bleed image at the top with a 1:1 or 4:5 aspect ratio. Content below the image should be padded with 24px on all sides using the `body-md` typography.
- **Input Fields:** Use a 1px border of `slate-grey`. On focus, the border transitions to `warm-wood` with a 2px thickness. Labels sit above the field in `label-sm`.
- **Chips:** Used for project categories (e.g., "Kitchen," "Bath"). These should have a background of `tile-white` and a border of `surface-border`, using `label-sm` for the text.
- **Masonry Gallery:** Images should have consistent 8px rounding and use a "reveal" animation on scroll to emphasize the "reveal" of a renovation.