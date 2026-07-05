---
name: Silicon Kinetic
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0d0e0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#292a2a'
  surface-container-highest: '#343535'
  on-surface: '#e3e2e2'
  on-surface-variant: '#e4bdbe'
  inverse-surface: '#e3e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#ab8889'
  outline-variant: '#5c3f41'
  surface-tint: '#ffb2b7'
  primary: '#ffb2b7'
  on-primary: '#67001b'
  primary-container: '#c5003c'
  on-primary-container: '#ffd4d6'
  inverse-primary: '#be003a'
  secondary: '#ffb3b6'
  on-secondary: '#680019'
  secondary-container: '#8f0c29'
  on-secondary-container: '#ff989e'
  tertiary: '#d6ca00'
  on-tertiary: '#353100'
  tertiary-container: '#b9af00'
  on-tertiary-container: '#454100'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdadb'
  primary-fixed-dim: '#ffb2b7'
  on-primary-fixed: '#40000d'
  on-primary-fixed-variant: '#92002a'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#ffb3b6'
  on-secondary-fixed: '#40000c'
  on-secondary-fixed-variant: '#8f0c29'
  tertiary-fixed: '#f4e703'
  tertiary-fixed-dim: '#d6ca00'
  on-tertiary-fixed: '#1e1c00'
  on-tertiary-fixed-variant: '#4d4800'
  background: '#121414'
  on-background: '#e3e2e2'
  surface-variant: '#343535'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0em
  body-lg:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.15em
  stats-number:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system embodies a "Cyber-Luxury" aesthetic, merging the raw intensity of high-performance athletics with the polished sophistication of high-technology. Targeted at an elite university demographic, the interface must feel like a premium command center—urgent, powerful, and impeccably engineered.

The visual style is a hybrid of **Glassmorphism** and **Futuristic Minimalism**. It utilizes deep obsidian surfaces, vibrant neon accents, and translucent layering to create a sense of infinite depth. High-performance gradients and subtle 3D chromatic aberration effects on key visuals evoke a sense of movement and "kinetic energy," ensuring the UI feels as active as the users themselves.

## Colors

The palette is rooted in a "Void Black" foundation to maximize contrast and premium feel. 

- **Primary Accent (#c5003c):** A high-voltage crimson used for critical actions and brand presence.
- **Secondary Accent (#880425):** A deep burgundy used for tonal gradients and secondary interactive states.
- **Highlight (#f3e600):** A "Cyber Yellow" used sparingly for high-priority alerts, specialized metrics, or "Elite" status indicators.
- **Neutrals:** White is reserved for high-readiness data, while Light Gray (#bdbdbd) handles secondary information and structural borders.

Gradients should primarily flow from Primary to Secondary accents at a 135-degree angle to simulate directional light and momentum.

## Typography

Typography centers on technical precision. **Space Grotesk** provides a geometric, futuristic skeleton for all headings and data points, reflecting the "Silicon" aspect of the brand. Its wide apertures and rhythmic spacing ensure legibility even at large, aggressive scales.

**Outfit** is used for body copy to maintain a clean, modern aesthetic that is softer and more readable than the headline face, ensuring that long-form information (like workout descriptions) remains accessible. 

Use All-Caps sparingly for labels and "overlines" to create a sense of architectural structure within the layout.

## Layout & Spacing

The system employs a "Luxury Spacing" model, favoring expansive negative space to frame content as "art." 

- **Grid:** A 12-column fluid grid on desktop with generous 64px outer margins to prevent the UI from feeling cluttered.
- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **Sectioning:** Vertical gaps between major content blocks are intentionally large (120px+) to create a "gallery" feel where each feature or machine category is given full focus.
- **Mobile:** Transition to a 4-column grid with reduced margins (20px) but maintain high vertical padding to preserve the premium, airy feel.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and internal luminescence rather than traditional shadows.

1.  **Backdrop Blurs:** Secondary surfaces use a 20px - 40px backdrop blur with a 10% white or 5% primary-color tint.
2.  **Inner Glows:** Instead of drop shadows, use subtle 1px "rim light" borders on the top and left edges of cards (15% white opacity) to simulate a light source from above.
3.  **Z-Axis:** 
    *   *Level 0:* Pure #000000 background.
    *   *Level 1:* Translucent glass cards for content grouping.
    *   *Level 2:* Floating interactive elements (buttons, active chips) with a soft #c5003c outer glow (15-20% opacity, 30px blur).

## Shapes

To maintain a "Cyber" and "Sharp" edge, the design system utilizes a **Soft (Level 1)** roundedness approach. While corners are not razor-sharp (to avoid a dated, purely brutalist look), they are kept tight to reinforce the technical and high-end engineering theme.

- **Standard Elements:** 4px (0.25rem) radius.
- **Large Cards/Containers:** 12px (0.75rem) radius.
- **Interactive States:** Maintain consistent radii; do not use pill-shapes for buttons as they conflict with the technical geometry.

## Components

- **Buttons:** Primary buttons use a solid #c5003c fill with a subtle 135° gradient to #880425. Text is Uppercase Space Grotesk. Secondary buttons use a glass background with a 1px #bdbdbd border.
- **Chips/Badges:** Small, rectangular with 2px radius. Use "Highlight" (#f3e600) with black text for "Live" or "New" status.
- **Input Fields:** Bottom-border only or very subtle translucent dark-gray fills. Focus state triggers a primary-color glow and a slight increase in border-weight.
- **Cards:** Utilize the glassmorphic style defined in Elevation. Cards should feature a "data corner"—a small technical detail like a coordinate or a hex code in the top right to reinforce the cyber-luxury theme.
- **Data Visualization:** Use high-contrast line charts with #f3e600 strokes. Apply a vertical gradient fill beneath lines using the primary accent color at low opacity.
- **Lists:** Separated by thin, 1px lines at 10% white opacity. Hover states should trigger a subtle shift in the backdrop blur density.