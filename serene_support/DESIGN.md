---
name: Serene Support
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
  on-surface-variant: '#41474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#72787e'
  outline-variant: '#c1c7ce'
  surface-tint: '#356382'
  primary: '#0f4361'
  on-primary: '#ffffff'
  primary-container: '#2d5b7a'
  on-primary-container: '#a5d2f6'
  inverse-primary: '#9fccf0'
  secondary: '#346760'
  on-secondary: '#ffffff'
  secondary-container: '#b7ede4'
  on-secondary-container: '#3a6d66'
  tertiary: '#34424a'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b5962'
  on-tertiary-container: '#c0cfda'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cae6ff'
  primary-fixed-dim: '#9fccf0'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#194b69'
  secondary-fixed: '#b7ede4'
  secondary-fixed-dim: '#9cd1c8'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#194f49'
  tertiary-fixed: '#d6e5ef'
  tertiary-fixed-dim: '#bac9d3'
  on-tertiary-fixed: '#0f1d25'
  on-tertiary-fixed-variant: '#3b4951'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 14px
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
  lg: 40px
  xl: 64px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is engineered to provide a sanctuary for mental wellness. The brand personality is empathetic, steadfast, and clarifying. It aims to evoke an emotional response of immediate relief and long-term safety, moving away from the cold, sterile aesthetics of traditional clinical software toward a "warm-modern" digital environment.

The design style is **Modern Minimalism** infused with **Soft Tonal Layering**. It prioritizes cognitive ease through high-quality typography, intentional negative space, and a reduction of visual noise. By using organic shapes and a gentle color theory, the interface acts as a supportive companion rather than a complex tool, ensuring users feel heard and held.

## Colors

The palette is rooted in color psychology to lower cortisol levels and promote focus.

*   **Primary (Soothing Navy):** Used for primary actions and core branding. It provides a sense of authority and stability.
*   **Secondary (Soft Teal):** Used for supportive elements, success states, and progress indicators. It represents growth and vitality.
*   **Tertiary (Morning Mist):** A very light blue used for subtle backgrounds and highlighting soft information without high contrast.
*   **Neutral (Grounding Slate):** A range of cool grays that provide structure without the harshness of pure black or white.

Surface colors should prioritize high-key (light) tones to maintain an airy feel. Text should primarily use a deep navy-gray rather than black to reduce eye strain.

## Typography

This design system utilizes a dual-font approach to balance character with functionality. **Manrope** is used for headlines to provide a modern, refined, and approachable personality. Its geometric yet soft curves feel friendly and contemporary.

**Inter** is utilized for all body copy and UI labels. Chosen for its exceptional legibility and neutral "systematic" feel, it ensures that sensitive health information is consumed without friction. 

Line heights are intentionally generous (1.5x - 1.6x for body text) to prevent the "wall of text" effect, making the content feel digestible and calm.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** model with a focus on "White Space as a Feature." By increasing margins and gutters, we reduce cognitive load and allow the user’s eyes to rest.

*   **Desktop:** 12-column grid, 1200px max-width, 24px gutters.
*   **Tablet:** 8-column grid, fluid width, 24px gutters.
*   **Mobile:** 4-column grid, fluid width, 16px margins.

Vertical rhythm is strictly adhered to using an 8px base unit. Component internal padding should lean toward the larger side (e.g., using `md` or `lg` spacing) to maintain the non-clinical, airy atmosphere.

## Elevation & Depth

To maintain a sense of lightness, this design system avoids heavy, dark shadows. Instead, it utilizes **Tonal Layers** and **Ambient Shadows**.

1.  **Level 0 (Floor):** Neutral Background (#F8FAFC).
2.  **Level 1 (Cards/Surface):** Pure White (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px rgba(45, 91, 122, 0.05)).
3.  **Level 2 (Modals/Overlays):** Pure White with a slightly deeper, more expanded shadow to denote temporary focus.

Depth is also communicated through subtle background shifts (e.g., using the Tertiary blue to distinguish a sidebar from a main content area) rather than physical elevation alone.

## Shapes

The shape language is defined by **Roundedness Level 2**. 

Corners are soft and inviting, removing any "sharp" or aggressive edges from the interface. 
- **Standard Components (Buttons, Inputs):** 0.5rem (8px) radius.
- **Large Components (Cards, Sections):** 1rem (16px) radius.
- **Extra Large (Hero Sections, Modals):** 1.5rem (24px) radius.

This consistency in rounding reinforces the friendly and supportive nature of the AI platform.

## Components

### Buttons
Primary buttons use the Primary Navy color with white text. Hover states should be a subtle tint lighter, not darker, to maintain a "lifting" feel. Secondary buttons use a Soft Teal outline or a Tertiary blue fill.

### Cards
Cards are the primary container for content. They must feature a white background, 16px corner radius, and the Ambient Shadow defined in the Elevation section. Internal padding should never be less than 24px.

### Input Fields
Inputs should have a light gray border (#E2E8F0) that transitions to the Secondary Teal on focus. Use "Helper Text" liberally below inputs to provide gentle guidance and reduce form anxiety.

### Chips & Tags
Use these for mood tracking or interest categories. They should have a 100px (pill) radius and use low-saturation background colors from the Tertiary palette.

### Progress Indicators
Progress bars should be thicker (8px+) and use rounded end-caps. Use the Secondary Teal for progress to symbolize growth and positive momentum.

### Additional Components: The "Check-in" Bubble
A unique component for this system is the conversational bubble used for AI interactions. These should have disproportionate rounding (e.g., 24px on three corners and 4px on the bottom-left) to distinguish AI "speech" from standard UI cards.