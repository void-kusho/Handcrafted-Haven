---
name: Archival Artisan
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#56423d'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#89726c'
  outline-variant: '#dcc1ba'
  surface-tint: '#9c4329'
  primary: '#994127'
  on-primary: '#ffffff'
  primary-container: '#b8583d'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb5a0'
  secondary: '#6f5b44'
  on-secondary: '#ffffff'
  secondary-container: '#fadec1'
  on-secondary-container: '#75614a'
  tertiary: '#536229'
  on-tertiary: '#ffffff'
  tertiary-container: '#6b7b3f'
  on-tertiary-container: '#fbffe4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#7d2c14'
  secondary-fixed: '#fadec1'
  secondary-fixed-dim: '#dcc2a7'
  on-secondary-fixed: '#271907'
  on-secondary-fixed-variant: '#56432f'
  tertiary-fixed: '#d9eaa3'
  tertiary-fixed-dim: '#bdce89'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#3e4c16'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Literata
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Literata
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 80px
---

## Brand & Style

The design system is rooted in the "Archival Aesthetic"—a visual language that balances the raw, tactile nature of a maker's studio with the sophisticated curation of a high-end gallery. It is designed to evoke a sense of heritage, intentionality, and warmth.

The style leans into **Minimalism with a Tactile twist**. It prioritizes heavy whitespace (the "canvas") to allow product photography to breathe, while using rich, earthy accents to ground the experience. The interface should feel like a physical catalog: structured, rhythmic, and enduring. 

**Target Audience:** Discerning collectors, ethical consumers, and independent artisans who value story over mass production.
**Emotional Response:** Grounded, inspired, and trusting.

## Colors

The palette is derived from natural pigments and raw materials. 

- **Primary (Terracotta):** Used for key actions and brand moments. It represents fired clay and human touch.
- **Secondary (Clay):** A grounding neutral-adjacent tone for secondary UI elements and metadata.
- **Tertiary (Sage):** Used sparingly for success states or to denote organic/natural product categories.
- **Background (Cream Canvas):** The foundation of the entire system. It is softer than pure white, reducing eye strain and providing a premium, "paper-like" feel.
- **Text (Deep Charcoal):** High-contrast for legibility but softer than pure black to maintain the warm atmosphere.

All color combinations must adhere to WCAG 2.1 Level AA standards. Ensure the Terracotta (#C05E42) is used against the Cream Canvas for clear visibility.

## Typography

This design system utilizes a traditional serif/sans-serif pairing to establish hierarchy.

- **Literata (Serif):** Used for headlines, storytelling, and editorial quotes. Its warm, bookish nature reinforces the archival theme. 
- **Inter (Sans-Serif):** Used for functional UI, navigation, and long-form body text. It provides a contemporary, clean counterpoint to the serif, ensuring the platform feels modern and efficient.

**Usage Notes:**
- Use `display-lg` sparingly for hero sections.
- `label-md` should be used for category tags and button text, often in uppercase with slight tracking to enhance the "archival tag" look.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop (max-width 1440px) and a **Fluid Grid** on mobile devices.

- **Desktop:** 12-column grid with 24px gutters. Large side margins (80px+) are encouraged to create a "gallery wall" effect.
- **Mobile:** 4-column grid with 16px margins.
- **Rhythm:** All spacing (padding, margins, gap) must be multiples of the 4px base unit. 

The layout should prioritize verticality and "breathing room." Avoid crowding elements; if in doubt, increase the spacing to the next increment in the scale.

## Elevation & Depth

To maintain the tactile, archival feel, this design system avoids aggressive drop shadows. Depth is communicated through **Tonal Layers** and **Soft Ambient Shadows**.

- **Surface Levels:** 
  - Level 0: Cream Canvas (Background).
  - Level 1: White (Cards/Modals).
- **Shadows:** Use extremely diffused, low-opacity shadows (e.g., `rgba(45, 45, 45, 0.05)`) with a high blur radius to simulate natural light in a studio. 
- **Interaction:** On hover, product cards may lift slightly by increasing the shadow spread and blur, subtly emphasizing the "object" nature of the item.
- **Outlines:** Use 1px solid borders in "Clay" (#8D775F) at 20% opacity for subtle definition between elements without adding visual weight.

## Shapes

The shape language is **Soft** but structured. 

- **Primary Elements:** Buttons and input fields use a `0.25rem` (4px) radius. This provides a hint of friendliness while maintaining a professional, architectural edge.
- **Containers:** Product cards and large image containers use `rounded-lg` (8px) to soften the "frame" of the artisan work.
- **Decorative Elements:** Occasional use of "Pill-shaped" tags for status indicators (e.g., "In Stock") to differentiate them from functional buttons.

## Components

### Buttons
- **Primary:** Solid Terracotta (#C05E42) with White text. Rectangular with slight rounding. High-contrast and clear.
- **Secondary:** Outlined Clay (#8D775F) with 1px stroke. Used for less urgent actions like "View Details."
- **Ghost:** Deep Charcoal text with no background. Used for utility links in navigation.

### Product Cards
- Background: Pure White (#FFFFFF).
- Border: 1px subtle clay outline or soft ambient shadow.
- Content: Full-width imagery at the top, followed by `headline-md` for the title and `body-md` for the price.
- Interaction: Image scale-up (1.05x) on hover within the container mask.

### Input Fields
- Background: Cream Canvas (slightly darker than the page background).
- Border: 1px Clay (#8D775F) at 40% opacity.
- Focus State: 2px Terracotta (#C05E42) border with no outer glow.

### Navigation
- A clean, horizontal header with the logo centered or far-left.
- Utilize wide spacing between menu items (32px+).
- Use `label-md` for navigation links to ensure a structured, curated feel.

### Chips & Tags
- Used for "Artisan Type" or "Material." 
- Small, uppercase text with a Sage (#8A9A5B) background at 10% opacity and Sage text for a soft, organic look.

### CSS Tool
- Tailwind CSS
