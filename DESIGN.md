---
name: Hydration Excellence System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#414754'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bbf'
  primary: '#0059ba'
  on-primary: '#ffffff'
  primary-container: '#0071e9'
  on-primary-container: '#fefcff'
  inverse-primary: '#acc7ff'
  secondary: '#00639b'
  on-secondary: '#ffffff'
  secondary-container: '#1ea8ff'
  on-secondary-container: '#003a5e'
  tertiary: '#006481'
  on-tertiary: '#ffffff'
  tertiary-container: '#007ea2'
  on-tertiary-container: '#fbfdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#004492'
  secondary-fixed: '#cee5ff'
  secondary-fixed-dim: '#96cbff'
  on-secondary-fixed: '#001d33'
  on-secondary-fixed-variant: '#004a76'
  tertiary-fixed: '#bee9ff'
  tertiary-fixed-dim: '#68d3ff'
  on-tertiary-fixed: '#001f2a'
  on-tertiary-fixed-variant: '#004d64'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is anchored in the concepts of purity, reliability, and precision. It targets families and corporate clients who prioritize hygiene and seamless service. The aesthetic is a fusion of **Corporate Modern** and **Minimalism**, utilizing vast amounts of whitespace to simulate the clarity of water. 

Visuals should focus exclusively on the product—pristine water containers, high-tech filtration systems, and professional male staff in clean, branded uniforms. The emotional response is one of safety and refreshment, achieved through high-contrast interfaces and a strictly organized structural grid.

## Colors
The palette is a monochromatic exploration of blue, symbolizing various depths and states of water. 
- **Primary Blue (#0B7DFF):** Used for primary actions and brand presence. It conveys trust and authority.
- **Secondary & Accent Blues:** Used for interactive hover states, progress indicators, and subtle highlights.
- **Surface Tint (#F4FAFF):** A very light "ice" blue used for background sections to differentiate content blocks without losing the feeling of cleanliness.
- **Neutral (#1A1A1A):** A deep charcoal for typography to ensure AAA accessibility and high readability against white backgrounds.

## Typography
This design system utilizes **Inter** for its systematic and neutral qualities. The hierarchy is intentionally strict to reflect a professional utility service.
- **Headlines:** Use Semi-Bold weights with slight negative letter-spacing to appear tighter and more premium.
- **Body Text:** Standard weight for maximum legibility. Use the `body-lg` for introductory paragraphs to maintain a sophisticated editorial feel.
- **Labels:** Medium weight is preferred for UI elements like buttons and chips to ensure they stand out from body copy.

## Layout & Spacing
The layout follows a **12-column fluid grid** on desktop and a **4-column grid** on mobile. 

- **Vertical Rhythm:** Built on an 8px baseline. Sections should be separated by `lg` (48px) or `xl` (80px) spacing to enforce the "Generous Whitespace" requirement.
- **Content Width:** Max-width for readable content is capped at 1200px to prevent line lengths from becoming too long on ultra-wide monitors.
- **Safe Areas:** On mobile, side margins never drop below 16px to ensure touch targets and text remain clear of bezel edges.

## Elevation & Depth
Depth in this design system is achieved through **Ambient Shadows** and **Tonal Layering**. 

1.  **Level 0 (Base):** #FFFFFF background.
2.  **Level 1 (Surfaces):** #F4FAFF used for cards or secondary sections.
3.  **Level 2 (Floating):** White cards with a subtle, diffused shadow (Blur: 20px, Y: 4px, Color: #0B7DFF at 4% opacity). This "tinted shadow" reinforces the brand color even in the shadows.
4.  **Level 3 (Interactive):** On hover, shadows should increase in spread and slightly in opacity to 8% to create a "lift" effect.

## Shapes
The shape language is "Rounded," utilizing an 8px (0.5rem) base radius. This softens the corporate edges, making the brand feel more family-friendly and approachable while maintaining professional rigor. 
- **Small Elements (Inputs/Chips):** 8px radius.
- **Large Elements (Cards/Modals):** 16px (1rem) radius.
- **Buttons:** 8px for a sturdy, reliable look, or full-pill for "Quick Order" CTAs.

## Components
- **Premium Cards:** Must use #FFFFFF backgrounds with a Level 2 shadow. Padding should be generous (min 32px).
- **Sticky Header:** Uses a Backdrop Blur (12px) with 90% opacity white background to maintain context while scrolling. Include a primary "Order Now" button in the top right.
- **Timeline Designs:** Used for delivery tracking. Use the Primary Blue for completed stages and Tertiary Blue for the active stage.
- **Accordion FAQs:** Minimalist style. Use thin 1px dividers (#E5F2FF) and a simple chevron. Avoid heavy borders.
- **Responsive Forms:** Inputs use the #F4FAFF background as default, shifting to #FFFFFF with a 2px Primary Blue border on focus.
- **Imagery Guidelines:** Only use high-resolution photography of male delivery professionals, clean machinery, or splashing pure water. Ensure no non-Islamic content or prohibited substances appear in backgrounds.