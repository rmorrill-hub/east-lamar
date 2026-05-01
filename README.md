# East Lamar Boarding & Training School — Website

Production-ready website for East Lamar Boarding & Training School in East Austin.

**Live:** eastlamar.com (deployed on Netlify)

## Overview

A fully responsive, single-page marketing website built with:
- **HTML5** — semantic, accessible structure
- **CSS3** — custom design system with CSS variables, mobile-first responsive design
- **JavaScript** — smooth scrolling, modal interactions, icon rendering via Lucide
- **Fonts** — Google Fonts CDN (Fraunces + Plus Jakarta Sans)
- **Images** — optimized JPEG and PNG photography

## Features

- Sticky navigation with smooth scroll anchors
- Hero section with CTA buttons and Google rating badge
- Services grid (Boarding, Daycare, Training) with image backgrounds
- Daily schedule transparency section with stats cards
- "Meet Lamar" bio section with credentials
- 6 client testimonials + Google rating card
- "East Austin Spaces" section showcasing new properties
- Neighbors ATX cross-promotion
- Responsive footer with links and contact info
- Booking modal with three option flows
- Fully responsive (mobile 375px → desktop 1200px+)
- Accessible touch targets (min 44px)
- Smooth transitions and hover states

## Project Structure

```
website/
├── index.html          ← main page, all styles + scripts inline
├── images/             ← photography + logo
│   ├── IMG_6066.jpeg
│   ├── IMG_6144.png
│   ├── IMG_6212.png
│   ├── IMG_6213.png
│   ├── IMG_6607.jpeg
│   ├── IMG_7100.jpeg
│   ├── IMG_7114.jpeg
│   ├── IMG_7387.jpeg
│   ├── IMG_8758.jpeg
│   ├── lamar.jpg
│   └── east_lamar_logo.png
├── netlify.toml        ← deployment config
└── README.md           ← this file
```

## Design Tokens

**Colors:**
- Primary Teal: `#0B7B72`
- Dark Teal (hero bg): `#092E2B`
- Bright Accent Teal: `#25B0A5`
- Teal Wash: `#E6F7F6`
- Golden Amber: `#F0B429`
- Dark Gold: `#B07000`
- Gold Wash: `#FEF3CC`

**Typography:**
- Display: Fraunces (serif, variable from Google Fonts)
- Body: Plus Jakarta Sans (sans-serif, from Google Fonts)
- Heading scale: h1 40-72px fluid, h2 32-52px, h3 22-30px

**Spacing:** 24px base unit, scales via CSS variables

**Radius:** 14px standard, 100px pill buttons, 20px large cards

## Responsive Breakpoints

- **Mobile:** < 480px (single column, reduced padding)
- **Tablet:** 481–768px (2 columns for cards, stacked schedule)
- **Desktop:** 769px+ (full 3-column grids, side-by-side layouts)

## Deployment on Netlify

1. Connect this repo to Netlify
2. Build command: (none needed — static HTML)
3. Publish directory: `.` (root)
4. Deploy

The `netlify.toml` config includes:
- Security headers (X-Frame-Options, Content-Type-Options)
- Image caching (1-year max-age for assets)
- SPA redirect (all 404s → index.html for anchor-based routing)

## Local Development

Open `index.html` in a browser. No build step required.

For testing on different devices, use Chrome DevTools (Ctrl/Cmd + Shift + M) or actual device preview.

## Brand Voice

"We lead with love, every single day."

All copy reflects warmth, professionalism, and genuine care for dogs and their families.

## Contact

- **Email:** boarding@eastlamar.com
- **Address:** 2001 E 12th St, Austin, TX 78702
- **Instagram:** @east.lamar
- **Sister Business:** Neighbors ATX Dog Park (neighborsatx.com)

---

Built April 2026 | East Austin
