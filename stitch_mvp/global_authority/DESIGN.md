---
name: Global Authority
colors:
  surface: '#f7fafc'
  surface-dim: '#d7dadc'
  surface-bright: '#f7fafc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f6'
  surface-container: '#ebeef0'
  surface-container-high: '#e5e9eb'
  surface-container-highest: '#e0e3e5'
  on-surface: '#181c1e'
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#944b00'
  on-secondary: '#ffffff'
  secondary-container: '#fe9743'
  on-secondary-container: '#6b3500'
  tertiary: '#162132'
  on-tertiary: '#ffffff'
  tertiary-container: '#2b3648'
  on-tertiary-container: '#949fb4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#ffdcc5'
  secondary-fixed-dim: '#ffb783'
  on-secondary-fixed: '#301400'
  on-secondary-fixed-variant: '#703700'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

This design system is built for a global solo-preneur's information hub, prioritizing expertise, approachability, and a "built-to-scale" professional image. The visual narrative is rooted in **Modern Minimalism** with a focus on high-density information clarity. 

The aesthetic leverages expansive whitespace to provide breathing room for complex ideas, while utilizing precise, subtle shadows to establish a hierarchy of information. The result is a UI that feels established and institutional yet remains agile and personal. The target audience includes high-level stakeholders, fellow entrepreneurs, and global collaborators who value time, clarity, and precision.

## Colors

The palette is anchored by **Global Blue** (#1A365D), which serves as the foundation for headers, primary actions, and brand-heavy backgrounds. This color communicates stability and global reach. 

**Entrepreneurial Orange** (#ED8936) is reserved strictly for high-conversion Call-to-Actions (CTAs) and critical focus points to ensure they pop against the professional backdrop. 

The neutral scale utilizes **Slate Grays** (ranging from #2D3748 for text to #EDF2F7 for subtle borders) and a crisp **White** background to maintain a clean, "tech-forward" feel. Use the Tertiary Slate (#4A5568) for secondary icons and metadata to avoid visual competition with primary content.

## Typography

The design system uses **Inter** exclusively to ensure a systematic, utilitarian, and highly legible experience across all platforms. The typeface choice emphasizes the professional, tech-savvy nature of the brand.

Headlines should utilize tighter letter-spacing and heavier weights to command authority. Body copy utilizes a generous line height (1.5-1.6) to ensure long-form articles and reports are easily digestible. Use `label-caps` for eyebrows and category tags to create a clear stylistic distinction from standard body text.

## Layout & Spacing

This design system employs a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. The layout is structured around an 8px rhythm to ensure vertical alignment and visual harmony.

- **Desktop:** 1200px max-width container, centered. Margins at 40px minimum.
- **Tablet:** Full-width fluid layout with 32px side margins.
- **Mobile:** Single column layout with 16px side margins.

Use `xl` spacing (64px) between major sections to maintain the minimalist philosophy and prevent the UI from feeling cluttered. Gutters are fixed at 24px to allow content to breathe without losing its relationship to adjacent elements.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layers**. Shadows should be highly diffused and nearly invisible, mimicking a natural light source from directly above.

- **Level 1 (Cards/Inputs):** `0px 2px 4px rgba(26, 54, 93, 0.04)`. A very subtle lift to define interactive boundaries.
- **Level 2 (Dropdowns/Hover states):** `0px 10px 15px -3px rgba(26, 54, 93, 0.08)`. Used for elements that temporarily float above the canvas.
- **Level 3 (Modals):** `0px 20px 25px -5px rgba(26, 54, 93, 0.1)`. Reserved for the highest level of the stacking order.

Avoid heavy borders; instead, use light-gray strokes (#E2E8F0) in combination with these shadows for definition.

## Shapes

The design system adopts a **Soft (1)** roundedness profile. This 4px (0.25rem) base radius provides a modern, approachable feel while maintaining the structural discipline required for a professional "Global Authority" vibe. 

Large containers like cards should utilize `rounded-lg` (8px), while buttons and input fields adhere to the base 4px radius. Circular shapes are reserved exclusively for avatars and status indicators to ensure they are instantly recognizable as distinct from functional UI components.

## Components

### Buttons
- **Primary:** Global Blue background, white text. No border.
- **CTA:** Entrepreneurial Orange background, white text. Used only for "Subscribe," "Hire," or "Purchase."
- **Secondary:** Transparent background with a Global Blue 1px border.

### Input Fields
- Use a white background with a light slate border (#E2E8F0).
- On focus, the border shifts to Global Blue with a 2px outer "glow" using a 10% opacity version of the primary color.

### Cards
- White background, `rounded-lg` (8px) corners, and Level 1 shadow.
- Content within cards should follow the standard spacing rhythm (24px internal padding).

### Chips & Tags
- Use a light tint of Global Blue (e.g., #EBF8FF) with the `label-caps` typography style for categorization. 

### Progress Indicators
- For "Information Hub" features (like course progress or reading length), use a thin Global Blue bar to maintain a minimal footprint.