# 🏍️ BikePartsBD.net | Kayi Corporation — Inventory OS

A live inventory, courier tracking & vendor contact dashboard for **Kayi Corporation** (bikepartsbd.net, Jashore outlet, Bangladesh).

## ✨ Features

- **📦 Inventory** — 5 sample Yamaha / Suzuki / Bajaj parts loaded. Auto SKU, auto Bangla translation, auto brand & category detection. Inline price editing with red flash + delta pill.
- **🏷️ 3-Field Add Part** — Just product name + buying price + selling price. SKU, Bangla, brand, category, profit, margin auto-generated.
- **🇧🇩 Bangla-First** — Bilingual UI (বাংলা + English) for the Inventory, Courier, and Vendor modules. Auto English → Bangla dictionary (60+ terms).
- **🛵 Courier Tracking** — Sundarban, SA Paribahan, Karotoa, Janani. Per-courier gross revenue & gross profit (Bengali + English). 5-stage timeline (Placed → Picked Up → In Transit → Out for Delivery → Delivered).
- **📞 Vendor Contacts** — One-tap **WhatsApp** (bilingual pre-filled message) and **Call** to 6 pre-loaded vendors matched by brand.
- **🚨 Emergency Restock** — Click "1-Click Restock" to see every low-stock part with the top 3 matching vendors and direct call/WhatsApp links.
- **🌗 Dark + Light Mode** — Toggle in the top bar, preference saved to `localStorage`. Brand red `#e10600` consistent in both.
- **📊 Live Simulation** — Click "Start Live Simulation" to watch sales stream in from Messenger, WhatsApp & Website in real-time, with stock auto-deduction and courier auto-advance.

## 🚀 Live Demo

Hosted on **GitHub Pages**: see the link your engineer shared.

Local: just open `index.html` in any browser, or run a static server:
```bash
python3 -m http.server 3001
# then open http://localhost:3001
```

## 🛠️ Tech

- **Single file**: `index.html` (~90 KB, no build step, no dependencies)
- **Vanilla JavaScript** — no React, no jQuery
- **CSS variables** for theming with full dark + light mode
- **Google Fonts**: Inter (UI) + JetBrains Mono (numbers)
- **Responsive** — works on phone, tablet, laptop, desktop

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The complete single-file application |
| `README.md` | This file |
| `.nojekyll` | Tells GitHub Pages to serve as-is, no Jekyll processing |

## 📱 Mobile / Desktop

- Phone (<600px): stacked layout, hidden non-essential columns, full-width buttons
- Tablet (600–1100px): 2-column grids, condensed side panel
- Desktop (>1100px): full layout with 360px side panel

## 🎨 Brand

- **Primary**: BikePartsBD Red `#e10600`
- **Typography**: Inter (UI) + JetBrains Mono (prices, SKUs)
- **Logo**: "BP" mark in red rounded square

---

© 2026 Kayi Corporation · Jashore, Bangladesh
