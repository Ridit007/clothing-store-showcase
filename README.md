# Clothing Store Showcase

A single-page showcase website for a clothing store: 3D hero, new arrivals with stock status, and a "best time to visit" crowd planner. No build step, no dependencies.

## Deploy on Vercel
1. Import this repo at https://vercel.com/new
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Deploy.

## Customize for a client
Open `index.html` and edit the blocks at the top of the `<script>`:
- `CONFIG`: store name, WhatsApp number (country code, no `+`), phone, address, Maps link, hours, photos
- `PRODUCTS`: name, category, price, tag, stock (`in` / `low` / `out`), optional `img` photo URL
- `CROWD`: crowd level 1 (quiet) to 5 (peak) for each hour, 10 AM to 9 PM

Put your own photos in an `assets/` folder and point `CONFIG.photos` / product `img` at them (e.g. `assets/rack.jpg`).
