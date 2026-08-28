---
name: Botanique Inventory
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdada'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e8'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414844'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#1b2637'
  on-tertiary: '#ffffff'
  tertiary-container: '#313c4e'
  on-tertiary-container: '#9ba6bc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
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
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is built for a "luxury laboratory" aesthetic, balancing the precision of inventory management with the high-end sensory world of perfumery. The target audience includes artisanal perfumers and luxury retail managers who require a tool that feels as sophisticated as the products they track.

The design style is **Minimalist / High-End Modern**. It prioritizes heavy white space (Ivory), crisp botanical accents, and thin, deliberate lines. The UI should evoke a sense of calm, organization, and prestige, moving away from cluttered enterprise software toward a curated, editorial experience.

## Colors

The palette is rooted in a "Deep Botanical" theme. 
- **Primary (#1B4332):** A deep, forest green used for navigation, primary actions, and branding. It represents the raw ingredients of perfumery.
- **Secondary (#D4AF37):** A soft gold leaf used sparingly for focus states, highlights, and premium indicators.
- **Neutral/Background (#FCFAFA):** A warm Ivory that reduces eye strain compared to pure white, maintaining a paper-like, editorial feel.
- **Text/Secondary (#4A5568):** A professional slate gray used for body copy and data labels to ensure high legibility without the harshness of pure black.

## Typography

This design system utilizes a high-contrast typographic pairing to reinforce the luxury laboratory theme. 

**Playfair Display** is used for all headlines and display text, providing an authoritative, editorial feel. For data-heavy views, **Inter** provides exceptional clarity and a systematic, modern touch. 

- Use `label-md` with its uppercase transformation for table headers and section category labels.
- Reserve `display-lg` for dashboard greetings or featured collection titles.
- All body text should use the Slate Gray (#4A5568) for a refined look.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain an editorial, magazine-like structure, transitioning to a fluid model on mobile devices.

- **Desktop:** 12-column grid with a 1280px max-width. Use generous 40px outer margins to allow the "Ivory" background to frame the content.
- **Rhythm:** All spacing (padding, margins) must be multiples of the 8px base unit.
- **Alignment:** Data tables and lists should be center-aligned within the container to maintain a balanced, symmetrical appearance typical of luxury branding.

## Elevation & Depth

Depth is communicated through **Tonal Layers** and extremely subtle, diffused shadows. 

- **Surface Levels:** The base Ivory (#FCFAFA) is Level 0. Cards and containers are Level 1, using a pure white background to subtly pop against the Ivory.
- **Shadows:** Use "Ambient Shadows"—diffused, low-opacity (5-8%) blurs with a slight green tint from the primary color to keep the shadows "warm" rather than "dirty."
- **Outlines:** Use 1px borders in a very light version of the slate gray for secondary structural elements, keeping the interface feeling lightweight and precise.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the "technical" nature of inventory management, making the tool feel more approachable and premium.

- Small elements like checkboxes and tags use the base `rounded` (4px).
- Larger containers like cards use `rounded-lg` (8px).
- Status badges use a full pill-shape to distinguish them from interactive buttons.

## Components

### Buttons
- **Primary:** Solid Deep Green (#1B4332) with white Inter-medium text. No border.
- **Secondary:** Transparent background with a 1px Gold (#D4AF37) border.

### Input Fields
- **Refined State:** Fields should have a 1px light gray bottom border only in their default state (resembling a formal ledger).
- **Focus State:** Transitions to a full-perimeter 1px Gold (#D4AF37) border with a soft 2px gold outer glow.

### Status Badges
- **In Stock:** Pale green background with Deep Green text.
- **Low Stock:** Soft Ivory-Gold background with Gold text.
- **Out of Stock:** Very light gray background with Slate Gray text (avoiding aggressive reds to maintain the calm aesthetic).

### Inventory Cards
Cards should feature high-quality product photography. Use a white background, 8px corner radius, and a subtle "ambient" shadow. Typography inside cards should be strictly hierarchical: Playfair for the scent name, Inter for the SKU and quantity.

### Additional Components
- **Ingredient Tags:** Small, outlined chips to categorize fragrance notes (e.g., "Floral", "Woody").
- **Stock Level Progress Bars:** Ultra-thin (2px) bars using the Gold accent color to indicate bottle fullness or raw material volume.