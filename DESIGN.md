---
name: Proven Marketplace
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e6'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2ff'
  surface-container: '#eeecfa'
  surface-container-high: '#e8e7f4'
  surface-container-highest: '#e2e1ee'
  on-surface: '#1a1b24'
  on-surface-variant: '#42474e'
  inverse-surface: '#2f303a'
  inverse-on-surface: '#f1effd'
  outline: '#73777f'
  outline-variant: '#c2c7cf'
  surface-tint: '#3c6186'
  primary: '#001c32'
  on-primary: '#ffffff'
  primary-container: '#003153'
  on-primary-container: '#759ac1'
  inverse-primary: '#a5caf4'
  secondary: '#53606f'
  on-secondary: '#ffffff'
  secondary-container: '#d6e4f7'
  on-secondary-container: '#586676'
  tertiary: '#0d1b29'
  on-tertiary: '#ffffff'
  tertiary-container: '#23303f'
  on-tertiary-container: '#8a98aa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e4ff'
  primary-fixed-dim: '#a5caf4'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#22496c'
  secondary-fixed: '#d6e4f7'
  secondary-fixed-dim: '#bac8da'
  on-secondary-fixed: '#0f1d2a'
  on-secondary-fixed-variant: '#3b4857'
  tertiary-fixed: '#d6e4f7'
  tertiary-fixed-dim: '#bac8db'
  on-tertiary-fixed: '#0f1d2b'
  on-tertiary-fixed-variant: '#3a4858'
  background: '#fbf8ff'
  on-background: '#1a1b24'
  surface-variant: '#e2e1ee'
typography:
  display-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  title-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  gutter-tablet: 1.5rem
  margin-tablet: 2rem
  gutter-desktop: 1.5rem
  margin-desktop: auto
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-trust, institutional marketplace environment built on verification, precision, and financial-grade rigor. It balances the structure of enterprise fintech with the fluid usability of modern consumer commerce. 

Visual attributes draw heavily from modern Material 3 conventions paired with a structured, crisp architectural layout. The aesthetic relies on clear boundary lines, deliberate white space, tactile surface separations, and authoritative typography. The UI avoids excessive decorative gradients or ornamental micro-interactions, prioritizing clarity, legibility, and high-confidence transaction flows.

## Colors

The palette is engineered around high-contrast stability and distinct functional zones:

- **Brand Navy (`#003153`):** Primary brand accent, primary buttons, high-priority interactive states, and active indicators. Elements on navy use On-Navy (`#C4C3D0`) or pure white (`#FFFFFF`) for verified clarity.
- **Text Primary (`#0F1D2B`):** Deep carbon ink for headline levels, primary labels, and critical numeric values.
- **Text Secondary (`#556272`):** Cool slate for metadata, supporting body copy, helper text, and secondary navigation labels.
- **Background (`#F4F6FA`):** Soft, cool tinted canvas that recedes behind active components.
- **Surface (`#FFFFFF`):** High-elevation ground for cards, sheets, modals, and input fields.
- **Surface Variant (`#EAEEF5`):** Subtle container background for segmented controls, badge backings, table headers, and nested cards.
- **Outline (`#C4C3D0`):** Precise 1px structural framing for inactive borders, input strokes, and dividers.

## Typography

The type system is powered entirely by **IBM Plex Sans**, leveraging its technical precision and monoline clarity to provide an engineered, dependable marketplace tone. 

- **Display & Headline:** Used for screen headers, order values, product titles, and major dashboard totals. Set with tighter letter spacing (`-0.01em` to `-0.02em`) and heavier weights (Medium to Semi-Bold) to convey structure.
- **Body:** Scaled for readability across transaction logs, product descriptions, and terms. Line heights strictly follow an 8pt-based rhythm (16px, 20px, 24px).
- **Labels & Numbers:** Used for badges, verification tags, form inputs, button actions, and tabular financial values. Medium and Semi-Bold weights maintain legibility at 11px and 12px.

## Layout & Spacing

The layout is built upon an 8pt baseline grid system (with a secondary 4pt half-step for micro-elements like icon-text offsets and compact tags).

- **Mobile Viewport (Base: 390px × 844px):**
  - Columns: 4 fluid columns.
  - Margins: 16px (`1rem`).
  - Gutters: 16px (`1rem`).
  - Max Canvas: Full width fluid container with safe area insets respected for top bars and bottom actions.
- **Tablet (600px - 1024px):**
  - Columns: 8 fluid columns.
  - Margins: 32px (`2rem`).
  - Gutters: 24px (`1.5rem`).
- **Desktop (1024px+):**
  - Columns: 12 columns constrained to a max-width container of 1200px.
  - Margins: Auto-centered.
  - Gutters: 24px (`1.5rem`).

