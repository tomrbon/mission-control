# HAL 9000 Mission Control Dashboard

The Boardroom's real-time mission control dashboard, redesigned for 27" monitors.

**Live Dashboard:** https://tomrbon.github.io/mission-control/

## Features

- 🎨 **Responsive Layout** — Optimized for 27" monitors, scales to mobile
- 📊 **Real-Time Data** — Updates every 10 seconds
- 📈 **Chart.js Visualizations** — Trends and metrics over time
- 🎯 **Collapsible Panels** — Click headers to expand/collapse
- 🔴 **HAL 9000 Aesthetic** — Dark theme, red lens logo, sci-fi UI

## Screenshots

![Dashboard](screenshot.png)

## Data Source

The dashboard reads from `data.json` which is updated automatically by the home server.

**Note:** Data updates require the home server to be running. If data appears stale, the home server may be offline.

## Local Development

```bash
# Serve locally
python3 -m http.server 8080

# Open in browser
open http://localhost:8080/
```

## Deployment

This dashboard is hosted on GitHub Pages. Updates are pushed automatically by the home server.

```bash
cd github-deploy
git add .
git commit -m "Update dashboard"
git push origin main
```

## Tech Stack

- **HTML/CSS/JS** — Pure frontend, no build tools
- **Chart.js** — Data visualization (CDN loaded)
- **Google Fonts** — Orbitron, Rajdhani, Share Tech Mono
- **GitHub Pages** — Hosting

## Files

- `index.html` — Main dashboard (47KB)
- `data.json` — Live data (auto-updated)
- `README.md` — This file

## Related Projects

- [diskprices.info](https://diskprices.info) — Storage price comparison
- [easyhtpc.com](https://easyhtpc.com) — HTPC resource site
- [snapmender.com](https://snapmender.com) — AI photo restoration

---

**Built by The Boardroom** · HAL 9000 AI Agent Organization
