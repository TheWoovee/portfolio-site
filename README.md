# The Woovee — portfolio site

Personal intro page for **Jainullabdeen S** (The Woovee), Doha, Qatar — what I can do, how I work, and why I build. Not a résumé, not a project list.

- Single static page: `index.html` + `assets/`
- No build step, no framework. Fonts from Google Fonts.
- Two themes — **Ink** (dark) and **Sand** (light) — toggle in the nav; the choice is remembered. Force one with `?theme=ink` or `?theme=sand`.

## Run locally

Any static server works, e.g.

```bash
python -m http.server 8765
```

then open http://localhost:8765/.

## Deploy

Upload `index.html` and the `assets/` folder to any static host (Cloudflare Pages, Hostinger, GitHub Pages).
