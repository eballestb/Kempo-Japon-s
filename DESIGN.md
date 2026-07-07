---
name: Bushido Modern
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#e4beba'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#ab8985'
  outline-variant: '#5b403d'
  surface-tint: '#ffb3ac'
  primary: '#ffb3ac'
  on-primary: '#680008'
  primary-container: '#d32f2f'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ba1a20'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#706f6f'
  on-tertiary-container: '#f7f4f3'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930010'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Archivo Narrow
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Archivo Narrow
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
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
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 4px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system embodies the spirit of contemporary Budo—the martial way. It is built on the pillars of **discipline, precision, and restrained power**. The aesthetic rejects the cluttered, high-energy tropes of Western commercial gyms in favor of a "Dojo" philosophy: a space of focused intent where every element has a purpose.

The visual style is **High-Contrast Minimalist with Neo-Brutalist influences**. It utilizes expansive dark voids to represent the quiet mind, punctuated by sharp, aggressive crimson strikes that signify action and vitality. The interface should feel as sharp as a blade—clean, uncompromising, and deeply professional. The target audience consists of serious practitioners and enthusiasts who value tradition but demand a modern, high-performance digital experience.

## Colors

The palette is strictly limited to maintain a sense of gravity and focus. 

- **Primary (Crimson):** Used exclusively for call-to-actions, critical highlights, and indicating active states. It represents the "In-yo" (Yin-Yang) balance of energy against the dark.
- **Backgrounds:** A tiered system of blacks. The base layer is a true deep black (`#0A0A0A`), while UI surfaces use Deep Charcoal (`#121212`) to provide subtle depth.
- **Typography:** Pure White (`#FFFFFF`) is used for primary content to ensure maximum legibility against the dark background. Muted labels use a 60% opacity white.
- **Accents:** Use a subtle "Ink Wash" grey (`#2A2A2A`) for borders and dividers to mimic the look of traditional Japanese sliding doors (Shoji) or tatami edges.

## Typography

The typography strategy pairs industrial strength with technical precision.

- **Headlines:** *Archivo Narrow* provides a tall, condensed, and disciplined feel reminiscent of traditional vertical calligraphy (Shodo) but rendered in a modern, sans-serif format. Always use uppercase for primary headings to command authority.
- **Body:** *Inter* ensures that long-form content, such as technique descriptions or philosophy, remains highly readable and neutral.
- **Technical/Labels:** *JetBrains Mono* is used for data points, timestamps, and metadata. This monospaced choice reinforces the "modern" aspect of the system, suggesting a structured, data-driven approach to training.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to create a centered, "meditative" focus point, while expanding to a **Fluid Grid** on mobile for efficiency.

- **The Power of "Ma":** "Ma" (negative space) is a critical component. Do not crowd the UI. Use generous margins (`64px+`) to separate major content blocks, forcing the user's eye to rest on one element at a time.
- **Alignment:** Use a 12-column grid. Elements should align strictly to the grid edges—no soft offsets.
- **Rhythm:** All spacing must be multiples of 4px. Use a larger vertical stack (`32px`) between unrelated components to maintain visual clarity.

## Elevation & Depth

This design system rejects soft shadows and realism. Depth is communicated through **Tonal Layering and Sharp Outlines**.

- **Surface Tiers:** Background is the lowest level (`#0A0A0A`). Cards and containers sit on top (`#121212`). Active or hovered elements use a slightly lighter grey (`#1A1A1A`).
- **Borders:** Use 1px solid borders (`#2A2A2A`) to define edges. On hover, primary components can transition to a Crimson border for a sharp, high-contrast effect.
- **Ink Brush Textures:** For high-impact areas (Hero sections, empty states), use subtle, low-opacity (5-10%) background textures resembling minimalist Sumi-e brush strokes. These should be static and not interfere with text legibility.

## Shapes

The shape language is **Sharp (0px)**. 

Every UI element—buttons, inputs, cards, and images—must have perfectly square corners. This reflects the precision of a katana blade and the rigid structure of a Dojo. Do not use rounded corners anywhere in the interface, as it softens the brand's disciplined and serious tone.

## Components

- **Buttons:** Primary buttons are solid Crimson (`#D32F2F`) with white text, uppercase Archivo Narrow. Secondary buttons are outlined (Ghost) with 1px white or grey borders. No gradients.
- **Cards:** Cards should have no shadow. They are distinguished from the background by a slight color shift to `#121212` and a thin `#2A2A2A` border.
- **Input Fields:** Bottom-border only (like a signature line) or a full 1px border. Backgrounds should be slightly darker than the surface they sit on. Use JetBrains Mono for the input text.
- **Chips/Badges:** Use a "Stamp" aesthetic—small, rectangular boxes with JetBrains Mono text. For status indicators, use a solid crimson block for "active" and a dark grey block for "inactive."
- **Lists:** Use thin horizontal dividers. Bullet points should be replaced by small, sharp crimson squares or vertical strokes.
- **Custom Iconography:** Use thin-stroke, geometric icons. Avoid rounded icon sets. All icons should be monochromatic (White or Crimson).