---
name: Stewardship Corporate System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#44474e'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#465f88'
  primary: '#000a1e'
  on-primary: '#ffffff'
  primary-container: '#002147'
  on-primary-container: '#708ab5'
  inverse-primary: '#aec7f6'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#180500'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d1500'
  on-tertiary-container: '#b97958'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aec7f6'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#6c391d'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
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
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin-desktop: 48px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for the high-stakes environment of insurance and commercial claims. The brand personality is **authoritative, meticulous, and resilient**. It avoids the coldness of traditional enterprise software by embracing a "Premium Corporate" aesthetic—balancing the sobriety of institutional finance with the fluidity of modern SaaS.

The target audience consists of adjusters, underwriters, and corporate clients who require clarity during complex processes. The UI evokes a sense of **unshakeable stability** through wide margins, a restricted color palette, and deliberate whitespace. The design style is **Modern Corporate**, utilizing subtle depth and high-quality typography to communicate precision and trustworthiness.

## Colors

The palette is anchored by **Dark Navy (#002147)**, representing institutional strength and heritage. This is the primary color for navigation, headings, and high-emphasis actions. 

**Gold (#D4AF37)** is used sparingly as a "prestige accent." It is reserved for success states, premium features, or subtle decorative elements like borders on featured cards. 

The background is a crisp **White (#FFFFFF)**, supported by a secondary surface color of **Cool Slate (#F8FAFC)** to differentiate between global navigation and content areas. Interactive neutrals use a range of grays to maintain a clean, non-distracting environment for data entry and claims review.

## Typography

The design system utilizes **Inter** for all roles to achieve a systematic, utilitarian, yet modern look. The typeface was chosen for its exceptional legibility in data-dense environments and its neutral, professional tone.

- **Headlines:** Use Bold or Semi-Bold weights with slight negative letter-spacing to create a "locked-in," authoritative feel.
- **Body:** Standardized on 16px for optimal readability in long-form claim narratives.
- **Labels:** Small labels use a higher weight (600) and increased letter-spacing to ensure they remain legible when used in dense forms or as field headers.

## Layout & Spacing

This design system follows a **Fixed-Width Grid** model for desktop to maintain the premium, "editorial" feel of a corporate report. The main content is centered within a 1280px container.

- **Desktop:** 12-column grid with 24px gutters. Large 48px external margins provide the necessary "breathing room" for a high-end feel.
- **Tablet:** 8-column grid with 24px gutters and 32px margins.
- **Mobile:** 4-column fluid grid with 16px gutters and 16px margins.

Spacing is strictly based on an **8px base unit**. All vertical stacking of elements should utilize the defined `stack` variables to ensure consistent rhythm across different modules.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. Unlike consumer-facing apps that may use heavy shadows, this design system uses "Sharp Elevation":

1.  **Level 0 (Base):** The primary background (#FFFFFF).
2.  **Level 1 (Cards):** Placed on Level 0, these cards use a very soft, diffused shadow (0px 4px 20px rgba(0, 33, 71, 0.05)) and a subtle 1px border in a light gray (#E2E8F0).
3.  **Level 2 (Modals/Popovers):** Higher contrast shadows (0px 12px 32px rgba(0, 0, 0, 0.1)) to draw focus.

The "Floating Card" effect is central to the dashboard layout, where cards appear to sit just above the surface, separated by clean white space rather than heavy borders.

## Shapes

The design system uses a **Rounded (0.5rem)** approach. This corner radius is applied to cards, input fields, and buttons. 

Larger containers (like high-fidelity feature cards) utilize `rounded-lg` (1rem) to create a softer, more approachable feel for the main dashboard elements. The consistent use of moderate rounding bridges the gap between traditional corporate "sharpness" and modern digital "softness."

## Components

### Buttons
- **Primary:** Dark Navy background, white text. No gradient. 0.5rem radius.
- **Secondary:** White background, Dark Navy 1px border. 
- **Accent:** Gold background, used only for "Finalize" or "Submit Claim" to draw the eye to the most critical action.

### High-Fidelity Grid Cards
Used for dashboard stats and main navigation. These feature a centered icon in a light navy tint, a `title-lg` header, and a `body-md` description. The card has a `rounded-lg` corner and a subtle hover state that deepens the shadow and adds a 2px Gold bottom border.

### Input Fields
Strict, rectangular forms with a 0.5rem radius. Labels are always positioned above the input in `label-sm` style. The focus state uses a 2px Dark Navy ring with a 2px offset.

### Professional Footer
A "High-Density" footer with a Dark Navy background. It contains the corporate wordmark, a sitemap, and regulatory disclosures in `label-md` white text.

### Progress Trackers
Used for claim status. Utilizes a horizontal line with Gold nodes for completed steps and Navy nodes for the active step.