# Personal Website - Project Context

## Overview
This is Remy Gaskell's personal landing page website. It's a simple, single-page site built with vanilla HTML, CSS, and JavaScript.

## Design Reference
The design is based on the **Ultra** Framer template (https://ultra.framer.website/). Reference files are in the `Website Design Swipefile/` folder:
- `ultra.framer.website.png` - Screenshot of the original template
- `ultra_framer_website.html` - Full HTML source of the original template

## Key Differences from Ultra Template
We have intentionally removed/modified these elements from the original Ultra design:
- **No left-hand side menu** - The original has navigation menus on the left; we've removed these for a cleaner, simpler layout
- **Reorganized sections** - Content sections have been adjusted to fit Remy's personal brand and content needs
- **Centered layout** - Content is centered with section labels positioned to the left on desktop

## Current Site Structure
The main file is `index.html` which contains:
- **Hero section**: Avatar, name, tagline, social icons, contact/copy email buttons, location coordinates
- **About section**: Bio text
- **Work section**: Project cards (currently placeholder content)
- **Stack section**: Tool/technology grid (Figma, Framer, Tailwind, Next.js, React, JavaScript, CSS, GitHub)
- **Footer**: Copyright notice

## Technical Details
- **Fonts**: Inter (body text) and DM Mono (monospace elements like time display)
- **Styling**: Custom CSS using CSS variables, no frameworks
- **Responsive**: Mobile-first with breakpoints at 809px and 1199px
- **Interactive features**:
  - Live time display
  - Copy email to clipboard with toast notification
  - Hover states on cards and buttons

## File Structure
```
/
├── index.html              # Main website file
├── CLAUDE.md               # This file
├── Website Assets/         # Images and assets
│   └── pfp.png            # Profile photo
└── Website Design Swipefile/
    ├── ultra.framer.website.png
    ├── ultra_framer_website.html
    └── [other reference screenshots]
```

## Owner Details
- **Name**: Remy Gaskell
- **Email**: remy@remygaskell.com
- **Location**: Melbourne, Australia (coordinates: 37.9394° S, 145.0006° E)
- **Social handles**: @remy_gaskell (X), @aiwithremy (Instagram, YouTube), @remygaskell (LinkedIn), @aiwithremy (GitHub)

## Design Principles
- Clean, minimal aesthetic
- Muted gray color palette with subtle hover interactions
- Typography-focused with generous whitespace
- Section labels appear to the left of content on desktop, inline on mobile
