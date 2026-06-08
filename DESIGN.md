---
name: Industrial Excellence
colors:
  surface: '#f9f9f6'
  surface-dim: '#dadad7'
  surface-bright: '#f9f9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f1'
  surface-container: '#eeeeeb'
  surface-container-high: '#e8e8e5'
  surface-container-highest: '#e2e3e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#41484c'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f1f1ee'
  outline: '#72787d'
  outline-variant: '#c1c7cd'
  surface-tint: '#38637c'
  primary: '#002435'
  on-primary: '#ffffff'
  primary-container: '#063b52'
  on-primary-container: '#7ba5c0'
  inverse-primary: '#a1cce8'
  secondary: '#516165'
  on-secondary: '#ffffff'
  secondary-container: '#d4e5ea'
  on-secondary-container: '#57676b'
  tertiary: '#00262e'
  on-tertiary: '#ffffff'
  tertiary-container: '#003d49'
  on-tertiary-container: '#52acc3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c5e7ff'
  primary-fixed-dim: '#a1cce8'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#1e4b63'
  secondary-fixed: '#d4e5ea'
  secondary-fixed-dim: '#b9c9ce'
  on-secondary-fixed: '#0e1e22'
  on-secondary-fixed-variant: '#3a494d'
  tertiary-fixed: '#adecff'
  tertiary-fixed-dim: '#7bd3ea'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5d'
  background: '#f9f9f6'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e0'
  slate-muted: '#5A7080'
  soft-sky: '#B6D7E8'
  pure-white: '#FFFFFF'
  surface-alt: '#EFEFEF'
typography:
  hero-lg:
    fontFamily: Nunito Sans
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  hero-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  section-title:
    fontFamily: Nunito Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  section-title-mobile:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  card-title:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.4'
  body-main:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 160%
  body-small:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 150%
  label-caps:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
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
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style

This design system embodies the precision and scale of global industrial manufacturing. The brand persona is defined by **Manufacturing Excellence** and **Technical Expertise**, manifesting in a UI that feels reliable, sophisticated, and undeniably professional.

The visual style is **Corporate / Modern** with a lean towards **Minimalism**. It leverages high-contrast layouts, expansive whitespace, and a structured grid to reflect the efficiency of modern production lines. While the core is grounded and sturdy, the inclusion of glassmorphic elements for data visualization adds a layer of technical sophistication, signaling a forward-thinking approach to traditional industry.

## Colors

The palette is anchored by **Dark Prussian Blue**, evoking authority and depth. This is balanced against a **Chiffon Beige** background, which provides a warmer, more premium feel than a standard sterile white. 

**Light Cyan** serves as a soft secondary layer to bridge the gap between the dark primary and light backgrounds. Accents of **Teal** (#2F8FA5) are reserved for technical callouts and interactive highlights. High contrast is maintained throughout to ensure legibility and a sense of "cleanroom" precision.

## Typography

The design system utilizes **Nunito Sans** across all levels to maintain a cohesive, modern humanist feel that remains highly readable in technical contexts. 

Headlines utilize heavy weights and tight letter spacing to project strength. Body copy is intentionally set with a generous 160% line height to enhance the "spacious" and "clean" requirement of the brand. Small text and uppercase labels are used for technical metadata and secondary navigation, ensuring a clear information hierarchy even in data-heavy views.

## Layout & Spacing

A **Fixed Grid** model is employed for desktop resolutions (1440px max-width) to ensure the visual composition remains tightly controlled and professional. 

- **Desktop:** 12-column grid with 24px gutters and 80px side margins. 
- **Tablet:** 8-column grid with 24px gutters and 40px side margins.
- **Mobile:** 4-column grid with 16px gutters and 20px side margins.

Spacing follows an 8px base unit. Large-scale vertical rhythm is established by generous 120px gaps between major sections, reinforcing the "Global Scale" and "Spacious" visual language. Alternating image-content blocks should utilize 50/50 or 60/40 splits to maintain balance.

## Elevation & Depth

Hierarchy is primarily achieved through **Tonal Layers** rather than heavy shadows. The base layer is Chiffon Beige, with primary content cards appearing in Pure White.

**Glassmorphism** is applied specifically to "Stats Cards" and technical overlays:
- **Backdrop Blur:** 12px to 20px.
- **Surface:** White at 60-80% opacity.
- **Border:** 1px solid white at 30% opacity.

For standard cards, use an **Ambient Shadow**: a very soft, diffused Y+10, Blur 30, with a low-opacity Prussian Blue tint (#063B52 at 0.05 opacity) to ground elements without creating visual clutter.

## Shapes

The shape language combines the stability of rectangles with the approachability of rounded corners. 

- **Primary Cards:** 24px radius (`rounded-xl`).
- **Interactive Elements:** 999px radius (Full Pill) for buttons and tags.
- **Input Fields:** 8px radius (`rounded-md`) for a more structured, functional feel.

The contrast between the soft pill-shaped buttons and the large, architectural content blocks creates a modern, sophisticated aesthetic.

## Components

### Buttons
- **Primary:** Dark Prussian Blue background, White text, 999px rounded. Subtle scale-up (1.02x) on hover.
- **Secondary:** Transparent background, Dark Prussian Blue border (2px), 999px rounded.

### Header
- **Behavior:** Sticky. 
- **Transition:** Starts transparent with Dark Prussian Blue text. On scroll, transitions to a Solid Chiffon Beige or White background with a subtle bottom border.

### Bento Grids
Used for product lines. Use varying column spans (e.g., 2x2, 1x1, 1x2) with 24px gaps. Each cell should feature a high-quality product image with a text overlay in the bottom-left corner using `card-title` typography.

### Horizontal Timeline
For quality processes. A 2px solid Dark Prussian Blue line with "Nodes" represented by circles. Active stages use a Teal fill; pending stages use a White fill with a Slate border.

### Stats Cards
Utilize the Glassmorphism style. Large numerical data should be in Prussian Blue, centered, with a small `label-caps` descriptor underneath.

### Input Fields
Chiffon Beige background with a 1px border of Slate-Muted. Focus state changes border to Teal and adds a soft Teal outer glow.