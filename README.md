# Artsy Places — World Art Gallery Map

A beautiful, interactive world art gallery map built for the "Artsy Places in NCR" WhatsApp community.

## Features
- 70+ art galleries across the world pinned on an interactive map
- Built-in directions (no switching apps!)
- Filter by region: India, Europe, Americas, Asia Pacific, Middle East, Africa
- Search by gallery name, city, or country
- Click any pin or card to see details
- Get directions with driving / walking / cycling modes
- Works on mobile and desktop

## How to deploy

### Option 1 — GitHub Pages (free)
1. Create a new repo on GitHub
2. Upload the `index.html` file
3. Go to Settings → Pages → Source: main branch
4. Your map is live at `https://yourusername.github.io/artsy-map`

### Option 2 — Vercel (free, faster)
1. Push this repo to GitHub
2. Go to vercel.com → New Project → Import your repo
3. Click Deploy — done in 30 seconds!

## Adding more galleries
Edit the `galleries` array in `index.html` — each entry looks like:
```js
{ name:"Gallery Name", city:"City", country:"Country", region:"India", lat:28.61, lng:77.23, address:"Full address" }
```

## Tech stack
- Leaflet.js for the map
- CartoDB tiles (free, no API key needed)
- Pure HTML/CSS/JS — no build step required
