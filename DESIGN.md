---
name: Executive Distinction
colors:
  surface: '#fcf8f9'
  surface-dim: '#dcd9da'
  surface-bright: '#fcf8f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f4'
  surface-container: '#f0edee'
  surface-container-high: '#eae7e8'
  surface-container-highest: '#e5e2e3'
  on-surface: '#1b1b1c'
  on-surface-variant: '#44474e'
  inverse-surface: '#303031'
  inverse-on-surface: '#f3f0f1'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#495f82'
  primary: '#001026'
  on-primary: '#ffffff'
  primary-container: '#0b2545'
  on-primary-container: '#778db2'
  inverse-primary: '#b1c7f0'
  secondary: '#755b00'
  on-secondary: '#ffffff'
  secondary-container: '#fed255'
  on-secondary-container: '#735a00'
  tertiary: '#0d1012'
  on-tertiary: '#ffffff'
  tertiary-container: '#222528'
  on-tertiary-container: '#898c8f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#b1c7f0'
  on-primary-fixed: '#001c3b'
  on-primary-fixed-variant: '#314769'
  secondary-fixed: '#ffe08e'
  secondary-fixed-dim: '#ecc246'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#e0e3e6'
  tertiary-fixed-dim: '#c4c7ca'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#44474a'
  background: '#fcf8f9'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e3'
typography:
  display-lg:
    fontFamily: Source Serif 4
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 128px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

The design system is engineered to project the prestige, authority, and public trust associated with high-level government leadership. It balances the sobriety of institutional service with the modern elegance of a high-profile executive biography. The target audience includes international dignitaries, policy makers, and the general public, requiring an interface that is both highly accessible and undeniably premium.

The aesthetic blends **Modern Minimalism** with subtle **Glassmorphism**. It utilizes expansive white space (Apple-inspired) to create a sense of calm and clarity, allowing the officer's achievements and vision to take center stage. The visual narrative is one of transparency, stability, and forward-thinking leadership.

## Colors

The palette is rooted in traditional government power colors, refined for a digital-first executive presence.

- **Primary (Navy Blue):** Used for primary navigation, headings, and high-emphasis buttons to convey depth and reliability.
- **Secondary (Gold):** Applied sparingly for highlights, call-to-actions, and active states to denote excellence and premium quality.
- **Surface (Light Gray):** Provides subtle distinction between content blocks without introducing visual noise.
- **Background (Pure White):** The primary canvas, ensuring maximum readability and a clean, high-end feel.
- **Text (Neutral):** A deep near-black is used for body text to maintain high contrast against the white and light gray surfaces.

## Typography

This design system employs a dual-typeface strategy to communicate both authority and accessibility.

- **Headings:** Source Serif 4 provides a scholarly, institutional weight. It is used for all display and headline roles to evoke the feel of a premium broadsheet or official state document.
- **Body & Interface:** Public Sans—originally designed for government use—ensures absolute clarity. It is neutral, professional, and highly legible across all devices.
- **Scaling:** On mobile devices, display sizes are aggressively scaled down to maintain visual hierarchy without overwhelming the smaller viewport.

## Layout & Spacing

The layout follows a **Fixed Grid** approach for desktop to maintain the "editorial" feel of an executive biography. Content is centered within a 1280px container.

- **Desktop:** A 12-column grid with generous 32px gutters. Section vertical spacing is intentionally large (128px) to provide "breathing room" between major life/career milestones.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column fluid grid. Section gaps are reduced to 64px.
- **Alignment:** Content is generally left-aligned to mirror official document structures, though hero sections may utilize centered typography for maximum impact.

## Elevation & Depth

Visual hierarchy is achieved through a combination of subtle tonal shifts and modern layering techniques:

- **Tonal Layering:** Surfaces use the Light Gray (#F5F7FA) against the White background to create logical groupings without heavy borders.
- **Glassmorphism:** Navigation bars and modal overlays utilize a 20px backdrop blur with a 60% translucent white fill. This creates a sophisticated, multi-dimensional feel.
- **Ambient Shadows:** Cards and interactive elements use a "floating" shadow: `0px 12px 32px rgba(11, 37, 69, 0.08)`. The shadow color is tinted with the Primary Navy Blue to ensure it feels integrated rather than muddy.

## Shapes

The design system uses a "Rounded" language to soften the formal nature of the content. 

- **Standard Elements:** Buttons and small cards use 0.5rem (8px).
- **Executive Cards:** Main profile sections and biography cards utilize `rounded-2xl` (1.5rem / 24px) to create a contemporary, approachable container.
- **Interactive States:** Subtle expansion or scaling (1.02x) is preferred over heavy color shifts.

## Components

- **Primary Buttons:** Solid Navy Blue with white text. High padding (16px 32px) and rounded-lg corners. 
- **Accent Buttons:** Gold background with Primary Navy text for secondary CTAs (e.g., "Download Brief").
- **Cards:** White background with a 1px Light Gray border or the ambient shadow defined in the Elevation section. They should feel like physical, high-quality stationary.
- **Navigation:** A glassmorphic top-bar that remains sticky. The active link is indicated by a small Gold dot or a subtle weight change in the label.
- **Timeline/Lists:** Vertical lists for career milestones should use Gold as the connector/node color, emphasizing the linear progression of the officer's career.
- **Input Fields:** Minimalist design with a bottom border that transitions to Navy Blue on focus.
- **Chips:** Used for "Areas of Expertise" or "Committees," these should be Light Gray with Navy Blue text, using small-radius corners.