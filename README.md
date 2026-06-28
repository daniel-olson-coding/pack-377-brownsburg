# Pack 377 — Brownsburg

The public website for **Cub Scout Pack 377** (Brownsburg, IN — serving all of Hendricks County),
published with **GitHub Pages**. It shares the pack's recruiting material — currently the
"Scouting Year" flyer — and the details for **Join Night: Thursday, August 20, 2026, 6:30–8:00 PM**.

**Live site:** https://daniel-olson-coding.github.io/pack-377-brownsburg/

## How it works

A static site — plain HTML + one CSS file, no build step — served from the root of `main`.

| Path | What it is |
|------|------------|
| `index.html` | The landing page. |
| `assets/styles.css` | All styling (Cub Scout Blue / Gold / Scout Red brand palette). |
| `assets/flyer-scouting-year*.png/.webp` | The flyer shown on the page (WebP for the web, full PNG for sharing). |
| `flyers/pack-377-scouting-year-2026.pdf` | The print-quality flyer download. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll processing). |

To preview locally, open `index.html` in a browser (or run any static server from the repo root).

## Contributing

Only finished, sanitized, publicly-shareable material belongs here — see [CLAUDE.md](CLAUDE.md)
for the publish gate. Source material (facts, branding, copy, original assets) lives in the
private `pack-377-marketing` repository.

Questions about the pack: **pack377bb@gmail.com**
