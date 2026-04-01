# CardCaddy — Credit Card Rewards Optimizer

A PWA that recommends the best credit card for any purchase, optimized for Q2 2026.

## Files
- `index.html` — Full app (single file)
- `manifest.json` — PWA manifest
- `sw.js` — Service worker for offline support

## Deploy to Cloudflare Pages via GitHub

1. Create a new GitHub repo (e.g. `card-caddy`)
2. Push these 3 files to the repo root
3. Go to Cloudflare Pages → Create Application → Connect to Git
4. Select your repo
5. Build settings: leave blank (static site, no build command needed)
6. Deploy

## PWA Icons
Cloudflare Pages will serve without icons fine, but for full PWA install support
add `icon-192.png` and `icon-512.png` to the repo root.
You can generate these at https://favicon.io or use any 192x192 and 512x512 PNG.

## Updating for Q3 2026
1. Open the app → Edit tab
2. Change Quarter to Q3 2026
3. Edit Chase Freedom, Chase Freedom Flex, and Discover it cards
4. Update their rotating category names and keywords to Q3 categories
5. Everything saves to localStorage automatically

## Features
- 🔍 Vendor/store search with category inference
- 💳 Best cashback recommendation + runner-up
- 🛡️ Protection perk suggestions (cell phone, rental car, trip cancellation)
- 👛 Optimal wallet view (best in-person cards only)
- ⚡ Quarterly activation reminders
- ⚙️ Full edit mode — add/remove/edit cards anytime
- 📴 Works offline via service worker
