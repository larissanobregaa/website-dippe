---
name: Horizon Elite
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
  on-surface-variant: '#43474f'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#00658d'
  on-secondary: '#ffffff'
  secondary-container: '#2dbcfe'
  on-secondary-container: '#004866'
  tertiary: '#2a1c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#453000'
  on-tertiary-container: '#bb9650'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#c6e7ff'
  secondary-fixed-dim: '#82cfff'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6b'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
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

The design system is anchored in the concept of "Seamless Exploration." It targets a discerning audience seeking reliability, premium service, and global reach. The visual narrative combines **Corporate Modern** stability with **Minimalist** clarity to ensure the travel booking experience feels effortless rather than overwhelming.

The aesthetic prioritizes legibility and "breathability." By utilizing expansive whitespace and high-quality photography, the UI evokes an emotional response of tranquility and anticipation. Every interaction is designed to feel intentional and sophisticated, reinforcing the agency's position as a trusted guide in the luxury and professional travel market.

## Colors

The color palette is directly derived from the core brand identity, emphasizing depth and trust. 

*   **Primary (Deep Navy):** Used for core branding, headers, and primary actions to establish authority.
*   **Secondary (Sky Blue):** Inspired by the globe, this is used for interactive elements, highlights, and icons to provide a sense of openness.
*   **Tertiary (Compass Gold):** A sophisticated accent color used sparingly for premium features, ratings, or special offers, mirroring the compass needle in the logo.
*   **Neutral:** A range of cool grays and crisp whites maintain the "airy" feel and provide high contrast for legibility.

## Typography

**Plus Jakarta Sans** is the exclusive typeface for this design system. Its modern, geometric construction offers a clean and approachable feel while maintaining professional rigor. 

For display text and headlines, we use tighter letter-spacing and heavier weights to create a strong visual hierarchy. Body text utilizes generous line-heights to ensure maximum readability during long-form destination reading. Labels are set in semi-bold with slight tracking to distinguish them clearly from body content in densly packed travel itineraries.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **Tonal Layers** and **Soft Ambient Shadows**. 

*   **Surface Levels:** The base background is the neutral white. Cards and containers use a subtle 1px border in a very light gray or a low-opacity Sky Blue tint.
*   **Shadows:** When depth is required (e.g., for hovering over a travel destination card), use an extra-diffused shadow: `box-shadow: 0 12px 32px -8px rgba(0, 51, 102, 0.12)`. This uses the primary navy color as the shadow tint rather than pure black, creating a more cohesive, "designer" feel.
*   **Overlays:** Navigation bars utilize a subtle glassmorphism effect (backdrop-blur: 12px) to allow the vibrant travel photography to bleed through while maintaining text legibility.

## Shapes

The shape language is **Rounded (Level 2)**. This balance avoids the clinical feel of sharp corners while remaining more professional than fully pill-shaped "playful" designs.

*   **Standard Components:** Buttons and input fields use an 8px radius.
*   **Feature Containers:** Destination cards and imagery use a 16px radius (`rounded-lg`) to create a softer, more inviting look for photography.
*   **Imagery:** Always use rounded corners for photos to maintain the design system's soft, elegant aesthetic.

## Components

### Buttons
*   **Primary:** Solid Deep Navy background with White text. High-contrast and authoritative.
*   **Secondary:** White background with Deep Navy border and Sky Blue text on hover.
*   **Tertiary/Ghost:** No background, Deep Navy text, used for less urgent actions like "View Map."

### Input Fields & Search
Search bars are the centerpiece of the travel experience. They should feature a clean 1px border, 8px roundedness, and use the Primary Navy for the focus state. Use Sky Blue for the search icon to draw the eye.

### Destination Cards
Cards should feature a large image at the top with a 16px corner radius. The content area below uses `body-md` for descriptions and the Tertiary Gold for star ratings or "Premium" badges.

### Chips & Tags
Used for categories (e.g., "All-Inclusive," "Flight + Hotel"). These should have a very light Sky Blue background (`#E0F7FF`) and Navy text to keep them legible but secondary to the main CTA.

### Navigation
The top navigation bar should be sticky with a subtle blur. Links use `label-md` for a crisp, organized appearance. Active states are indicated by a 2px Deep Navy underline.