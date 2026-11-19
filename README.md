# Sarwa Feature Concepts

Three working prototypes for gaps in the Sarwa app, built to the app's own patterns.

**Live:** https://wamiqadnan.github.io/sarwa-concepts/

| Concept | What it does | Prototype |
|---|---|---|
| 🎯 Goals & What-If Planner | Set a target and date on a named account like "New House", see your odds of hitting it, and fix the gap with one tap | [Open](https://wamiqadnan.github.io/sarwa-concepts/features/goal-planner/) |
| 🌙 Zakat, worked out | One Zakat figure across Invest, Trade and Save, in English and Arabic (RTL) | [Open](https://wamiqadnan.github.io/sarwa-concepts/features/zakat/) |
| 📅 Passive Income Calendar | See when your dividends land and what you keep after US tax | [Open](https://wamiqadnan.github.io/sarwa-concepts/features/income-calendar/) |

## How it's built

- Plain HTML, CSS and JavaScript. No framework and no build step; each prototype is one self-contained file.
- One state object per prototype, with each screen a pure render of it.
- Hand-drawn SVG charts that scrub with pointer or arrow keys and announce values through `aria-live`.
- Logical CSS properties, so the EN / ع toggle mirrors the layout for Arabic.
- Screens and edge states open from the URL, e.g. `?screen=whatif` or `?state=error`.

Run locally with any static server, e.g. `python3 -m http.server`, then open `http://localhost:8000`.

---

An independent concept by Wamiq Adnan. Not affiliated with or endorsed by Sarwa. Figures in the prototypes are illustrative.
