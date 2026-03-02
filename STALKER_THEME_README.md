# STALKER Dark Theme Design

## Overview
Your portfolio now features a dark theme inspired by the S.T.A.L.K.E.R. video game series, creating a post-apocalyptic, atmospheric vibe with industrial and gritty aesthetics.

## Theme Features

### Color Palette
- **Dark Background**: Deep black (#0a0e0f) with subtle green scanline patterns
- **Secondary Background**: Dark charcoal (#141a1d) for content containers
- **Primary Text**: Light gray (#c0c0c0) for comfortable readability
- **Accent Colors**:
  - **Amber/Gold** (#d4af37): Main headings and links - gives a warm, glowing feel
  - **Forest Green** (#2b8a2b): Accents, borders, and decorative elements - evokes the post-apocalyptic zone
  - **Cyan** (#00d4aa): Hover effects and secondary headings - provides sci-fi terminal feel

### Visual Effects

#### 1. **Scanline Effect**
- Horizontal scanlines across the entire page background and content area
- Mimics old CRT monitors and creates an authentic retro-futuristic vibe
- Subtle and non-intrusive (3% opacity)

#### 2. **Glow Effects**
- Headings glow with soft green and gold shadows
- Links glow on hover with cyan accent
- Terminal icon (#header-underscore) has a green glow effect
- Horizontal divider line has a green box shadow for atmospheric separation

#### 3. **Borders & Shadows**
- Dark, muted borders (#1a2d2a) instead of bright lines
- Inset shadows on content containers create depth
- Subtle outward glow suggesting radiation/energy emanation

#### 4. **Typography**
- Primary fonts: **Rajdhani** and **Jura** - geometric, technical fonts perfect for sci-fi aesthetic
- Increased letter spacing on headings for dramatic effect
- All headings use text shadows for depth

### Interactive Elements

#### Links
- Default color: Warm amber/gold
- Hover state: Cyan with glow effect
- Visited state: Darker golden brown
- Smooth 0.3s transitions

#### Scrollbar
- Custom styled with green glow
- Changes to cyan on hover
- Rounded appearance for modern look

#### Selection
- Text selection uses forest green background
- Maintains readability with dark text on green

## CSS Variables Reference
All colors are defined as CSS variables for easy customization:

```css
--color-bg-dark: #0a0e0f;           /* Main background */
--color-bg-secondary: #141a1d;      /* Content boxes */
--color-text-primary: #c0c0c0;      /* Main text */
--color-text-secondary: #808080;    /* Secondary text */
--color-accent-amber: #d4af37;      /* Gold/amber accents */
--color-accent-green: #2b8a2b;      /* Radiation zone green */
--color-accent-cyan: #00d4aa;       /* Sci-fi cyan */
--color-border: #1a2d2a;            /* Dark borders */
--color-glow: #2b8a2b;              /* Glow color */
```

## Customization

### Change Color Scheme
Edit the CSS variables at the top of `styles.css`:

```css
:root {
  --color-bg-dark: #new-color;
  /* ... modify other colors as needed */
}
```

### Adjust Scanline Intensity
Modify the opacity in the `repeating-linear-gradient`:
- Current: `rgba(43, 138, 43, 0.03)` = 3% opacity
- Increase second value for more visible scanlines
- Set to `0.0` to disable

### Change Font
Modify the `font-family` in the `html` selector:
```css
html {
  font-family: 'Your-Font-Here', fallback-font, sans-serif;
}
```

## Compatibility
- Modern browsers: Chrome, Firefox, Safari, Edge
- CSS features used:
  - CSS Variables (--custom-properties)
  - CSS Gradients
  - Box Shadow & Text Shadow
  - Pseudo-elements (::before, ::selection)
  - Smooth transitions

## Accessibility
- High contrast ratios maintained for text readability
- Glow effects are subtle and don't interfere with content
- Selection color provides clear visual feedback
- Font sizes remain readable on all screen sizes

## File Structure
- **css/styles.css** - Complete theme styling (242 lines)
- **index.html** - HTML structure (unchanged)
- **STALKER_THEME_README.md** - This documentation

---

Enjoy your new post-apocalyptic portfolio theme! 🎮☢️

