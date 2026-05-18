---
name: Organic Kinetic
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c5c9b1'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8f937d'
  outline-variant: '#444936'
  surface-tint: '#aed53c'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c9f156'
  on-primary-container: '#556d00'
  inverse-primary: '#4f6600'
  secondary: '#c6c6c6'
  on-secondary: '#303030'
  secondary-container: '#474747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#ffffff'
  on-tertiary: '#392c3c'
  tertiary-container: '#f1dcf2'
  on-tertiary-container: '#6f5f71'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c9f156'
  primary-fixed-dim: '#aed53c'
  on-primary-fixed: '#161f00'
  on-primary-fixed-variant: '#3b4d00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#f1dcf2'
  tertiary-fixed-dim: '#d5c0d5'
  on-tertiary-fixed: '#231726'
  on-tertiary-fixed-variant: '#514253'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
  electric-lime: '#D6FF62'
  absolute-black: '#000000'
  pure-white: '#FFFFFF'
  dark-grey: '#1A1A1A'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 96px
    fontWeight: '900'
    lineHeight: 90px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '900'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 36px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 4px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system is built on a "Techno-Organic" philosophy, blending the precision of high-end athletic performance with the raw energy of nature. The brand personality is aggressive, high-energy, and premium, targeting a high-performance audience that values both scientific rigor and natural purity.

The design style utilizes **High-Contrast / Bold** aesthetics with a touch of **Minimalism**. It relies on massive, impactful typography, heavy black surfaces, and a singular high-vibrancy accent to create a sense of urgency and elite quality. Visuals are stripped of unnecessary decoration to focus purely on motion, strength, and clarity.

## Colors

The palette is intentionally restricted to maximize visual impact. The primary "Electric Lime" (#D6FF62) serves as the "honey-gold" evolution—a high-visibility, neon-inflected yellow-green that signifies energy and organic life. 

The background is strictly "Absolute Black," providing a void-like depth that makes the primary color and typography "pop." White is used exclusively for functional text and core data points. All secondary surfaces should use "Dark Grey" (#1A1A1A) to maintain depth without breaking the high-contrast immersion.

## Typography

The typography strategy mirrors the "GT America" aesthetic using modern, accessible alternatives. 

**Hanken Grotesk** is used for headlines to provide a sharp, technical, yet muscular feel. Display sizes should be set with tight kerning and leading to create dense, impactful blocks of text. 

**Inter** provides a neutral, highly legible foundation for all body copy, ensuring that information remains the priority in data-heavy sections.

**JetBrains Mono** is introduced for labels and technical metadata, reinforcing the "lab-tested" and scientific aspect of the brand.

## Layout & Spacing

The design system utilizes a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). 

Layouts should favor asymmetrical compositions to evoke a sense of movement. Large "dead zones" of black space are encouraged to drive focus toward specific CTAs or product imagery. 

Spacing follows a strict 4px base unit. Margins are generous (64px+) on desktop to create a premium, editorial feel, while mobile margins are tighter (16px) to maximize screen real estate for high-impact typography.

## Elevation & Depth

This system rejects traditional shadows in favor of **Tonal Layers** and **Low-contrast Outlines**. 

Depth is communicated through stacking shades of black and dark grey. Elements that need to stand out from the background should use a subtle 1px border of `dark-grey` (#1A1A1A) rather than a shadow.

For interactive elements or high-priority modals, a subtle "Electric Lime" outer glow (0px blur, 2px spread, low opacity) can be used to simulate a neon-like emission, suggesting that the element is "powered on."

## Shapes

The shape language is **Sharp (0)**. 

To maintain the aggressive and high-performance aesthetic, all buttons, cards, and input fields must use 90-degree angles. Any deviation from sharp corners—such as circular icons or profile photos—should be contained within square frames to maintain the rigid structural integrity of the design system.

## Components

### Buttons
Primary buttons are solid `electric-lime` with `absolute-black` text, using `label-caps` typography. They feature no rounding and use a "fill-on-hover" inversion effect. Secondary buttons are `absolute-black` with a 2px `electric-lime` border.

### Inputs
Text fields are transparent with a 1px `pure-white` bottom border only. Labels use `label-caps` and sit above the field. Errors are signaled by the border changing to a high-saturation red, though the primary accent remains the dominant indicator.

### Cards
Cards are defined by their content rather than containers. Use a subtle `dark-grey` background only when necessary to group disparate elements. Otherwise, use typography size and "Electric Lime" accents (like a vertical 4px bar on the left edge) to define card boundaries.

### Chips/Tags
Use `label-caps` inside a small `dark-grey` box. For "Active" or "Live" statuses, use a small 8px square of `electric-lime` next to the text to simulate a status light.

### Lists
Lists should be separated by thin `dark-grey` horizontal rules. Hover states on list items should trigger a full-row background color change to `dark-grey` and shift text color to `electric-lime`.