# B1 — Route zur Prüfung 🎯

A self-contained study site for the Goethe / telc **B1 German exam (15 July 2026)**, built around a diagnosed set of weak spots (dropped Perfekt auxiliaries, verb-second slips, fixed prepositions, relative pronouns).

## Files

| File | What it is |
|------|------------|
| `index.html` | The main app — live countdown, 24-day plan with tickable tasks, speaking topics, writing templates, grammar cheat sheets, and an interactive preposition quiz. Progress is saved in the browser. |
| `cheatsheet.html` | A printable cheat sheet: exam-day glance page + a commute YouTube-watchlist (tap-to-search). |
| `B1_24_Tage_Plan.md` | The full written study plan. |

Everything is plain static HTML/CSS/JS — no build step, no dependencies (just Google Fonts loaded from a CDN).

## Deploy on Render (Static Site)

1. Push these files to a GitHub repo.
2. On Render → **New → Static Site** → connect this repo.
3. Settings:
   - **Build Command:** *(leave empty)*
   - **Publish Directory:** `./`
4. Create the site. Render serves `index.html` at the root URL; the cheat sheet is at `/cheatsheet.html`.

## Alternative: GitHub Pages

Repo **Settings → Pages → Source: Deploy from a branch → `main` / root**. Same result, served from `https://<user>.github.io/<repo>/`.

---
Tip baked into the design: tap a watchlist topic → watch a short video → immediately say 3 sentences out loud using it. Speaking closes the leaks, not watching.
