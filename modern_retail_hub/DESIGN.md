---
name: Modern Retail Hub
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
  on-surface-variant: '#434656'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004ced'
  primary: '#003ec7'
  on-primary: '#ffffff'
  primary-container: '#0052ff'
  on-primary-container: '#dfe3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#005474'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e95'
  on-tertiary-container: '#caeaff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001452'
  on-primary-fixed-variant: '#0038b6'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  price-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
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
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
The design system is engineered for a high-performance marketplace that balances the precision of electronics with the aesthetic appeal of fashion. The brand personality is professional, trustworthy, and streamlined, aiming to evoke a sense of reliability and effortless discovery. 

The chosen style is **Corporate / Modern**, characterized by generous whitespace, a structured grid, and a refined use of depth. It avoids unnecessary ornamentation to ensure that product imagery—the core of the user experience—remains the focal point. The interface feels "premium yet accessible," utilizing smooth transitions and a cohesive visual language to guide the user from discovery to checkout.

## Colors
The palette is rooted in a "Clean Blue and White" theme to establish a high level of professional credibility. 

- **Primary Blue (#0052FF):** A vibrant, high-energy blue used for primary actions, progress indicators, and key brand touchpoints.
- **Secondary Navy (#0172A):** A deep slate-navy used for typography and high-contrast UI elements to ensure legibility.
- **Neutral Surface (#F8FAFC):** A very light cool-gray used for backgrounds to reduce eye strain and differentiate content sections without the harshness of pure white.
- **Success/Action:** Utilize the primary blue for "Add to Cart" and positive reinforcement, ensuring a monochromatic confidence throughout the flow.

## Typography
This design system utilizes **Plus Jakarta Sans** for its modern, friendly, and highly legible geometric qualities. Given the Portuguese language requirement, the typography scales to accommodate longer word lengths (e.g., "Adicionar ao carrinho") without breaking the layout.

- **Headlines:** Use Bold weights with tight letter-spacing for a modern, editorial feel.
- **Pricing:** Dedicated `price-display` role ensures that currency and value are prominent and immediately scannable.
- **Body:** Regular weight with generous line height for product descriptions.
- **Interactive Labels:** Semi-bold or Bold for buttons and navigation items to pass accessibility standards easily.

## Layout & Spacing
The design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is centered on "Clear Hierarchy and Breathing Room."

- **Grid:** Use a 24px gutter to provide distinct separation between product cards.
- **Margins:** 16px on mobile to maximize screen real estate, increasing to 48px on desktop to frame the content.
- **Vertical Rhythm:** A strict 8px baseline grid ensures consistent vertical spacing between elements like product titles, prices, and buttons.
- **Responsive Behavior:** On mobile, product grids should transition from 4 columns to 2 columns to keep product imagery large and detailed.

## Elevation & Depth
Visual hierarchy is achieved through **Ambient Shadows** and **Tonal Layers**. 

- **Surface Levels:** The main background is the Neutral hex, while interactive cards and containers use pure white (#FFFFFF) to "pop" off the page.
- **Shadows:** Use extremely soft, diffused shadows (0px 4px 20px rgba(0, 0, 0, 0.05)) for product cards. This creates a tactile feel that suggests the cards are tappable without cluttering the UI with heavy borders.
- **States:** On hover, a card's elevation should increase slightly (0px 12px 30px rgba(0, 0, 0, 0.08)) to provide immediate visual feedback.

## Shapes
The shape language is defined by **Rounded (0.5rem)** corners. This level of curvature softens the professional "corporate" aesthetic, making the marketplace feel more modern and consumer-friendly.

- **Product Cards:** Use `rounded-lg` (1rem) to create a friendly frame for product photography.
- **Buttons:** Use `rounded-lg` (1rem) or `pill-shaped` for primary CTAs like "Comprar Agora" to draw the eye.
- **Inputs:** Use the base `rounded` (0.5rem) for form fields to maintain a structured, clean look.

## Components
Consistent component styling is vital for the professional appearance of this design system:

- **Product Cards:** Must include a high-aspect-ratio image container, a title (max 2 lines), a bold price display, and a secondary-styled "Add to Cart" icon or a full-width primary button.
- **Buttons:** 
    - *Primary:* Blue background, white text, bold weight.
    - *Secondary:* Ghost style with blue border or light blue tint.
- **Navigation:** A sticky top bar with a clean search input, category dropdowns, and clear icons for "Favorites" and "Cart."
- **Input Fields:** Minimalist style with a 1px border (#E2E8F0) that thickens and turns Primary Blue on focus. Labels should be small and positioned above the field.
- **Chips:** Used for category tags or "New" / "Sale" badges, featuring light blue backgrounds and dark blue text.
- **Lists:** Clean, borderless lists for account menus and category sidebars, using subtle hover backgrounds for feedback.