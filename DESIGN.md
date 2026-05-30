---
name: Lunar Bloom & Keepsake
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#504444'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#827473'
  outline-variant: '#d4c2c2'
  surface-tint: '#7b5455'
  primary: '#7b5455'
  on-primary: '#ffffff'
  primary-container: '#d4a5a5'
  on-primary-container: '#5d3a3b'
  inverse-primary: '#ecbbba'
  secondary: '#63597f'
  on-secondary: '#ffffff'
  secondary-container: '#ded1fe'
  on-secondary-container: '#61587e'
  tertiary: '#4f6260'
  on-tertiary: '#ffffff'
  tertiary-container: '#a0b5b2'
  on-tertiary-container: '#344745'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ecbbba'
  on-primary-fixed: '#2f1314'
  on-primary-fixed-variant: '#603d3e'
  secondary-fixed: '#e8ddff'
  secondary-fixed-dim: '#cdc0ec'
  on-secondary-fixed: '#1e1638'
  on-secondary-fixed-variant: '#4b4166'
  tertiary-fixed: '#d1e7e4'
  tertiary-fixed-dim: '#b6cbc8'
  on-tertiary-fixed: '#0b1f1d'
  on-tertiary-fixed-variant: '#374a48'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  card-padding: 1.5rem
---

## Brand & Style
The brand personality is intimate, nostalgic, and ethereal. It captures the fleeting beauty of a birthday through a cinematic lens, blending the warmth of a handwritten scrapbook with the polished aesthetic of vintage film photography. The design evokes a sense of "dreamy realism"—where personal memories are elevated into art.

The design system adopts a **Modern Scrapbook** style. This involves:
- **Cinematic Depth:** Using soft-focus imagery and subtle grain to mimic 35mm film.
- **Editorial Elegance:** High-end typography paired with ample "breathable" white space.
- **Tactile Accents:** Delicate floral illustrations, paper textures, and "taped" edge details that suggest a physical memento.

## Colors
The palette is rooted in muted, desaturated tones that feel like they have been aged by the sun and moon.
- **Dusty Pink (Primary):** Used for key actions and focal emotional elements.
- **Lavender (Secondary):** Provides a dreamy, twilight accent for secondary information and highlights.
- **Soft Green (Tertiary):** Inspired by eucalyptus and floral stems, used for decorative strokes and organic motifs.
- **Cream White (Surface):** The primary background color, providing a warm, paper-like foundation.
- **Moonlight (Accent):** A cool, silver-tinted blue for subtle borders and soft glow effects.

## Typography
The typography contrasts high-personality serifs with ultra-clean sans-serifs to maintain an editorial feel.
- **Headlines:** Use **Playfair Display**. It provides a sophisticated, high-contrast look that feels timeless and celebratory. It should be used for names, dates, and primary section headers.
- **Body & Labels:** Use **DM Sans**. This geometric sans-serif offers a modern, low-contrast counterpoint that ensures legibility within "scrapbook" layouts without distracting from the photography. 
- **Styling:** Use italicized serifs for emphasis to lean into the romantic, poetic nature of the theme.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Soft Glows** rather than harsh shadows.
- **Backdrop Blurs:** Used on navigation bars and overlays to create a "frosted glass" effect, keeping the focus on the underlying colors.
- **Shadows:** Only used for "floating" elements like photos or cards. These should be extremely diffused (Blur: 40px, Opacity: 8%) with a slight tint of the primary pink or lavender color.
- **Grain Overlay:** A global, low-opacity noise texture is applied to the entire UI to give it a tactile, cinematic film quality.

## Shapes
The shape language is **Soft (0.25rem)** to mimic the hand-cut edges of photos in an album. 
- **Images:** Most photos should have small radii, but "featured" memories may use a circular mask or a subtle organic "blob" shape to suggest a floral or moonlight motif.
- **Buttons:** Subtle rounding conveys approachability without becoming overly "app-like" or corporate.

## Components
- **Buttons:** Text-only or outlined with a thin 1px stroke. Filled buttons use a soft gradient of Dusty Pink to Moonlight.
- **Cards:** Defined by a change in background color (e.g., Cream to Moonlight) rather than borders. Often features a "taped corner" decorative element.
- **Floral Accents:** Vector illustrations of eucalyptus or daisies used as floating background elements or "stickers" on content blocks.
- **Interactive Lists:** Clean, high-line-height text with delicate separators using the Soft Green color at 20% opacity.
- **Input Fields:** Minimalist lines with Playfair Display placeholders to keep the intimate, handwritten feel.
- **Photo Polaroids:** A specific component for the "Sharon" theme; images wrapped in a thick Cream White border with a slight rotation (±2 degrees) for an organic look.