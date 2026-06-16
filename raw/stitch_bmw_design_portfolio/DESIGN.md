---
version: alpha
name: BMW-design-analysis
description: BMW's corporate site — distinct from BMW M's motorsport-bombastic variant,
  this is a measured and settled corporate-automotive interface. On a light (cream-tinted
  white) canvas, BMW corporate blue (#1c69d4) carries every primary CTA; dark navy
  hero bands frame model photography. BMW Type Next Latin sets the entire hierarchy
  on two weights — heavy 700 display and Light 300 body. Configuration and reservation
  flows ride a card-based 4-up grid, where each card holds a model render, a name,
  and a "Learn More" link.
colors:
  primary: '#1c69d4'
  primary-active: '#0653b6'
  primary-disabled: '#d6d6d6'
  ink: '#262626'
  body: '#3c3c3c'
  body-strong: '#1a1a1a'
  muted: '#6b6b6b'
  muted-soft: '#9a9a9a'
  hairline: '#e6e6e6'
  hairline-strong: '#cccccc'
  canvas: '#ffffff'
  surface-soft: '#f7f7f7'
  surface-card: '#fafafa'
  surface-strong: '#ebebeb'
  surface-dark: '#1a2129'
  surface-dark-elevated: '#262e38'
  on-primary: '#ffffff'
  on-dark: '#ffffff'
  on-dark-soft: '#bbbbbb'
  m-blue-light: '#0066b1'
  m-blue-dark: '#1c69d4'
  m-red: '#e22718'
  success: '#22c55e'
  warning: '#f59e0b'
  error: '#dc2626'
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#424753'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#727784'
  outline-variant: '#c2c6d5'
  surface-tint: '#005bc1'
  primary-container: '#1c69d4'
  on-primary-container: '#ebefff'
  inverse-primary: '#adc6ff'
  secondary: '#585f68'
  on-secondary: '#ffffff'
  secondary-container: '#d9e0eb'
  on-secondary-container: '#5c636d'
  tertiary: '#8d3b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#b44d00'
  on-tertiary-container: '#ffebe2'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004494'
  secondary-fixed: '#dce3ee'
  secondary-fixed-dim: '#c0c7d2'
  on-secondary-fixed: '#151c24'
  on-secondary-fixed-variant: '#404750'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783100'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-xl:
    fontFamily: '''BMW Type Next Latin'', system-ui, -apple-system, BlinkMacSystemFont,
      ''Segoe UI'', Roboto, sans-serif'
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: 0
  display-lg:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0
  display-md:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: 0
  display-sm:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  title-lg:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 0
  title-sm:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 0
  body-md:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 14px
    fontWeight: 300
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.5px
  label-uppercase:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 1.5px
    textTransform: uppercase
  button:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0.5px
  nav-link:
    fontFamily: '''BMW Type Next Latin'', sans-serif'
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.3px
rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 12px
  pill: 9999px
  full: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 80px
  gutter: 24px
components:
  top-nav:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.nav-link}'
    height: 64px
  button-primary:
    backgroundColor: '{colors.primary}'
    textColor: '{colors.on-primary}'
    typography: '{typography.button}'
    rounded: '{rounded.none}'
    padding: 14px 32px
    height: 48px
  button-primary-active:
    backgroundColor: '{colors.primary-active}'
    textColor: '{colors.on-primary}'
    rounded: '{rounded.none}'
  button-primary-disabled:
    backgroundColor: '{colors.primary-disabled}'
    textColor: '{colors.muted}'
    rounded: '{rounded.none}'
  button-secondary:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.button}'
    rounded: '{rounded.none}'
    padding: 13px 31px
    height: 48px
  button-secondary-on-dark:
    backgroundColor: transparent
    textColor: '{colors.on-dark}'
    typography: '{typography.button}'
    rounded: '{rounded.none}'
    padding: 13px 31px
  button-text-link:
    backgroundColor: transparent
    textColor: '{colors.ink}'
    typography: '{typography.label-uppercase}'
  text-link:
    backgroundColor: transparent
    textColor: '{colors.ink}'
    typography: '{typography.body-md}'
  hero-band-dark:
    backgroundColor: '{colors.surface-dark}'
    textColor: '{colors.on-dark}'
    typography: '{typography.display-xl}'
    padding: 80px
  hero-photo-band:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.display-lg}'
    padding: 80px
  model-card:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.title-md}'
    rounded: '{rounded.none}'
    padding: 24px
  model-card-photo:
    backgroundColor: '{colors.surface-card}'
    rounded: '{rounded.none}'
  feature-photo-card:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.title-md}'
    rounded: '{rounded.none}'
    padding: 24px
  spec-cell:
    backgroundColor: transparent
    textColor: '{colors.ink}'
    typography: '{typography.display-sm}'
    rounded: '{rounded.none}'
    padding: 24px
  inventory-card:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.title-sm}'
    rounded: '{rounded.none}'
    padding: 16px
  filter-chip:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.caption}'
    rounded: '{rounded.none}'
    padding: 8px 14px
  filter-chip-active:
    backgroundColor: '{colors.ink}'
    textColor: '{colors.on-dark}'
    rounded: '{rounded.none}'
  configurator-option-tile:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.body-md}'
    rounded: '{rounded.none}'
    padding: 16px 24px
  configurator-option-tile-selected:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    rounded: '{rounded.none}'
    padding: 15px 23px
  text-input:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.ink}'
    typography: '{typography.body-md}'
    rounded: '{rounded.none}'
    padding: 14px 16px
    height: 48px
  cookie-consent-card:
    backgroundColor: '{colors.canvas}'
    textColor: '{colors.body}'
    typography: '{typography.body-sm}'
    rounded: '{rounded.none}'
    padding: 24px
  category-tab:
    backgroundColor: transparent
    textColor: '{colors.muted}'
    typography: '{typography.label-uppercase}'
    rounded: '{rounded.none}'
  category-tab-active:
    backgroundColor: transparent
    textColor: '{colors.ink}'
    typography: '{typography.label-uppercase}'
    rounded: '{rounded.none}'
  m-stripe-divider:
    backgroundColor: transparent
    rounded: '{rounded.none}'
  cta-band-photo:
    backgroundColor: '{colors.surface-dark}'
    textColor: '{colors.on-dark}'
    typography: '{typography.display-md}'
    padding: 80px
  footer:
    backgroundColor: '{colors.surface-soft}'
    textColor: '{colors.body}'
    typography: '{typography.body-sm}'
    padding: 64px
---

