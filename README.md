# DVRS — Fitting Room

A one-page virtual fitting room for DVRS. ichi_x stands in a dark DVRS studio; a product carousel curves behind her, and the centred product is shown on her with a 350 ms crossfade.

- **Categories:** Bottoms, Outerwear, Shoes, Accessories (4 products each)
- **Controls:** arrows, ← → keys, drag/swipe, or click a card
- **Mobile (≤768px):** model on top, swipe row below, detail bar pinned to the bottom

## Run locally

Static site, no build step:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Works as-is on Vercel, Netlify or GitHub Pages (framework preset: "Other", no build command, output directory: root).

## Files

- `index.html` — the whole page (HTML, CSS, JS)
- `looks/look01–16.webp` — ichi_x wearing each product; all share one canvas so her pose never shifts. `look00.webp` is the base outfit.
- `products/p01–16.webp` — product shots on transparent backgrounds
