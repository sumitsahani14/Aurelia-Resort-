# Aurelia Resort — Where the World Begins

A luxury resort website featuring a full-bleed hero, destination gallery, rooms showcase, dining section, testimonials, and a booking banner.

## Tech Stack

- Pure HTML, CSS, JavaScript — no frameworks, no build tools
- Google Fonts: Cormorant Garamond & Jost
- Unsplash images (CDN-hosted, no downloads needed)

## Features

- Custom animated cursor
- Scroll-triggered reveal animations
- Sticky nav with blur on scroll
- Responsive layout with mobile navigation and optimized tablet/mobile layouts
- Floating "Reserve a Stay" button
- Sections: Hero → About → Destinations → Rooms → Quote → Experiences → Dining → Testimonials → Booking → Footer

## Deploy on Vercel

### One-click via Vercel Dashboard
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo
4. Leave all settings as default — Vercel auto-detects static HTML
5. Click **Deploy**

### Via Vercel CLI
```bash
npm i -g vercel
vercel
```

## Local Development

No build step needed. Just open `index.html` in a browser:

```bash
# Using Python
python3 -m http.server 3000

# Using Node (npx)
npx serve .
```

Then visit `http://localhost:3000`

---

© 2025 Aurelia Resort Collection
