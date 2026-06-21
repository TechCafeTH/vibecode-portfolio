---
name: Studio Paper & Ink
colors:
  surface: '#fdf9f5'
  surface-dim: '#ddd9d6'
  surface-bright: '#fdf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ef'
  surface-container: '#f1edea'
  surface-container-high: '#ebe7e4'
  surface-container-highest: '#e6e2de'
  on-surface: '#1c1b1a'
  on-surface-variant: '#414753'
  inverse-surface: '#31302e'
  inverse-on-surface: '#f4f0ed'
  outline: '#717784'
  outline-variant: '#c1c6d5'
  surface-tint: '#005eb4'
  primary: '#005db2'
  on-primary: '#ffffff'
  primary-container: '#0075de'
  on-primary-container: '#fffeff'
  inverse-primary: '#a8c8ff'
  secondary: '#4958aa'
  on-secondary: '#ffffff'
  secondary-container: '#97a5fe'
  on-secondary-container: '#283789'
  tertiary: '#006d1d'
  on-tertiary: '#ffffff'
  tertiary-container: '#008927'
  on-tertiary-container: '#ffffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a8c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#00468a'
  secondary-fixed: '#dee0ff'
  secondary-fixed-dim: '#bac3ff'
  on-secondary-fixed: '#00105b'
  on-secondary-fixed-variant: '#303f91'
  tertiary-fixed: '#78fe7d'
  tertiary-fixed-dim: '#5ae064'
  on-tertiary-fixed: '#002204'
  on-tertiary-fixed-variant: '#005314'
  background: '#fdf9f5'
  on-background: '#1c1b1a'
  surface-variant: '#e6e2de'
  canvas: '#ffffff'
  canvas-soft: '#f6f5f4'
  ink: '#000000'
  ink-muted: '#615d59'
  ink-faint: '#a39e98'
  hairline: '#e6e6e6'
  accent-sky: '#62aef0'
  accent-purple: '#d6b6f6'
  accent-pink: '#ff64c8'
  accent-orange: '#dd5b00'
  accent-teal: '#2a9d99'
typography:
  display-1:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -2.125px
  display-1-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -1px
  display-2:
    fontFamily: Inter
    fontSize: 54px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -1.875px
  heading-1:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -1px
  heading-2:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.625px
  heading-3:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.25px
  title:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.125px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  button:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: '0'
  caption:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  eyebrow:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.125px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 28px
  xxl: 32px
  section-gap: 80px
  container-max-width: 1120px
---

## Brand & Style

This design system is built on a philosophy of **Digital Stationery**. It aims to evoke the tactile quality of a high-end physical notebook—clean, structured, and intentional. The brand personality is calm, professional, and intellectually curious, positioning the professional portfolio not just as a resume, but as a curated archive of work.

The aesthetic follows a **Minimalist-Corporate** hybrid. It utilizes heavy whitespace and a warm, off-white "paper" canvas to reduce eye strain and differentiate from the clinical coldness of standard SaaS interfaces. Visual interest is driven by high-impact typography and a "sticker" system of colorful accents, allowing the personality of the portfolio owner to shine through without compromising the structural integrity of the layout.

## Colors

The palette is anchored by the "Canvas" colors, which provide a warm, document-like foundation. 

- **Primary & Secondary**: Used sparingly for functional intent. The signature blue is reserved for primary actions and links, while the deep indigo is used for high-contrast "Night" sections or inverted surfaces.
- **Ink Tiers**: Typography uses a tiered grayscale to establish hierarchy. Avoid using pure `#000000` for long-form body text; instead, reserve it for high-impact headlines.
- **Sticker Accents**: The named accent colors should be used for decorative elements, category tags, and "stickers." These should never be used for primary navigation or critical functional buttons unless they represent a specific category state.

## Typography

This system uses a custom-tuned implementation of **Inter**. The core of the typographic identity lies in the aggressive negative tracking applied to display and heading levels. This "tightness" gives the typeface a more bespoke, editorial character.

- **Display Levels**: Use `display-1` and `display-2` for hero moments only. Ensure they are center-aligned or tightly grouped with secondary copy.
- **Body Text**: Maintain standard tracking for readability. Use `body-md` for the majority of long-form reading and `body-sm` for UI labels and metadata.
- **Negative Space**: Large headers should be accompanied by significant vertical margins to maintain the "clean paper" aesthetic.

## Layout & Spacing

The layout philosophy is based on a **Fixed Grid** model. Content is centered within a maximum width of 1120px to ensure line lengths remain readable and the portfolio feels like a structured document rather than a sprawling website.

- **Grid**: Use a 12-column grid for desktop with 24px gutters.
- **Rhythm**: Follow an 8px base rhythm for component-level spacing. 
- **Responsive Behavior**: 
  - **Desktop**: 1120px container, 32px side margins.
  - **Tablet**: Fluid width, 24px side margins.
  - **Mobile**: Fluid width, 16px side margins. Large display type scales down to mobile-specific tokens to prevent clipping and excessive line-breaking.

## Elevation & Depth

Depth is used sparingly to maintain the "flat paper" feel. Most elements sit directly on the `canvas-soft` background, separated only by `hairline` borders.

- **Tonal Layers**: The primary method of separation. Use `canvas` (pure white) for elevated surfaces like cards or modals against the `canvas-soft` background.
- **Ambient Shadows**: Shadows are only applied to "active" or "floating" elements. Use the multi-stop shadow stack for Level 1 (Soft Shadow) on interactive cards and focused inputs. Level 2 (Elevated) is reserved exclusively for overlays like modals and dropdown menus.
- **Flat Hairlines**: For static lists and standard grid items, use 1px solid borders in `hairline` color with no shadow.

## Shapes

The shape language distinguishes between "Marketing/Brand" and "Utility/Function":

- **Pill Shapes (Full)**: Used for primary Call-to-Action buttons and category badges. This adds a friendly, modern touch to the otherwise rigid grid.
- **Rounded (8px-12px)**: Used for feature cards and illustration containers. This provides a soft, professional look.
- **Soft (4px-5px)**: Used for functional UI elements like text inputs and navigation menu items to signal precision and utility.

## Components

### Buttons
- **Primary**: Pill-shaped, `primary` background with `on-primary` text. Applies a `scale(0.9)` on press.
- **Utility**: `md` (8px) rounded, white background with `hairline` border. Used for secondary actions.

### Cards
- **Feature Cards**: White background (`canvas`), 1px `hairline` border, `lg` (12px) rounded corners. Use Level 1 shadow on hover to indicate interactivity.
- **Content Cards**: No border, `canvas-soft` background, used for grouping text-heavy content.

### Inputs & Fields
- **Text Inputs**: `xs` (4px) roundedness, `hairline` border. On focus, the border color shifts to `primary` and applies a subtle Level 1 shadow.

### Stickers & Badges
- **Badges**: Pill-shaped, using `eyebrow` typography. Backgrounds should use low-opacity versions of the "sticker" palette (e.g., 10% opacity) with full-saturation text for high legibility.
- **Stickers**: Decorative icons or small illustrations framed in `lg` (12px) rounded containers, using the full-saturation accent palette.

### Lists
- **Nav Rows**: Use `sm` (5px) roundedness for hover states. Text should shift from `ink-secondary` to `ink` on hover.