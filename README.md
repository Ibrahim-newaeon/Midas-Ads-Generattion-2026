# Midas Ad Template Generator

Generate product ad templates for **Midas Furniture** across Meta, TikTok & Snapchat.

## Features
- 5 platforms: Meta Feed 1:1, Meta 4:5, Meta Story 9:16, TikTok, Snapchat
- 5 templates: Product Hero, Sale/Promo, New Arrival, Eid/Ramadan, Lifestyle
- 7 color schemes using official Midas brand colors
- 4 Gulf markets: KW, KSA, QAT, JOR with auto-currency
- Saudi Riyal new symbol (U+20C1) support
- Multi-product upload with per-product pricing
- Old/new price with strikethrough + auto discount badge
- EN/AR bilingual with Cairo font
- 9:16 story safe zones (250px top/bottom)
- PWA installable — works offline
- Single HTML file, zero build step

## Deploy

### Option 1: Netlify Drop (5 seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this entire folder into the browser
3. Done — you get a shareable URL

### Option 2: GitHub Pages
1. Create a new repo on GitHub
2. Push this folder to the repo
3. Go to Settings → Pages → Source: main branch → Save
4. URL: `https://yourusername.github.io/repo-name`

### Option 3: Vercel
```bash
npx vercel
```

### Option 4: Cloudflare Pages
1. Go to [dash.cloudflare.com](https://dash.cloudflare.com)
2. Pages → Create → Upload assets → drag folder
3. Done

## Install as App (PWA)
Once deployed, users can install it:
- **Chrome/Edge**: Click the install icon in the address bar
- **Safari iOS**: Share → Add to Home Screen
- **Android**: Banner auto-prompts or Menu → Install app

## Tech
- Pure HTML/CSS/JS — no framework, no build
- Canvas API for rendering
- Cairo font (Google Fonts CDN)
- Saudi Riyal font (jsdelivr CDN)
- Service worker for offline caching
