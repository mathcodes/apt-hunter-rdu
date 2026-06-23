# 🏠 Apt Hunter – Raleigh/Durham

An interactive apartment map for the Raleigh–Durham area. Zero dependencies — pure HTML/CSS/JS with a Web Mercator canvas renderer.

## Features

- **27 apartments** plotted on a pannable, zoomable canvas map
- **Color-coded pins** by price tier (green / yellow / red)
- **Sidebar list** synced to the map — click either to highlight both
- **Price filters** to show/hide by tier
- **Google Maps deep links** in each popup
- **No API keys, no CDNs** — works offline

## Price Tiers

| Color | Range |
|-------|-------|
| 🟢 Green | Under $1,100/mo |
| 🟡 Yellow | $1,100–$1,400/mo |
| 🔴 Red | Over $1,400/mo |

## Deploy

Deployed via [Vercel](https://vercel.com) as a static site.

```bash
vercel --prod
```

## Dev

Just open `index.html` in a browser — no build step needed.
