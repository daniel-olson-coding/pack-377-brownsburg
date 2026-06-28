# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is the **PUBLIC** website for Cub Scout Pack 377 (Brownsburg, IN), published via
**GitHub Pages** at `https://daniel-olson-coding.github.io/pack-377-brownsburg/`. Its job is to
share finished recruiting material — flyers and other marketing pieces — with the public.

Everything committed here is **world-visible and permanent** (git history survives deletion, and
GitHub Pages serves it publicly). Treat every file as if it were already printed in the newspaper.

## ⛔ The publish gate — the most important rule

**Only commit a file here if ALL THREE are true.** If any one is in doubt, do NOT add it — leave
it in the private `../pack-377-marketing/` repo and ask.

1. **Ready for publish** — a finished, signed-off deliverable, not a draft, a work-in-progress,
   or an internal note. No `⚠️ confirm` / unverified facts (e.g. council, district, charter org).
   No `[CONFIRM]`/`[FIX]` annotations, no editor work-orders, no planning docs.
2. **Sanitized** — contains nothing internal or private: no personal contact info beyond the
   pack's public address (`pack377bb@gmail.com`), no children's names/photos without cleared
   permission, no home addresses, no leadership personal details, no API keys or credentials.
3. **Legally clear to use** — we have the right to publish it. Finished pack flyers/exports
   (PDF/PNG) are made for public handout and are fine. **Never** publish raw official assets,
   Brand Center source files, licensed stock, or anything git-ignored/local-only from the private
   repo. Do not recreate or AI-fake the Cub Scouts emblem in site chrome — use a **text lockup**
   ("PACK 377 · CUB SCOUTS") in brand colors; official emblems appear only inside finished,
   licensed flyer images.

**Where things come from:** publishable artifacts originate in the private repo
`../pack-377-marketing/` (the source of truth for facts, branding, copy, and assets). Pull finished
exports from `../pack-377-marketing/deliverables/`. When unsure whether something clears the gate,
default to private.

## Site conventions

- **Static site, no build step.** Plain HTML/CSS served from the repo root on branch `main`.
  `.nojekyll` is present so GitHub Pages serves files as-is without Jekyll processing.
- **Relative asset paths only** (e.g. `assets/…`, `flyers/…`) so the site works under the
  `/pack-377-brownsburg/` Pages subpath. No absolute `/…` paths.
- **Brand basics** (full system in `../pack-377-marketing/knowledge/branding.md`): Cub Scout Blue
  `#003F87`, Gold `#FCD116`, Scout Red `#CE1126`. Program is **Cub Scouts** (part of Scouting
  America) — never "Boy Scouts." Every recruiting piece must carry both required lines:
  "for kids in grades K–5" and "based in Brownsburg, serving all of Hendricks County."

## Layout

| Path | What lives here |
|------|-----------------|
| `index.html` | The landing page. |
| `assets/` | Site CSS and web images (e.g. flyer preview PNGs). |
| `flyers/` | Downloadable finished flyers (PDF). |
| `.nojekyll` | Disables Jekyll so files serve verbatim. |
