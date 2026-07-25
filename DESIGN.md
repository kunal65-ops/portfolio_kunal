---
name: Ethereal Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#d0cdcd'
  on-tertiary: '#313030'
  tertiary-container: '#b4b2b2'
  on-tertiary-container: '#454544'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 80px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.15em
  button:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 2rem
  margin-desktop: 5rem
  margin-mobile: 1.5rem
  stack-lg: 8rem
  stack-md: 4rem
  stack-sm: 2rem
---

## Brand & Style

This design system is a fusion of **Cinematic Minimalism** and **Editorial Luxury**. It is engineered to evoke an emotional response of prestige, quiet confidence, and timelessness. Taking inspiration from high-end fashion journals and noir cinematography, the interface prioritizes content as art, utilizing expansive whitespace (negative space) and sophisticated motion to guide the user's eye.

The visual language leverages **Glassmorphism** to create a sense of depth and atmospheric layering without breaking the monochromatic discipline. The aesthetic is "quiet luxury"—where the quality of typography and the precision of the layout communicate value more than overt ornamentation. It is designed for high-end creative portfolios, luxury architectural firms, and premium lifestyle brands.

## Colors

The palette is a strictly curated **Dark Grayscale** hierarchy punctuated by a single, precious metal accent.

- **Backgrounds:** Utilize a deep charcoal (#121212) as the base canvas to ensure the white serif typography and high-contrast imagery remain the focal point.
- **Primary Accent:** Gold (#D4AF37) is reserved strictly for high-priority calls to action, active states, or subtle brand markers. It should be used sparingly (the "60-30-10" rule) to maintain its perceived value.
- **Glassmorphism:** Surfaces use a semi-transparent white tint with a heavy backdrop blur (20px-40px). This creates a "frosted obsidian" effect that allows background colors to bleed through softly.
- **Typography:** White (#FFFFFF) for headers to maximize legibility against dark backgrounds; Soft Gray (#8E8E8E) for metadata and secondary body text to establish a clear information hierarchy.

## Typography

The typographic strategy balances **Heritage and Modernity**.

- **Display & Headlines:** Playfair Display provides a literary, authoritative voice. Use it for names, project titles, and section headers. High-contrast strokes in the font reflect the editorial influence.
- **Body & UI:** Manrope is used for all functional text. Its geometric yet approachable structure ensures high readability and a contemporary feel that prevents the serif from feeling "dated."
- **Editorial Polish:** Use `label-caps` for eyebrows, project categories, and small navigation items. The increased letter-spacing is critical for the premium look.
- **Scale:** On mobile, display sizes should aggressively scale down, but maintain their line-height ratios to preserve the "high-fashion" layout feel.

## Layout & Spacing

This design system employs a **Fluid Editorial Grid** that prioritizes asymmetric balance.

- **Desktop (1440px+):** A 12-column grid with generous 80px (5rem) outer margins. Content is often intentionally offset—for example, a headline might span columns 2-6 while the body text starts at column 8—to create visual tension and interest.
- **Rhythm:** Vertical spacing is intentionally "over-indexed." Use `stack-lg` (128px) between major sections to allow the user's eyes to "rest" before moving to the next piece of content.
- **Mobile:** Transition to a 4-column grid with 24px margins. Elements that were horizontally offset on desktop should reflow into a clean vertical stack.
- **Safe Areas:** Ensure all glassmorphic overlays maintain a minimum of 32px padding from their internal content to preserve the "airy" feel.

## Elevation & Depth

Hierarchy is established through **Luminance and Blur** rather than traditional drop shadows.

- **Base Layer:** The deepest charcoal background (#0D0D0D).
- **Mid Layer (Cards/Panels):** Semi-transparent surfaces (`rgba(255, 255, 255, 0.03)`) with a 1px border (`rgba(255, 255, 255, 0.1)`). These appear as "sheets of glass" floating over the background.
- **Top Layer (Modals/Navigation):** Higher opacity glass with a subtle "inner glow" achieved through a top-weighted border-gradient.
- **Focus States:** Instead of heavy shadows, use the Gold accent as a 1px "halo" or underline to indicate interactivity.
- **Image Treatment:** Use subtle grayscale filters on images that transition to full color on hover, reinforcing the cinematic "noir-to-life" metaphor.

## Shapes

The shape language is **Softly Structured**.

- **Standard Radius:** 0.5rem (8px) is the baseline for all cards and input fields. This softens the "brutalist" edge of the monochrome palette.
- **Large Components:** Images and primary containers use `rounded-xl` (1.5rem/24px) to emphasize the premium, modern aesthetic.
- **Interactive Elements:** Buttons can vary between standard rounded and pill-shaped (3) depending on the desired energy level; however, standard rounded is preferred for a more "architectural" look.

## Components

- **Buttons:** 
  - *Primary:* Solid Gold (#D4AF37) with black text. No shadow, but a subtle "shimmer" animation on hover.
  - *Secondary:* Ghost style with a white 1px border and white text. Fills with 10% white opacity on hover.
- **Navigation:** A persistent glassmorphic bar at the top or bottom. Links use `label-caps` typography. The active link is indicated by a small gold dot beneath the text.
- **Cards:** Bordered glass containers with 24px internal padding. Images within cards should have a 4:5 (editorial) or 16:9 (cinematic) aspect ratio.
- **Input Fields:** Underline style is preferred over boxes. A 1px light gray line that turns gold and thickens to 2px when focused. Labels should be floating `label-caps`.
- **Chips/Tags:** Small, pill-shaped outlines with `label-caps` text. Used for project categories (e.g., "PHOTOGRAPHY", "DIRECTION").
- **Lists:** Clean, high-contrast rows separated by 1px `rgba(255, 255, 255, 0.1)` lines. Hovering over a list item should trigger a subtle scale-up effect of the associated thumbnail.