---
name: Ethereal Precision
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e3'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2fd'
  surface-container: '#eeedf7'
  surface-container-high: '#e8e7f1'
  surface-container-highest: '#e3e1ec'
  on-surface: '#1a1b22'
  on-surface-variant: '#494553'
  inverse-surface: '#2f3038'
  inverse-on-surface: '#f1effa'
  outline: '#7a7485'
  outline-variant: '#cbc3d5'
  surface-tint: '#6844c7'
  primary: '#6844c7'
  on-primary: '#ffffff'
  primary-container: '#9d7bff'
  on-primary-container: '#320085'
  inverse-primary: '#cebdff'
  secondary: '#635b6e'
  on-secondary: '#ffffff'
  secondary-container: '#e9def5'
  on-secondary-container: '#696174'
  tertiary: '#6f46b9'
  on-tertiary: '#ffffff'
  tertiary-container: '#a47bf2'
  on-tertiary-container: '#38007e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e8ddff'
  primary-fixed-dim: '#cebdff'
  on-primary-fixed: '#21005e'
  on-primary-fixed-variant: '#5028ae'
  secondary-fixed: '#e9def5'
  secondary-fixed-dim: '#cdc2d9'
  on-secondary-fixed: '#1e1929'
  on-secondary-fixed-variant: '#4a4456'
  tertiary-fixed: '#ebdcff'
  tertiary-fixed-dim: '#d3bbff'
  on-tertiary-fixed: '#260059'
  on-tertiary-fixed-variant: '#572ba0'
  background: '#fbf8ff'
  on-background: '#1a1b22'
  surface-variant: '#e3e1ec'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.08em
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

The design system is defined by a serene, airy, and high-precision aesthetic. It targets sophisticated technology and creative platforms where clarity meets a dreamlike quality. The brand personality is calm yet technical, blending the intellectual authority of classic typography with the forward-looking geometry of modern interfaces.

The visual style is **Glassmorphism mixed with Minimalism**. It prioritizes heavy whitespace, subtle translucency, and a "floating" UI architecture. The emotional response should be one of focused tranquility—reducing cognitive load through soft lavender tones while maintaining a sharp, professional edge through precise line work and geometric sans-serif details.

## Colors

The palette shifts from cool blues to a sophisticated spectrum of purples. 

- **Primary (Vivid Lavender):** Used for key actions and active states. It provides enough contrast to be functional while remaining soft.
- **Secondary (Pale Lilac):** The foundation for surface backgrounds and subtle highlights. It reinforces the airy feel.
- **Tertiary (Deep Violet):** Reserved for high-contrast accents, text hierarchy, and grounding elements.
- **Neutral:** A range of cool grays with a slight purple tint to ensure harmony across the interface.

Surfaces should leverage semi-transparency (70-80% opacity) against a very light lilac-white background to achieve the ethereal, layered effect.

## Typography

This design system utilizes a high-contrast typographic pairing. **EB Garamond** (chosen as a high-quality Serif alternative to Times New Roman) is used for headlines to provide a sense of timelessness and editorial prestige. **Space Grotesk** is used for all UI elements, body text, and labels to introduce a technical, geometric precision.

Headlines should use tight letter spacing and generous line heights to feel elegant. UI labels and small body text in Space Grotesk should utilize slightly increased letter spacing to enhance legibility and reinforce the "airy" theme.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** on desktop (12 columns, 1200px max-width) and a **Fluid Grid** on mobile (4 columns). 

The spacing rhythm is generous, favoring `lg` and `xl` tokens for vertical section spacing to maintain the "Ethereal" breathability. Elements are rarely cramped; negative space is treated as a functional element to guide the eye. Gutters remain consistent at 24px to provide a structured skeleton beneath the floating surfaces.

## Elevation & Depth

Depth is conveyed through **Glassmorphism and Ambient Shadows**. 

- **Surface Tiers:** Primary surfaces use a backdrop blur (12px to 20px) with a semi-transparent white-to-lilac fill. 
- **Shadows:** Instead of harsh black shadows, use "Ambient Purples"—extremely diffused shadows with low opacity (10-15%) tinted with the Primary color (#9D7BFF). This makes components appear to be floating on a bed of light.
- **Outlines:** Use thin, 1px soft-purple borders (`primary_color` at 20% opacity) to define edges without breaking the translucent effect.

## Shapes

The shape language is consistently **Rounded**. All container elements, buttons, and input fields utilize a 0.5rem (8px) base radius. This softening of the geometry balances the technical nature of the Space Grotesk typeface. For large cards and floating modals, use `rounded-xl` (1.5rem / 24px) to emphasize the "object-like" quality of the UI.

## Components

- **Buttons:** Primary buttons should be solid Lavender (#9D7BFF) with white text. Secondary buttons use a lilac ghost style: transparent background, 1px lilac border, and lilac text.
- **Chips:** Highly rounded (pill-shaped) with a very pale lilac background and deep violet text. Use these for categorization and filtering.
- **Inputs:** Use a soft-white background with a 1px pale lilac border. On focus, the border should glow with the Primary Lavender and a subtle outer shadow.
- **Cards:** The signature component. Use `rounded-xl`, a subtle purple-tinted ambient shadow, and a 20px backdrop blur.
- **Checkboxes & Radios:** Use the Primary Lavender for active states. Maintain a 2px radius even on checkboxes to keep the "Soft" language consistent.
- **Glass Modals:** Large-scale overlays that utilize a 32px backdrop blur, effectively "veiling" the content behind them in a soft purple mist.