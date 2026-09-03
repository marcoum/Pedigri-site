---
name: Clinical Care & Heritage
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#56423d'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#89726c'
  outline-variant: '#dcc0b9'
  surface-tint: '#9e4228'
  primary: '#9e4228'
  on-primary: '#ffffff'
  primary-container: '#e87a5c'
  on-primary-container: '#611601'
  inverse-primary: '#ffb5a1'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e2'
  on-secondary-container: '#646464'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#989999'
  on-tertiary-container: '#2f3132'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a1'
  on-primary-fixed: '#3b0800'
  on-primary-fixed-variant: '#7e2b13'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#c8c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e3e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

This design system is built for a 30-year legacy of veterinary care, blending established authority with modern warmth. The brand personality is **Professional, Compassionate, and Reliable**. It serves pet owners who seek a balance between cutting-edge medical technology and a nurturing environment.

The visual style is **Corporate / Modern** with a focus on high-clarity and spaciousness. We utilize generous whitespace to create a sense of "calm" in what can often be stressful medical situations. The aesthetic avoids cold clinical vibes by using soft curves and a "Humanist" approach to typography and iconography.

Key visual principles:
- **Clarity over Clutter:** Every element must have a clear purpose.
- **Warmth through Accents:** The coral palette is used strategically to guide the eye and evoke care.
- **Trust through Geometry:** Use of structured grids and clean lines to reflect 24h medical precision.

## Colors

The palette is derived directly from the heritage logo, optimized for digital accessibility.

- **Primary (Coral):** Used for primary Call-to-Actions (CTAs), urgent medical indicators, and brand-defining accents. It represents the heart and energy of the clinic.
- **Secondary (Graphite):** The anchor for all typography and structural elements. It conveys the 30-year professional foundation and stability.
- **Background (Soft White/Light Gray):** We avoid pure #FFFFFF for large backgrounds, opting for a very soft off-white to reduce eye strain and feel more welcoming.
- **Functional Colors:**
    - **Success:** Soft Teal (complementary to coral).
    - **Alert:** Bright Coral (higher saturation).
    - **Info:** Muted Slate Blue.

## Typography

This design system uses a dual-font strategy to balance character with readability.

**Montserrat (Headlines):** Its geometric but open nature feels modern and confident. Use Bold and Semi-Bold weights to establish a clear hierarchy.
**Open Sans (Body & UI):** Chosen for its exceptional legibility and friendly, neutral tone. It remains readable even in high-density information areas like medical records or service lists.

Hierarchy is maintained by using Graphite (#4A4A4A) for headlines to ensure strong contrast, while body text uses a slightly lighter Neutral Gray (#555555) to soften the reading experience.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** with generous safe areas to ensure the "respiro" (breathing room) requested.

- **Grid:** A 12-column system for desktop, 6-column for tablet, and 2-column for mobile.
- **Rhythm:** An 8px base unit governs all spacing.
- **Margins:** Desktop margins are set to a minimum of 80px to pull the content into a focused central area, reflecting a boutique, high-care experience.
- **Vertical Spacing:** Use `xl` (80px) spacing between major sections to prevent the UI from feeling "crowded" or "urgent," maintaining a calm atmosphere for the user.

## Elevation & Depth

We utilize **Tonal Layers** supplemented by **Ambient Shadows** to create a sophisticated, trustworthy depth. 

- **Surface 0 (Background):** Solid off-white/light gray.
- **Surface 1 (Cards/Containers):** Pure white background with a very soft, diffused shadow (Blur: 20px, Y: 4px, Opacity: 4% Black). This makes the content appear as if it is floating gently above the base.
- **Interactions:** When a user hovers over an interactive element, the shadow should slightly deepen and the element should lift (Y-axis shift), providing tactile feedback without breaking the clean aesthetic.
- **Outlines:** Use very low-contrast borders (1px solid #EDEDED) for input fields and list items to define structure without adding visual noise.

## Shapes

The shape language is **Rounded**, avoiding sharp corners to evoke a sense of safety and friendliness towards pets and their owners.

- **Standard Elements:** Buttons, input fields, and tags use a 0.5rem (8px) radius.
- **Large Containers:** Cards and image containers use 1rem (16px) radius to soften the overall layout.
- **Icons:** Should feature rounded terminals and soft corners to match the typographic style of Montserrat.

## Components

### Buttons
- **Primary:** Coral background, white text. Bold weight. High-contrast for "Emergency" or "Book Appointment" actions.
- **Secondary:** Graphite outline with Graphite text. Used for secondary navigation or less urgent actions.
- **Ghost:** No background, Coral or Graphite text. Used for "Learn More" or text-heavy utility links.

### Input Fields
- Subtle gray backgrounds (#F5F5F5) that turn White on focus, with a 2px Coral border. Labels are always visible above the field in `label-md` style.

### Cards
- White background, 16px corner radius, soft ambient shadow. Used for "Meet our Vets," "Our Services," and "Pet Health Blog" sections.

### Chips & Tags
- Used for status (e.g., "Open 24h", "Specialist"). These use pill shapes (fully rounded) with a low-opacity Coral background and dark Coral text for high readability.

### Lists
- Medical or service lists should have generous vertical padding (16-24px) between items and a soft separator line to maintain the feeling of "clean space."

### Special Component: Emergency Banner
- A sticky header or floating bar in a slightly more vibrant Coral with a "+" symbol icon, ensuring the "24h Care" promise is always accessible.