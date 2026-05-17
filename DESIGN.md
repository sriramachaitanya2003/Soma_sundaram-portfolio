---
name: Aurelian Estate
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c8b0'
  on-secondary: '#303221'
  secondary-container: '#494a38'
  on-secondary-container: '#b9baa3'
  tertiary: '#d0cecd'
  on-tertiary: '#313030'
  tertiary-container: '#b5b2b2'
  on-tertiary-container: '#454545'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e4e4cc'
  secondary-fixed-dim: '#c8c8b0'
  on-secondary-fixed: '#1b1d0e'
  on-secondary-fixed-variant: '#474836'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 84px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 32px
  section-gap: 120px
---

## Brand & Style

This design system is engineered for the ultra-high-net-worth real estate market. The visual narrative is defined by **Cinematic Minimalism**—a blend of dark-mode sophistication, glassmorphic depth, and architectural precision. The UI should evoke an emotional response of exclusivity, quiet confidence, and timeless luxury.

The aesthetic utilizes "Black-on-Black" layering to create depth, where the interface feels like a curated gallery. Key brand attributes include:
- **Exclusivity:** Generous whitespace (or "darkspace") to let high-resolution property photography breathe.
- **Precision:** Razor-sharp alignment and delicate gold accents that act as "jewelry" for the interface.
- **Sophistication:** Glassmorphic overlays and subtle glows that mimic the lighting of a high-end physical lounge.

## Colors

The palette is anchored in a monochromatic dark spectrum to emphasize property imagery and the Champagne Gold primary accent.

- **Matte Black (#0A0A0A):** The primary canvas color, used for the base background.
- **Deep Charcoal (#121212):** Used for elevated containers and card surfaces to create depth against the matte black base.
- **Champagne Gold (#D4AF37):** Reserved for high-value interactions, call-to-actions, and essential navigational cues.
- **Warm Beige (#F5F5DC):** Employed for secondary text and subtle borders to soften the contrast and add a "paper-like" warmth to the digital experience.
- **Pure White (#FFFFFF):** Strictly for primary headlines and high-priority body text to ensure maximum legibility.

## Typography

The typography strategy relies on a classic high-contrast pairing. **Playfair Display** provides an editorial, authoritative serif voice for headlines, echoing luxury print magazines. **Montserrat** offers a clean, geometric sans-serif balance for functional text, ensuring the interface feels modern and accessible.

Large display type should use "Optical Sizing" principles—tighter letter spacing for large headers and expanded tracking for uppercase labels. Always prioritize vertical rhythm by adhering to the 8px baseline grid.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain an "editorial" feel, transitioning to a fluid layout for mobile devices.

- **Grid:** 12-column grid with a 1440px max-width.
- **Margins:** Ultra-wide 80px side margins on desktop to create an expansive, high-end atmosphere.
- **Rhythm:** All spacing (padding, margins, gaps) must be multiples of 8px. Use 120px gaps between major landing page sections to reinforce the luxury of "wasted" space.
- **Alignment:** Property details should be meticulously aligned to the grid, often using asymmetrical layouts where imagery takes up 8 columns and text takes 4.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Atmospheric Glows** rather than traditional heavy shadows.

1.  **Level 0 (Base):** Matte Black (#0A0A0A) flat surface.
2.  **Level 1 (Floating Elements):** Deep Charcoal (#121212) with a 1px solid stroke in Champagne Gold at 10% opacity.
3.  **Level 2 (Glass Overlays):** Semi-transparent Charcoal with a `backdrop-filter: blur(20px)`. This is used for navigation bars and property detail overlays.
4.  **Accent Elevation:** Important components like "Contact Agent" buttons feature a soft, golden ambient glow (`box-shadow: 0 10px 40px rgba(212, 175, 55, 0.15)`).

Avoid hard shadows; instead, use subtle inner borders to define edges within the dark theme.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a subtle nod to modernity without losing the sharp, architectural rigor associated with high-end luxury estates. 

- **Primary Buttons & Inputs:** Use the base 4px (0.25rem) radius.
- **Property Cards:** Use `rounded-lg` (8px) to provide a slightly softer container for vivid photography.
- **Interactive Accents:** Small decorative elements (like price tags) can use a full pill-shape to distinguish them from structural UI.

## Components

### Premium Property Cards
Cards should feature full-bleed imagery with a subtle gradient overlay at the bottom for text legibility. Property titles use **Playfair Display**, while metadata (sq ft, beds) uses **Montserrat Label-caps** in Champagne Gold.

### Elegant Navigation
A floating, glassmorphic header that stays pinned. Links are in Montserrat (14px) with a 2px gold underline animation on hover.

### Sophisticated Forms
Input fields are "Ghost Style"—only a bottom border (1px) in Deep Charcoal that transitions to Champagne Gold on focus. Placeholders are in Warm Beige at 50% opacity.

### Animated Statistics
For "Sold Volume" or "Experience," use large Playfair Display numbers. On scroll, these numbers should animate upward, accompanied by a soft golden glow effect behind the text.

### Buttons
- **Primary:** Champagne Gold background with Matte Black text. No border.
- **Secondary:** Transparent background with a 1px Champagne Gold border and gold text.
- **Hover State:** Add a subtle outer glow and a 2px upward transform shift.