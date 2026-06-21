---
version: alpha
name: Nike-design-analysis
description: |
  A photography-first commerce system built on extreme typographic contrast — towering uppercase Futura display lockups burned into editorial campaign imagery, sitting above a dense, neutral, near-monochrome retail chrome of pill-shaped black CTAs, gray search and tag pills, and tight 8px-grid product cards. The brand's voice is athletic, kinetic, and absolute: pure black, pure white, a single soft surface gray, and a deliberately small set of semantic accents (sale red, success green, restrained category tints) — every chromatic moment is reserved for editorial photography or pricing signal, never decorative chrome.
colors:
  primary: '#111111'
  on-primary: '#ffffff'
  canvas: '#ffffff'
  soft-cloud: '#f5f5f5'
  ink: '#111111'
  charcoal: '#39393b'
  ash: '#4b4b4d'
  mute: '#707072'
  stone: '#9e9ea0'
  hairline: '#cacacb'
  hairline-soft: '#e5e5e5'
  sale: '#d30005'
  sale-deep: '#780700'
  success: '#007d48'
  success-bright: '#1eaa52'
  info: '#1151ff'
  info-deep: '#0034e3'
  accent-pink: '#ed1aa0'
  accent-pink-soft: '#ffb0dd'
  accent-purple-soft: '#beaffd'
  accent-purple-pale: '#d6d1ff'
  accent-teal: '#0a7281'
  accent-pink-deep: '#4c012d'
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1b1a'
  on-tertiary-container: '#868381'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e6e1df'
  tertiary-fixed-dim: '#cac6c3'
  on-tertiary-fixed: '#1d1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-campaign:
    fontFamily: Nike Futura ND
    fontSize: 96px
    fontWeight: 500
    lineHeight: 0.9
    letterSpacing: 0
    textTransform: uppercase
  heading-xl:
    fontFamily: Helvetica Now Display Medium
    fontSize: 32px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  heading-lg:
    fontFamily: Helvetica Now Display Medium
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  heading-md:
    fontFamily: Helvetica Now Display Medium
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.75
    letterSpacing: 0
  body-md:
    fontFamily: Helvetica Now Text
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-strong:
    fontFamily: Helvetica Now Text Medium
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  button-lg:
    fontFamily: Helvetica Now Display Medium
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  button-md:
    fontFamily: Helvetica Now Text Medium
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  button-sm:
    fontFamily: Helvetica Now Text Medium
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  link-md:
    fontFamily: Helvetica Now Text
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.75
    letterSpacing: 0
    textDecoration: underline
  caption-md:
    fontFamily: Helvetica Now Text Medium
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  caption-sm:
    fontFamily: Helvetica Now Text Medium
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  utility-xs:
    fontFamily: Helvetica Neue
    fontSize: 9px
    fontWeight: 500
    lineHeight: 1.75
    letterSpacing: 0
  display-campaign-mobile:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.0'
rounded:
  none: 0px
  sm: 18px
  md: 24px
  lg: 30px
  full: 9999px
  DEFAULT: 1rem
  xl: 3rem
spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 18px
  xl: 24px
  xxl: 30px
  section: 48px
  grid-base: 8px
components:
  button-primary:
    backgroundColor: '{colors.ink}'
    textColor: '{colors.on-primary}'
    typography: '{typography.button-md}'
    rounded: '{rounded.full}'
    padding: 16px 32px
    height: 48px
  button-primary-active:
    backgroundColor: '{colors.ink}'
    textColor: '{colors.on-primary}'
    typography: '{typography.button-md}'
    rounded: '{rounded.full}'
  button-secondary:
    backgroundColor: '{colors.soft-cloud}'
    textColor: '{colors.ink}'
    typography: '{typography.button-md}'
    rounded: '{rounded.full}'
    padding: 16px 32px
    height: 48px
  button-outline-on-image:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.button-md}'
    rounded: '{rounded.full}'
    padding: 12px 24px
  button-icon-circular:
    backgroundColor: '{colors.soft-cloud}'
    textColor: '{colors.ink}'
    rounded: '{rounded.full}'
    size: 40px
  search-pill:
    backgroundColor: '{colors.soft-cloud}'
    textColor: '{colors.ink}'
    typography: '{typography.body-md}'
    rounded: '{rounded.md}'
    padding: 8px 16px
    height: 40px
  search-pill-focused:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    rounded: '{rounded.md}'
  filter-chip:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.button-md}'
    rounded: '{rounded.full}'
    padding: 8px 16px
  filter-chip-active:
    backgroundColor: '{colors.ink}'
    textColor: '{colors.on-primary}'
    typography: '{typography.button-md}'
    rounded: '{rounded.full}'
  badge-promo:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.caption-sm}'
    rounded: '{rounded.full}'
    padding: 4px 12px
  badge-sale-text:
    textColor: '{colors.sale}'
    typography: '{typography.caption-md}'
  product-card:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.body-strong}'
    rounded: '{rounded.none}'
    padding: 0px
  product-card-image:
    backgroundColor: '{colors.soft-cloud}'
    rounded: '{rounded.none}'
  swatch-dot:
    backgroundColor: '{colors.ink}'
    rounded: '{rounded.full}'
    size: 12px
  swatch-dot-active:
    backgroundColor: '{colors.ink}'
    rounded: '{rounded.full}'
    size: 12px
  campaign-tile:
    backgroundColor: '{colors.ink}'
    textColor: '{colors.on-primary}'
    typography: '{typography.display-campaign}'
    rounded: '{rounded.none}'
  category-icon-card:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.caption-md}'
    rounded: '{rounded.none}'
  member-benefit-card:
    backgroundColor: '{colors.ink}'
    textColor: '{colors.on-primary}'
    typography: '{typography.heading-lg}'
    rounded: '{rounded.none}'
  faq-row:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.heading-md}'
    rounded: '{rounded.none}'
    padding: 24px 0px
  pdp-disclosure-row:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.body-strong}'
    rounded: '{rounded.none}'
    padding: 24px 0px
  utility-bar:
    backgroundColor: '{colors.soft-cloud}'
    textColor: '{colors.ink}'
    typography: '{typography.caption-sm}'
    rounded: '{rounded.none}'
    height: 36px
  primary-nav:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.body-strong}'
    rounded: '{rounded.none}'
    height: 56px
  filter-sidebar:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.body-strong}'
    rounded: '{rounded.none}'
  footer:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.mute}'
    typography: '{typography.caption-md}'
    rounded: '{rounded.none}'
---

