---
name: Clinical Elegance
colors:
  surface: '#f6faff'
  surface-dim: '#d2dbe4'
  surface-bright: '#f6faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ecf5fe'
  surface-container: '#e6eff8'
  surface-container-high: '#e0e9f2'
  surface-container-highest: '#dbe4ed'
  on-surface: '#141d23'
  on-surface-variant: '#3c4946'
  inverse-surface: '#293138'
  inverse-on-surface: '#e9f2fb'
  outline: '#6c7a76'
  outline-variant: '#bbcac5'
  surface-tint: '#006b5f'
  primary: '#006b5f'
  on-primary: '#ffffff'
  primary-container: '#00a896'
  on-primary-container: '#00352e'
  inverse-primary: '#59dbc7'
  secondary: '#505f79'
  on-secondary: '#ffffff'
  secondary-container: '#d1e0ff'
  on-secondary-container: '#54637d'
  tertiary: '#5c5f60'
  on-tertiary: '#ffffff'
  tertiary-container: '#949697'
  on-tertiary-container: '#2c2f30'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#79f7e3'
  primary-fixed-dim: '#59dbc7'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005047'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#b8c7e5'
  on-secondary-fixed: '#0c1c32'
  on-secondary-fixed-variant: '#394760'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f6faff'
  on-background: '#141d23'
  surface-variant: '#dbe4ed'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  grid-gutter: 24px
  container-max-width: 1280px
---

## Brand & Style
The design system is engineered for a premium medical tourism experience, balancing clinical precision with high-end hospitality. The target audience includes international patients seeking top-tier healthcare combined with luxury travel. 

The aesthetic is **Modern Corporate** with a **Minimalist** foundation. It leverages generous white space to evoke a sense of cleanliness and calm. The visual narrative moves away from traditional "hospital" coldness toward a "medical spa" warmth, utilizing smooth transitions and a light, airy interface to build immediate trust and reduce user anxiety.

## Colors
The palette is anchored by **Medical Turquoise**, a color that signifies health, vitality, and professional sterilization. 

- **Primary (#00A896):** Used for key actions and brand accents.
- **Secondary (#1B2A41):** A deep navy used for grounding the design in professional authority and for high-contrast typography.
- **Backgrounds (#FFFFFF, #F8F9FA):** Crisp white is the base for all content areas, while soft light grey is used to differentiate sections and create a subtle layered effect.
- **State Colors:** Success (Green), Warning (Amber), and Error (Red) should be muted to match the professional tone.

## Typography
This design system utilizes **Inter** exclusively to maintain a systematic and highly legible interface. The weight distribution is intentional: use heavier weights (SemiBold/Bold) for headlines to establish authority, and Regular weights with increased line height for body text to ensure readability for international users.

Special attention is paid to tracking: Display sizes use negative letter spacing for a tighter, premium editorial look, while uppercase labels use expanded tracking for better scannability in navigation and category markers.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to maintain the high-end, structured feel of a premium brochure. 

- **Desktop (1280px+):** 12-column grid with 24px gutters. Use large "breathing spaces" (120px) between major sections to prevent information overload.
- **Tablet (768px - 1024px):** 8-column grid with 24px margins.
- **Mobile (<768px):** 4-column grid with 16px margins.
- **Rhythm:** All internal component spacing (padding/margins) must be multiples of the 8px base unit to ensure a consistent visual cadence.

## Elevation & Depth
The design system employs **Ambient Shadows** to create a sense of physical layering without looking "heavy."

- **Level 1 (Subtle):** Used for persistent cards. A soft, extremely diffused shadow (0px 4px 20px) with 5% opacity and a slight turquoise tint (#00A896 at 0.05).
- **Level 2 (Active/Hover):** For interactive elements. A more pronounced shadow (0px 10px 30px) with 10% opacity.
- **Surface Layering:** Use the light grey background (#F8F9FA) for the main page body and pure white (#FFFFFF) for interactive containers to make them "pop" naturally.

## Shapes
The shape language is **Rounded**, utilizing an 8px (0.5rem) base radius. This specific curvature is chosen because it feels modern and approachable while remaining professional—avoiding the "playfulness" of pill shapes or the "harshness" of sharp corners. 

Buttons and input fields should strictly adhere to this 8px radius. High-level containers, like package cards or hero images, can scale up to `rounded-xl` (24px) to emphasize their role as distinct, "soft" objects in the layout.

## Components
- **Glossy Package Cards:** Use a white background with a subtle Level 1 shadow. Include a 1px solid border in a very light grey (#E9ECEF). The top of the card should feature a high-resolution image with a subtle 5% turquoise overlay.
- **Primary CTAs:** Solid Medical Turquoise (#00A896) background with White text. Use Bold weight and 8px padding (vertical) by 24px (horizontal).
- **Secondary CTAs:** Ghost style with a 2px turquoise border.
- **Input Fields:** Soft grey background (#F8F9FA) with a 1px border that turns Turquoise on focus. Labels should be small and SemiBold.
- **Professional Gallery:** A masonry or structured grid with consistent 24px gaps. Every image should have a slight `rounded-lg` corner.
- **Trust Badges:** Small, monochromatic icons in #6C757D to maintain a clean aesthetic, placed in a horizontal flex layout with generous spacing.