# 🏛️ Patent Portfolio Page

**Built:** 2026-02-28 (Overnight YOLO Build)  
**Status:** Working — open `index.html` in any browser

---

## What it is

A beautiful, standalone HTML page showcasing Kishore's 4 UK patents from Mercedes-Benz R&D and his CoRL 2023 paper. Zero dependencies (fonts loaded from Google Fonts via CDN).

## Patents included

| # | Patent ID | Title |
|---|-----------|-------|
| 1 | GB2627443 | Camera selection for autonomous vehicles |
| 2 | GB2626533 | Route planning with terrain data |
| 3 | GB2629203 | Vehicle localization with landmarks |
| 4 | GB2634078 | Multi-vehicle positioning system |

## How to use

**Option 1 — Local:** Just open `index.html` in Chrome/Firefox/Safari

**Option 2 — Deploy to GitHub Pages (5 min):**
```bash
# From this folder:
git init
git add index.html
git commit -m "Patent portfolio page"
gh repo create kishore-patents --public --push --source=.
# Then enable GitHub Pages: Settings → Pages → Deploy from main
```

**Option 3 — Deploy to Vercel (2 min):**
```bash
npx vercel --yes
```

**Option 4 — Embed in kishorepagidi.com:**  
Copy the full HTML body and styles into your existing site.

---

## EB-1A Usage

This page is designed to be submitted as evidence for the **"Original Contributions"** and **"Patents"** criteria in an EB-1A petition. Features:
- Direct links to UK IPO official records (primary source)
- Callout explaining relevance to extraordinary ability criteria
- Professional enough to share with immigration lawyers directly

---

## Design

- Dark mode, animated grid background, card hover effects
- Responsive (mobile-friendly)
- Zero JS frameworks — pure HTML/CSS
- 26KB single file — loads instantly
