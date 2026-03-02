# STALKER ANOMALY THEME - ATMOSPHERIC EDITION

## Overview
Your portfolio now features a completely redesigned **dark Stalker-type theme** with a post-apocalyptic, radiation zone atmosphere. The theme emphasizes atmospheric decay, industrial deterioration, and mysterious SCP-style aesthetics.

## 🎮 **Key Changes from Previous Theme**

### Header Redesign
✅ **Terminal icon removed** - Clean, minimalist approach  
✅ **New header style** - Uppercase, spaced-out typography with atmospheric framing  
✅ **Contextual labels** - "[CLASSIFIED]" and "[SCP-CLASS]" tags frame the title  
✅ **Flicker animation** - Subtle opacity flicker creates unstable, eerie feel  
✅ **Rust color scheme** - Brown/rust tones replace amber for weathered aesthetic  

### New Visual Features
- **Flicker animation** on header and page load for instability effect
- **Atmospheric background** with radial gradient glow emanating from top
- **Scanline overlay** on content boxes for CRT monitor feel
- **Rust/decay color palette** instead of gold - more authentic post-apocalyptic vibe
- **Dashed borders** on links for fragmented appearance
- **Custom bullet points** (◆) in lists with rust accent
- **Info boxes** with gradient backgrounds and subtle scanlines

## 🎨 **Color Palette**

| Variable | Color | Purpose |
|----------|-------|---------|
| `--bg-void` | #050607 | Deep black void background |
| `--bg-decay` | #0f1215 | Slightly lighter secondary background |
| `--bg-panel` | #111820 | Content container background |
| `--text-primary` | #a8a8a8 | Main readable text |
| `--text-secondary` | #5a5a5a | Dimmed secondary text |
| `--accent-rust` | #8b4513 | Rust/decay brown - headers, borders |
| `--accent-radiation` | #4a7c4e | Forest green - radiation zone feel |
| `--accent-decay` | #7d7d3f | Khaki/mustard - subtle accents |
| `--accent-danger` | #cc3333 | Red - warning/danger indicators |
| `--border-broken` | #2a3a35 | Dark teal borders |

## 🎬 **CSS Animations**

### Flicker Animation
- Triggers on header and page elements
- Creates subtle opacity variations
- Mimics failing electronics/unstable anomaly zones
- 3-4 second cycle for authenticity

### Glitch Shift Animation
- Available for future use (not currently active)
- Can be applied for extra distorted vibe

## 🎯 **Design Elements**

### Header
```
       [ CLASSIFIED ]
    ADAM LASÁK - PORTFOLIO
       [ SCP-CLASS ]
```
- Monospace, uppercase typography with wide letter spacing
- Contextual framing labels with danger red color
- Subtle flicker effect
- Rust-colored text (#8b4513)

### Content Boxes
- Dark panel background with gradient overlay
- Thick rust-colored left border (3px)
- Scanline effect overlay
- Soft radiation green glow
- Inset shadows for depth

### Links
- Khaki/mustard color with dashed underline
- Hover state: Changes to radiation green with glow effect
- Visited state: Muted brown with reduced opacity

### Lists
- Custom diamond bullets (◆) in rust color
- Improved spacing and readability
- Clean appearance without default browser bullets

### Info Sections (CV & Contact)
- Semi-transparent gradient backgrounds
- Scanline overlay effect
- Dark teal borders with rust left accent
- Contained relative positioning to maintain depth

## 🖥️ **Typography**

**Primary Fonts:**
- `Jura` - Technical, monospace feel
- `Rajdhani` - Clean, geometric fallback

**Font Usage:**
- Headers (h1, h3): Bold, uppercase with letter-spacing
- Body text: Lighter weight for readability
- Footer: Uppercase with letter-spacing for emphasis

## ♿ **Accessibility**

- High contrast ratios maintained for readability
- Subtle animations don't interfere with content comprehension
- Text remains clear despite scanline overlay
- Color choices avoid red-green colorblindness issues
- Flicker effect is gentle and non-photosensitive

## 🎨 **Customization Tips**

### Change Rust Accent Color
Edit `--accent-rust` in the `:root` section:
```css
--accent-rust: #your-color-here;
```

### Adjust Flicker Speed
Modify the animation duration:
```css
animation: flicker 3s infinite; /* Change 3s to desired duration */
```

### Remove Scanlines
Modify `#content::before`:
```css
background: none; /* Removes scanline effect */
```

### Change Header Label Text
Edit the HTML in `index.html`:
```html
<h1>
  [Your-Custom-Label-Left]
  Adam Lasák - portfolio
  [Your-Custom-Label-Right]
</h1>
```

## 📁 **File Structure**

- **css/styles.css** - Complete theme stylesheet (352 lines)
- **index.html** - HTML structure with header-underscore hidden via CSS
- **STALKER_THEME_README.md** - This documentation

## 🔮 **Features at a Glance**

✅ Deep void background with atmospheric gradient  
✅ Flicker animation for instability  
✅ Rust/decay color palette  
✅ Radiation zone green accents  
✅ Scanline CRT monitor overlay  
✅ Glowing shadows and atmospheric effects  
✅ Custom scrollbar with rust styling  
✅ Dashed link borders for fragmented feel  
✅ Info boxes with gradient backgrounds  
✅ SCP-style header framing  

---

**Welcome to the Zone.** ☢️ 🎮



