# Chit Fund Manager

A simple, mobile-friendly web app to manage chit funds (committees). Built for organizers/foremen to track members, payments, and lifts — no server or database needed.

## Features

- **Create chit groups** — ₹50K, ₹1L, ₹2L, ₹5L presets (20 members, 20 months)
- **Track payments** — Mark members as paid via Cash or UPI with one tap
- **Give chit (lift)** — Select who receives the pot each month; rate auto-adjusts
- **Browse past months** — Navigate to any previous month to review or fix payments
- **Auto-save** — All data stored in your browser (localStorage), no account needed
- **Mobile-first** — Big buttons, clean UI, works great on phones

## How It Works

| Chit Value | Monthly (before lift) | Monthly (after lift) |
|---|---|---|
| ₹50,000 | ₹2,500 | ₹3,000 |
| ₹1,00,000 | ₹5,000 | ₹6,000 |
| ₹2,00,000 | ₹10,000 | ₹12,000 |
| ₹5,00,000 | ₹25,000 | ₹30,000 |

## Setup

**No installation needed.** Just open `index.html` in any browser.

### Host on GitHub Pages (free):

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to **Settings → Pages → Source → Deploy from a branch → main → / (root)**
4. Your app will be live at `https://yourusername.github.io/reponame/`

### Or just use locally:

Double-click `index.html` to open in your browser. That's it.

## Data Storage

All data is saved in your browser's localStorage. This means:
- Data persists across sessions (closing and reopening the browser)
- Data is per-device and per-browser (not synced across devices)
- Clearing browser data will erase the app data

## Tech

Single HTML file. No build step, no dependencies to install.
- React 18 (loaded from CDN)
- Tailwind CSS (loaded from CDN)
- localStorage for persistence

## License

MIT
