---
name: Regal Academic
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#4c4451'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#7d7483'
  outline-variant: '#cec3d3'
  surface-tint: '#7b41b3'
  primary: '#2e0052'
  on-primary: '#ffffff'
  primary-container: '#4b0082'
  on-primary-container: '#ba7ef4'
  inverse-primary: '#ddb7ff'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd400'
  on-secondary-container: '#6e5c00'
  tertiary: '#2e0052'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b0081'
  on-tertiary-container: '#be79ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0050'
  on-primary-fixed-variant: '#622599'
  secondary-fixed: '#ffe16d'
  secondary-fixed-dim: '#e9c400'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#f1dbff'
  tertiary-fixed-dim: '#deb7ff'
  on-tertiary-fixed: '#2d0050'
  on-tertiary-fixed-variant: '#680eac'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-sm:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  motto-style:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style

The brand personality is professional, aspirational, and celebratory. It reflects a decade of academic achievement through a lens of community pride and institutional stability. The design system balances the "Discipline and Hardwork" motto with a festive anniversary spirit.

The visual style is **Corporate / Modern** with a **Celebratory** overlay. It utilizes structured layouts to convey order and discipline, while incorporating vibrant gold accents and circular photo treatments to represent the school's inclusive community. Design elements should feel established yet energetic, blending a traditional educational aesthetic with modern digital clarity.

## Colors

The palette is rooted in a deep, authoritative purple, symbolizing wisdom and institutional dignity. This is contrasted by a vibrant, "Gold-leaf" yellow that evokes success, celebration, and energy.

- **Primary (Royal Purple):** Used for headers, primary backgrounds, and critical brand identifiers.
- **Secondary (Vibrant Gold):** Reserved for anniversary elements, calls to action, and highlights that need to "pop."
- **Tertiary (Amethyst):** A lighter purple used for decorative gradients and secondary UI elements to add depth.
- **Neutral:** A range of clean whites and soft grays to ensure the high-contrast brand colors remain legible and professional.

## Typography

The system uses **Manrope** for its clean, geometric, yet humanistic character, ensuring maximum readability across digital and print applications. Its varying weights allow for clear hierarchy between celebratory headlines and functional body text.

**Hanken Grotesk** is used for labels and the school motto to provide a sharp, technical contrast that underscores the "Discipline" aspect of the brand. Headings should utilize heavy weights (700-800) to feel impactful and celebratory, while body text remains balanced for accessibility.

## Layout & Spacing

The layout follows a **fluid grid system** based on a 12-column structure for desktop and a 4-column structure for mobile. Spacing follows a 4px base unit to ensure rhythmic consistency.

- **Desktop:** Utilize generous section gaps (80px+) to allow the brand's bold colors to breathe. Content is centered within a maximum width of 1280px.
- **Mobile:** Margins are reduced to 16px. Typography and components stack vertically.
- **Anniversary Elements:** Occasionally break the grid with circular image masks or "floating" gold confetti assets to create a dynamic, celebratory feel.

## Elevation & Depth

Visual hierarchy is primarily established through **Tonal Layers** and subtle **Ambient Shadows**.

- **Surfaces:** Use clean white containers against neutral off-white backgrounds to create soft separation. 
- **Shadows:** Use extremely diffused, low-opacity shadows (e.g., `0px 4px 20px rgba(75, 0, 130, 0.08)`) to give cards a slight lift without appearing heavy.
- **Anniversary Depth:** Use subtle gradients (Royal Purple to Amethyst) on primary surfaces to simulate the texture of school banners or ribbons.

## Shapes

The shape language is defined by **Rounded (0.5rem)** corners, which feel modern and approachable while maintaining a professional edge. 

A specific "Circle" motif is used for imagery, echoing the school's crest and anniversary logo. High-impact photos (graduations, events) should often be housed in circular or semi-circular masks to create a friendly, community-focused visual rhythm.

## Components

- **Buttons:** Primary buttons are Solid Royal Purple with White text. Secondary buttons are Gold with Purple text for high-impact celebratory actions. Use `rounded-lg` for all buttons.
- **Cards:** White backgrounds with a subtle 1px gray border or very soft shadow. Headlines inside cards should be Primary Purple.
- **Chips/Badges:** Use Gold backgrounds for status indicators like "10th Anniversary" or "Award Winner." 
- **Input Fields:** Clean, minimal outlines (1px gray) that turn Purple on focus. Labels should use the `label-bold` typography style.
- **Anniversary Ribbon:** A specialized component—a horizontal banner in Purple with Gold trim used to display the motto "Discipline and Hardwork" or event dates.
- **List Items:** Use Gold bullet points or checkmarks to maintain the brand color rhythm in informational sections.