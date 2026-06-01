---
name: Kinetic Professional
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#474553'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#787585'
  outline-variant: '#c9c4d5'
  surface-tint: '#5c4bc4'
  primary: '#20007a'
  on-primary: '#ffffff'
  primary-container: '#361d9d'
  on-primary-container: '#a295ff'
  inverse-primary: '#c8bfff'
  secondary: '#710fe5'
  on-secondary: '#ffffff'
  secondary-container: '#8b3dff'
  on-secondary-container: '#faf1ff'
  tertiary: '#755b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#d3a500'
  on-tertiary-container: '#503d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5deff'
  primary-fixed-dim: '#c8bfff'
  on-primary-fixed: '#190064'
  on-primary-fixed-variant: '#4430ab'
  secondary-fixed: '#ebdcff'
  secondary-fixed-dim: '#d4bbff'
  on-secondary-fixed: '#270058'
  on-secondary-fixed-variant: '#5d00c2'
  tertiary-fixed: '#ffdf92'
  tertiary-fixed-dim: '#f4bf00'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  surface-white: '#FFFFFF'
  surface-soft: '#F7F8FA'
  electric-purple: '#8B3DFF'
  deep-indigo: '#361D9D'
  accent-yellow: '#FFC800'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  button:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
  element-gap: 32px
---

## Brand & Style

This design system is engineered for a high-impact personal brand that balances professional authority with creative energy. It draws inspiration from modern digital publishing and high-end presentation design, utilizing a **Corporate Modern** foundation infused with **Minimalist** clarity.

The aesthetic focuses on "Information as Art"—where the resume content is elevated through purposeful white space, bold typographic hierarchy, and strategic bursts of vibrant color. The target audience includes recruiters, stakeholders, and collaborators who value precision, modernity, and a distinctive point of view. The UI should evoke a sense of confidence, technical proficiency, and polished sophistication.

## Colors

The palette is anchored by **Deep Indigo** and **Electric Purple**, creating a sophisticated gradient of depth that feels more contemporary than traditional black. 

- **Primary (Deep Indigo):** Used for primary headings, navigation backgrounds, and high-emphasis interactive states.
- **Secondary (Electric Purple):** Used for actionable items, links, and secondary accents to provide a sense of creativity.
- **Tertiary (Accent Yellow):** Reserved for high-importance highlights, "Open to Work" badges, or specific call-to-action details where maximum contrast is required.
- **Neutral:** A near-black charcoal (`#121212`) is used for body text to maintain readability while appearing more premium than pure black.
- **Surface:** Pure white is used for the primary canvas, with a soft cool-gray (`#F7F8FA`) for section layering.

## Typography

The typography system uses a mix of high-impact sans-serifs and a technical monospace font to create a "curated resume" feel.

- **Headlines (Hanken Grotesk):** Tight tracking and heavy weights are used for names and section titles to mirror the bold Canva-style aesthetic.
- **Body (Inter):** Chosen for its exceptional legibility at small sizes, ensuring that detailed job descriptions and bullet points remain clear.
- **Labels (JetBrains Mono):** Used for dates, categories, and technical skills. The monospaced nature adds a "metadata" feel that suggests precision and technical expertise.

Standardize on tight line-heights for headlines to keep them punchy, while maintaining generous line-heights for body text to aid long-form reading.

## Layout & Spacing

The design follows a **Fixed Grid** philosophy on desktop, centered to create a clean, editorial frame around the content. 

- **Desktop (1200px+):** A 12-column grid with generous 120px vertical gaps between major sections (Experience, Education, Projects). This creates a "slideshow" feel as the user scrolls.
- **Tablet (768px - 1024px):** 8-column grid with reduced margins.
- **Mobile (Below 768px):** Single-column layout with 20px side margins. Content should be stacked, with typography scaling down to ensure readability without excessive horizontal scrolling.

Whitespace is treated as a first-class design element; do not crowd the content. Use large paddings within cards to emphasize the premium nature of the presentation.

## Elevation & Depth

This design system uses **Tonal Layers** combined with **Ambient Shadows** to create a subtle sense of physical depth.

1.  **The Base:** The main page background is either pure white or the `surface-soft` gray.
2.  **The Cards:** Portfolio items and experience blocks are placed on white cards with a very soft, diffused shadow (`0px 10px 30px rgba(54, 29, 157, 0.05)`). The hint of the primary indigo in the shadow color ties the element to the brand.
3.  **The Interaction:** Upon hover, elements should slightly lift (move -4px on Y-axis) and the shadow should become slightly more pronounced.
4.  **Floating Elements:** Sticky navigation uses a backdrop-blur (10px) with 90% opacity white to maintain context of the content passing underneath.

## Shapes

The shape language is **Rounded**, conveying an approachable and modern personality. 

- **Containers:** Standard cards and project thumbnails use a 1rem (`rounded-lg`) corner radius.
- **Buttons:** Use a 0.5rem radius for a sturdy, professional feel.
- **Badges/Chips:** Use full-rounded (pill) shapes for skill tags and status indicators to contrast against the more structured rectangular cards.
- **Images:** Professional headshots and project hero images should follow the 1.5rem (`rounded-xl`) radius to soften the visual impact of photography.

## Components

### Buttons
- **Primary:** Deep Indigo background, white text, 0.5rem radius. Subtle lift on hover.
- **Secondary:** Electric Purple outline, 2px border, Indigo text.
- **Ghost:** No background, Indigo text, used for less frequent actions like "Download CV."

### Chips (Skills)
- Light Electric Purple background (10% opacity) with Deep Indigo text.
- Pill-shaped.
- No border, no shadow.

### Cards (Experience/Education)
- White background with the brand-tinted ambient shadow.
- 1.5rem padding.
- Use the `label-md` (JetBrains Mono) for dates at the top right of the card.

### Input Fields
- Soft gray (`surface-soft`) background.
- 2px border that transitions from gray to Electric Purple on focus.
- 0.5rem corner radius.

### Project Grid
- Large-scale imagery with an overlay that reveals the project title (`headline-md`) and a "View Project" link on hover.
- 32px gap between grid items.