## Elevation & Depth

Visual hierarchy combines tonal layering with precise, low-intensity ambient shadows:

- **Level 0 (Flat / Canvas):** `#F4F6FA` base background.
- **Level 1 (Card Default / Inset):** `#FFFFFF` surfaces with a 1px border stroke using Outline (`#C4C3D0`). Soft shadow: `0px 1px 3px rgba(15, 29, 43, 0.04)`.
- **Level 2 (Hover / Elevated Card):** `#FFFFFF` surface, 1px border stroke using `#C4C3D0`. Ambient lift: `0px 4px 12px rgba(15, 29, 43, 0.06), 0px 1px 2px rgba(15, 29, 43, 0.04)`.
- **Level 3 (Sticky Headers / Dropdowns / Bottom Sheets):** `#FFFFFF` surface without standard outer borders. Pronounced shadow: `0px 8px 24px rgba(15, 29, 43, 0.08), 0px 2px 6px rgba(15, 29, 43, 0.04)`.
- **Level 4 (Modals & Overlays):** Full backdrop scrim `rgba(15, 29, 43, 0.45)`, card elevated with `0px 16px 32px rgba(15, 29, 43, 0.12)`.

## Shapes

The geometric identity balances structural stability with user-friendly ergonomics through precise, fixed corner radii:

- **Cards & Primary Modules:** Strict 16px border-radius.
- **Interactive Controls (Buttons, Text Inputs, Search Bars):** Strict 14px border-radius.
- **Small Components (Chips, Status Badges, Tabs):** 8px border-radius for badges and micro-cards; pill-shaped (`9999px`) reserved strictly for status pills and counter tags.
- **Modals & Bottom Sheets:** 24px top border-radius for bottom sheets; 16px continuous radius for centered dialogs.

## Components

### Buttons
- **Primary:** Background Brand Navy (`#003153`), text pure white (`#FFFFFF`), height 48px, horizontal padding 20px, corner radius 14px. Font: `label-lg`. Pressed state applies a 12% black overlay.
- **Secondary / Outlined:** Background transparent, border 1px solid Outline (`#C4C3D0`), text Primary Ink (`#0F1D2B`), height 48px, horizontal padding 20px, corner radius 14px. Pressed state triggers Surface Variant (`#EAEEF5`).
- **Tertiary / Text:** No border, text Brand Navy (`#003153`), padding 12px horizontal, height 40px, corner radius 14px.

### Input Fields
- **Container:** Height 52px, background `#FFFFFF`, border 1px solid `#C4C3D0`, corner radius 14px, internal padding 16px horizontal.
- **States:**
  - *Resting:* Border `#C4C3D0`, placeholder text `#556272`.
  - *Active / Focused:* Border 2px solid Brand Navy (`#003153`), label shifts to top micro-position (`label-sm`).
  - *Error:* Border 1.5px solid `#D32F2F`, error caption in `#D32F2F`.

### Cards
- **Base Style:** Background `#FFFFFF`, corner radius 16px, border 1px solid `#C4C3D0`, padding 16px or 20px depending on density.
- **Variant (Interactive / Selectable):** Adds resting shadow `0px 1px 3px rgba(15, 29, 43, 0.04)`; selected state gains a 2px inner border of Brand Navy (`#003153`).

### Chips & Filter Tags
- **Filter Chip:** Height 36px, corner radius 8px, background `#EAEEF5`, text `#0F1D2B`, font `label-md`. Active state changes background to Brand Navy (`#003153`) and text to `#FFFFFF`.

### Lists & Row Items
- **Structure:** 64px min-height for single-line with thumbnail; 72px for two-line metadata. Separators use a 1px solid `#EAEEF5` line with 16px inset from leading icon or thumbnail.

### Checkboxes & Radio Buttons
- **Radio Buttons:** 20px circle, 1.5px stroke `#556272`. Selected: 2px stroke Brand Navy (`#003153`) with 10px centered solid fill in Brand Navy.
- **Checkboxes:** 20px square, 6px corner radius, 1.5px stroke `#556272`. Selected: Brand Navy (`#003153`) background with `#FFFFFF` checkmark.

### Marketplace Specialized Components
- **Trust & Verification Badges:** Height 24px, radius 9999px (pill), background `#EAEEF5`, border 1px solid `#C4C3D0`, text Brand Navy (`#003153`), containing a verified check icon (12px).
- **Price Ledger Row:** Dual column split; left label in Text Secondary (`#556272`, `body-md`), right value in Text Primary (`#0F1D2B`, `title-md`), numbers tabular-aligned.