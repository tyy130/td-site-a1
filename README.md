# TacticDev Website

Modern, minimalist website for TacticDev.com - engineered for clarity and precision.

## Design Philosophy

This website embodies a quiet, modern, and engineered aesthetic with:

- **White/light backgrounds** (#FAFAFA) with **near-black text** (#1A1A1A)
- **Large, restrained typography** with strong vertical rhythm
- **Generous whitespace** and thin structural dividers
- **Schematic components** that feel engineered, not decorative
- **Subtle, purposeful motion** and transitions
- **Ambient video** background (optional, with graceful fallback)
- **Sparing accent color** (blue #0066FF) used only for intentional actions

## Structure

```
├── index.html          # Main HTML structure
├── styles.css          # Complete design system and styles
├── script.js           # Subtle interactions and animations
├── assets/             # Media assets (videos, images)
│   └── README.md       # Asset specifications
└── README.md           # This file
```

## Features

### Design System
- **8px-based spacing system** for consistent vertical rhythm
- **Responsive typography** using clamp() for fluid scaling
- **CSS custom properties** for maintainable theming
- **Mobile-first responsive design**

### Sections
1. **Header** - Fixed navigation with smooth scroll
2. **Hero** - Full-height introduction with optional ambient video
3. **Services** - Grid layout with numbered service cards
4. **About** - Company description with key statistics
5. **Contact** - Call-to-action with accent button
6. **Footer** - Minimal links and copyright

### Interactions
- Smooth scroll navigation
- Fade-in animations on scroll
- Subtle hover effects on interactive elements
- Semi-transparent header backdrop with blur
- Graceful video fallback

## Running Locally

Simply open `index.html` in a modern web browser, or use a local server:

```bash
# Python 3
python3 -m http.server 8080

# Node.js (with http-server)
npx http-server -p 8080
```

Then navigate to `http://localhost:8080`

## Customization

### Colors
Edit CSS custom properties in `styles.css`:
```css
:root {
    --color-background: #FAFAFA;
    --color-text-primary: #1A1A1A;
    --color-accent: #0066FF;
}
```

### Typography
Fonts can be changed via the `--font-sans` variable. Current default uses Inter with system fallbacks.

### Video Background
Place your ambient video at `assets/ambient-bg.mp4`. See `assets/README.md` for specifications.

## Browser Support

Works in all modern browsers supporting:
- CSS Grid
- CSS Custom Properties
- CSS clamp()
- Intersection Observer API

## License

© 2024 TacticDev. All rights reserved.

