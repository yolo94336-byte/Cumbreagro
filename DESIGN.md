---
name: Agricultural Intelligence
colors:
  surface: '#fff8f5'
  surface-dim: '#ffd2a7'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1e7'
  surface-container: '#ffeada'
  surface-container-high: '#ffe3cc'
  surface-container-highest: '#ffdcbd'
  on-surface: '#2c1600'
  on-surface-variant: '#414844'
  inverse-surface: '#482904'
  inverse-on-surface: '#ffeee0'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#116c4a'
  on-secondary: '#ffffff'
  secondary-container: '#a1f4c8'
  on-secondary-container: '#1b724f'
  tertiary: '#401b1b'
  on-tertiary: '#ffffff'
  tertiary-container: '#5a302f'
  on-tertiary-container: '#d29895'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#a1f4c8'
  secondary-fixed-dim: '#86d7ad'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#f5b7b4'
  on-tertiary-fixed: '#331111'
  on-tertiary-fixed-variant: '#673a39'
  background: '#fff8f5'
  on-background: '#2c1600'
  surface-variant: '#ffdcbd'
typography:
  display:
    fontFamily: Manrope
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h2:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.3'
  h3:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
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
  container-max: 1280px
  gutter: 24px
  margin: 32px
  section-padding: 120px
---

## Brand & Style

The design system is anchored in the intersection of biological heritage and technological advancement. It evokes a sense of "Agricultural Intelligence"—a bridge between the deep, rooted traditions of Misiones and the precise, clinical world of biotechnology.

The visual style is **Corporate / Modern** with a strong leaning toward **Minimalism**. It prioritizes high-impact institutional presence through generous whitespace, sophisticated color transitions, and a strict adherence to grid systems. To soften the technical edge, subtle organic patterns—such as topographic contours and cellular leaf structures—are used as low-opacity overlays on secondary containers. 

The emotional response is one of prestige, reliability, and innovation. This is achieved by combining high-saturation natural greens with warm, earthy neutrals, ensuring the digital experience feels as grounded as the soil it represents.

## Colors

This design system utilizes a palette that reflects both the dense forest and the laboratory. 

- **Primary & Secondary Greens:** The Deep Forest Green (#1B4332) serves as the foundation for institutional authority and dark-mode sections. The Leaf Green (#40916C) provides a vibrant, living contrast for secondary elements and iconography.
- **Earth/Sand Tones:** The Sand (#F0EAD6) and Earth (#D4A373) tones act as structural anchors, preventing the UI from feeling too cold or overly "tech." They are used for subtle backgrounds and grouping elements.
- **Accent:** The Soft Orange (#FB8500) is reserved exclusively for high-priority Call to Actions (CTAs) and critical wayfinding, ensuring maximum conversion and visibility against green backgrounds.
- **Surface Strategy:** Use the Warm White (#FDFCF0) for the main canvas. Transitions to Deep Forest Green sections should be used for impact-driven content like keynote speakers or manifesto statements.

## Typography

The typography system balances the refined geometry of **Manrope** for headings with the systematic clarity of **Inter** for functional text. 

Headlines must be authoritative and large, often set in high-weight variants to command attention in hero sections. Use tight letter-spacing on display sizes to create a more custom, editorial feel. 

Body text is optimized for legibility in long-form biotechnology reports and speaker bios. The "label-caps" style is specifically intended for breadcrumbs, metadata, and small eyebrow headers above main titles, reinforcing the institutional aesthetic.

## Layout & Spacing

This design system follows a **Fixed Grid** model for desktop, centered within the viewport. A 12-column grid provides the framework for content alignment, with generous gutters to maintain the minimalist feel.

The spacing rhythm is based on a factor of 8px. Horizontal padding in sections is intentionally large (120px+) to create a focused reading experience and emphasize high-quality imagery. Elements within cards and components should use a consistent 24px or 32px internal padding to ensure "breathability."

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layers**. Rather than using harsh black shadows, this system uses low-opacity shadows tinted with the Primary Forest Green (e.g., #1B4332 at 8-12% opacity). This ensures that raised elements like cards feel like they belong to the organic environment.

Depth is also created through color-blocking:
1. **Level 0 (Canvas):** Warm White.
2. **Level 1 (Sub-sectioning):** Earth/Sand tones.
3. **Level 2 (Active elements):** White cards with soft, diffused shadows.
4. **Overlay:** Use semi-transparent blurs (8px-12px) for navigation bars when scrolling to maintain context of the background imagery.

## Shapes

The shape language is sophisticated and approachable, utilizing a **Rounded** (0.5rem base) strategy. 

- **Cards & Primary Containers:** Use a radius of 1rem (16px) to echo the organic nature of seeds and leaves.
- **Buttons & Small UI Elements:** Use a radius of 0.5rem (8px). 
- **Image Masks:** Occasionally use organic, non-uniform blobs or "leaf-cut" shapes for featured imagery to break the rigidity of the grid and reinforce the biotechnology theme.

## Components

### Buttons
- **Primary:** Soft Orange (#FB8500) background with white text. Bold, sans-serif, uppercase. High-contrast and reserved for "Register" or "Submit."
- **Secondary:** Deep Forest Green border with transparent background or Leaf Green solid.
- **Ghost:** Text-only with an arrow icon, used for "Read More" in bios or news.

### Cards
- **Speaker/Session Cards:** White background, 16px corner radius, soft forest-tinted shadow. Use a 2px top border in Leaf Green to add a professional "institutional" stripe.
- **Bio-Tech Feature Cards:** Subtle topographic pattern overlay in the background with a 10% opacity.

### Inputs & Fields
- **Search/Forms:** Warm White background with a 1px border in Earth tone (#D4A373). On focus, the border shifts to Leaf Green with a soft outer glow.

### Additional Components
- **Topographic Dividers:** Subtle, wavy horizontal lines that separate major sections instead of straight geometric lines.
- **Stat Blocks:** Large Manrope numbers in Deep Forest Green, paired with small Inter labels in Earth tones, used to highlight agricultural impact metrics.
- **Status Chips:** Small, rounded-full labels for session categories (e.g., "Biotechnology," "Sustainability") using the Sand tone background and Deep Green text.