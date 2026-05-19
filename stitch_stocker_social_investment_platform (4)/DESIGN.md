---
name: 'Organic Kinetic: Stocker'
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c5c9b1'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#8f937d'
  outline-variant: '#444936'
  surface-tint: '#aed53c'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c9f156'
  on-primary-container: '#556d00'
  inverse-primary: '#4f6600'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#ffffff'
  on-tertiary: '#313030'
  tertiary-container: '#e5e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c9f156'
  primary-fixed-dim: '#aed53c'
  on-primary-fixed: '#161f00'
  on-primary-fixed-variant: '#3b4d00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
  absolute-black: '#000000'
  electric-lime: '#D6FF62'
  pure-white: '#FFFFFF'
  dark-grey: '#1A1A1A'
  success-green: '#2ECC71'
  error-red: '#FF3B30'
typography:
  display-xl:
    fontFamily: Cairo
    fontSize: 96px
    fontWeight: '900'
    lineHeight: 100px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Cairo
    fontSize: 48px
    fontWeight: '900'
    lineHeight: 52px
  headline-lg:
    fontFamily: Cairo
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Cairo
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 38px
  headline-md:
    fontFamily: Cairo
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Tajawal
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Tajawal
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: jetbrainsMono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  data-mono:
    fontFamily: jetbrainsMono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  base: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 48px
---

## Brand & Style

The design system is a high-performance fusion of "Techno-Organic" aesthetics and aggressive financial precision. It is designed for the Egyptian investor who demands both professional-grade reliability and the raw energy of modern FinTech. The brand personality is bold, high-octane, and uncompromisingly technical.

The chosen style is a blend of **Brutalism** and **High-Contrast / Bold** modernism. It utilizes a zero-radius philosophy to project strength and structural integrity. The interface relies on massive, impactful typography and a void-like black background to create an environment where data and action items vibrate with intensity. All decorative flourishes are stripped away to focus on the speed of the Egyptian Exchange (EGX).

## Colors

The palette is engineered for maximum contrast in low-light environments, prioritizing the "Electric Lime" accent as a signal of growth and energy. 

- **Primary (Electric Lime):** Used for primary actions, positive stock trends, and active states. It represents the "kinetic" energy of the market.
- **Background (Absolute Black):** The foundation of the UI. It provides an infinite depth that eliminates visual noise and allows the typography to command attention.
- **Neutral (Dark Grey):** Used for secondary containers, inactive states, and structural dividers to maintain a monochromatic hierarchy without using shadows.
- **Pure White:** Reserved for core data, body text, and primary information to ensure 100% legibility against the black void.

## Typography

The typography system is dual-language by design, optimized for Arabic (RTL) as the primary experience. 

- **Cairo** is the headline workhorse. Its modern, geometric construction scales beautifully for massive display figures, common in stock price visualisations.
- **Tajawal** serves as the body typeface, providing a clean, technical, and open feel that mirrors the neutrality of Inter while maintaining perfect Arabic legibility.
- **JetBrains Mono** is utilized for stock tickers, percentage changes, and metadata. Its monospaced nature ensures that fluctuating numbers do not cause layout shifts.

For RTL layouts, all alignment, tracking, and leading are preserved, ensuring the "muscular" block-text aesthetic remains consistent when switching between English and Arabic.

## Layout & Spacing

This design system follows a **Fluid Grid** for mobile and a **Fixed 12-Column Grid** for desktop. 

- **RTL Logic:** The layout mirrors horizontally for Arabic. The "Price Chart" or "Growth Trend" remains the focal point, with labels and sidebars flipping to the right. 
- **Rhythm:** A 4px base unit governs all dimensions.
- **Margins:** Generous desktop margins (64px) create an elite, gallery-like feel for investment portfolios. Mobile layouts compress this to 16px to maximize the density of financial data.
- **Composition:** Use asymmetrical layouts for social feeds and leaderboards to suggest movement. Large areas of "Absolute Black" should be used to isolate high-value CTA buttons.

## Elevation & Depth

In line with the Techno-Organic aesthetic, traditional shadows are prohibited. Depth is achieved through **Tonal Layering** and **High-Contrast Borders**.

- **Level 0 (Background):** Absolute Black (#000000).
- **Level 1 (Containers/Cards):** Dark Grey (#1A1A1A) with no border.
- **Level 2 (Active/Floating):** Dark Grey with a 1px Electric Lime or Pure White border.
- **Interaction:** High-priority items (like a "Buy" button in a social feed) use a 0px blur, 2px spread "Electric Lime" glow to simulate a powered-on, neon state.
- **Dividers:** Use 1px Dark Grey lines for list item separation to maintain a flat, architectural feel.

## Shapes

The shape language is strictly **Sharp (0)**. 

Every UI element—from primary buttons to investment cards and input fields—must feature 90-degree corners. This rigidity reinforces the "Stocker" brand's focus on precision and structural stability. Circular elements (like user avatars in leaderboards) must be housed within square frames or defined by a square 1px border to maintain the system's geometric purity.

## Components

### Investment Icons
Custom icons for asset classes (Stocks, Funds, Metal, Fixed Income) use 2px stroke weights with sharp terminals. They are never enclosed in circles; if a container is needed, use a square.

### Social Investing Cards
- **Leaderboard Cards:** Sharp-edged rows. The user's rank is displayed in `display-xl` (Cairo) for impact. The "Electric Lime" bar is used on the leading edge (right for Arabic, left for English) to indicate a "top-tier" status.
- **Feed Posts:** Minimalist cards with a 1px `dark-grey` top and bottom border. The "Buy" button is pinned to the bottom right (LTR) or bottom left (RTL) as a solid `electric-lime` square.

### Buttons & Chips
- **Primary Action:** Solid `electric-lime` with `absolute-black` text. 0px radius.
- **Status Chips:** `dark-grey` background with `label-caps`. Active stocks feature a 4px `electric-lime` square (the "Live" indicator) preceding the text.

### Gift Cards
Digital investment gift cards are styled with a full-bleed `electric-lime` background and `absolute-black` typography, functioning as a high-contrast physical object within the digital space.

### Input Fields
Transparent backgrounds with a 2px `pure-white` bottom border only. On focus, the border shifts to `electric-lime`.