# AimSense AI

An FPS aim analyzer powered by Claude Vision. Upload a gameplay clip, get a full coaching report with rank tier, performance scores, drills, and frame-by-frame breakdown.

**No installs. No server. Runs entirely in your browser.**

---

## Supported Games

VALORANT · CS2 · Apex Legends · Overwatch 2 · Rainbow Six Siege · Warzone · Fortnite

---

## How to Use

1. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
2. Open `index.html` in your browser (or visit the GitHub Pages link)
3. Paste your API key — it stays in your browser, never shared
4. Select your game
5. Upload a gameplay clip (MP4, MOV, AVI)
6. Click **Analyze Gameplay**

Analysis takes 60–90 seconds. Results include:

- Rank tier (Iron → Radiant)
- Overall score + Crosshair / Tracking / Consistency / Reflex / Positioning scores
- Performance radar chart
- Coaching analysis
- Recommended drills
- Quick tips
- 30 frame-by-frame thumbnails with quality ratings

---

## Cost

Each analysis costs roughly **$0.10–$0.20** from your Anthropic API balance. A $5 top-up covers ~30 analyses.

---

## Privacy

- Your video never leaves your device — frames are extracted in the browser using the HTML5 Canvas API
- Your API key is stored only in your browser's localStorage
- The only data sent externally is frame images → Anthropic's API for analysis

---

## Run Locally

Just open the file:

```bash
open index.html
```

No installs required.

---

## Deploy to GitHub Pages

1. Fork or upload `index.html` to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to **main branch**
4. Share the link
