---
name: Ethereal Retreat
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#4f453f'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#81756e'
  outline-variant: '#d3c4bc'
  surface-tint: '#72594a'
  primary: '#0d0300'
  on-primary: '#ffffff'
  primary-container: '#2c1a0e'
  on-primary-container: '#9d806f'
  inverse-primary: '#e1c0ad'
  secondary: '#51634d'
  on-secondary: '#ffffff'
  secondary-container: '#d3e9cd'
  on-secondary-container: '#576953'
  tertiary: '#080400'
  on-tertiary: '#ffffff'
  tertiary-container: '#251d0b'
  on-tertiary-container: '#92846b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fedcc8'
  primary-fixed-dim: '#e1c0ad'
  on-primary-fixed: '#29170c'
  on-primary-fixed-variant: '#594234'
  secondary-fixed: '#d3e9cd'
  secondary-fixed-dim: '#b8ccb1'
  on-secondary-fixed: '#0f1f0e'
  on-secondary-fixed-variant: '#394b37'
  tertiary-fixed: '#f1e0c3'
  tertiary-fixed-dim: '#d5c5a9'
  on-tertiary-fixed: '#231a08'
  on-tertiary-fixed-variant: '#504530'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: 0.05em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: 0.03em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-md:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in the concept of "The Quiet Sanctuary." It targets an affluent, wellness-conscious audience seeking a respite from digital noise. The aesthetic is rooted in **Minimalism** with an organic, editorial lean. 

Visual hierarchy is established through extreme whitespace and intentional "breathing room," rather than aggressive UI elements. The emotional response should be one of immediate deceleration—calm, professional, and deeply premium. Every element must feel curated, avoiding any hint of clutter or frantic energy. Photography is the primary storytelling tool, treated with full-bleed layouts or generous margins to act as a window into the spa experience.

## Colors

The palette is derived from natural elements: stone, earth, and flora. 

- **Background:** Deep warm ivory (#FAF7F2) serves as the canvas, providing a softer, more sophisticated feel than pure white.
- **Headings & Text:** Rich espresso brown (#2C1A0E) provides high-contrast legibility while maintaining a warmth that black lacks.
- **Accents:** Muted sage green (#8A9E85) is used sparingly for primary actions, subtle indicators, or success states, grounding the UI in a botanical context.
- **Structure:** Soft sand (#D4C4A8) is reserved strictly for hairline borders, dividers, and disabled states, ensuring structural elements remain whisper-quiet.

## Typography

Typography in the design system is a study in contrast. 

**Headlines** utilize Playfair Display in light weights. To achieve a premium, editorial feel, generous letter spacing (tracking) must be applied to all serif headings. Headlines should never be crowded; they require significant leading to maintain their elegance.

**Body Text** and functional UI elements use DM Sans. This provides a clean, modern counterpoint to the decorative serif. For labels and small utility text, use uppercase styling with increased letter spacing to maintain legibility and a sophisticated, architectural feel.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop to ensure content remains centered and curated, transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for desktop (1280px max-width).
- **Rhythm:** An 8px base unit governs all spacing. However, for section-to-section transitions, large gaps (120px+) are encouraged to emphasize the "Luxury Minimalist" aesthetic.
- **Margins:** Desktop layouts feature expansive side margins (80px) to keep the focal point tight and intentional. 
- **Reflow:** On mobile, vertical stacks are preferred with reduced margins (24px). Spacing between elements should remain generous even on smaller screens to prevent a "cramped" feeling.

## Elevation & Depth

This design system avoids traditional shadows to maintain its clean, flat-leaning aesthetic. Depth is instead communicated through:

1.  **Tonal Layers:** Using the Warm Ivory background as the base, and slightly darker Sand (#D4C4A8) or Sage (#8A9E85) tints for secondary containers.
2.  **Low-Contrast Outlines:** Elements like cards or input fields are defined by 1px solid borders in Soft Sand (#D4C4A8). This creates a "ghost" boundary that is visible but non-intrusive.
3.  **Imagery:** Depth is primarily introduced through high-quality photography with natural depth-of-field, allowing the UI to sit "above" the visual content as a transparent, functional overlay.

## Shapes

The shape language is **Soft**. While the overall layout is architectural and structured, a subtle 4px (0.25rem) corner radius is applied to buttons, cards, and input fields. This softens the "Brutalist" potential of the grid and makes the UI feel more approachable and organic, reflecting the human-centric nature of a spa. Large image containers may remain sharp (0px) to maintain an editorial, high-fashion look.

## Components

### Buttons
Primary buttons use a solid Espresso (#2C1A0E) fill with Ivory text. Secondary buttons are "ghost" style with a 1px Sand border and Espresso text. All buttons use the `label-md` typography style (uppercase, tracked out).

### Cards
Cards are defined by a 1px Soft Sand border. They should have no shadow. Padding inside cards must be generous (minimum 32px) to ensure content never feels squeezed.

### Input Fields
Fields consist of a bottom-border only (1px Soft Sand) in their default state, evolving to a full 1px border when focused. Placeholder text uses the body-md style in a muted espresso tint.

### Chips & Tags
Used for service categories (e.g., "Massage", "Facial"). These are pill-shaped with a light Sage (#8A9E85) background at 10% opacity and Sage text.

### Lists
Lists should be separated by 1px Sand horizontal rules. Item spacing should be at least 24px vertically to ensure each item feels distinct and premium.

### Additional Components
- **Booking Calendar:** Minimalist grid, no heavy borders, using Sage to highlight selected dates.
- **Image Carousels:** Thin Espresso pagination lines rather than bulky dots or arrows.