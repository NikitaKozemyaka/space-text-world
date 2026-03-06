# AGENTS.md

## Cursor Cloud specific instructions

This is a zero-dependency, single-file static website (`index.html`) — a promotional landing page for "Space Text World" Telegram MMO game.

### Running the dev server

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/` in the browser. No build step, no package manager, no Node.js required.

### Key notes

- There are **no linters, tests, or build tools** configured in this project. The entire site is a single `index.html` with inline CSS and JS.
- Google Fonts (Orbitron, Exo 2) are loaded from CDN; the page works without internet but falls back to sans-serif.
- CTA buttons link to `https://t.me/SpacetextworldBot` (set in the `<script>` block at the bottom of `index.html`).
- README is in Russian and contains deployment instructions for GitHub Pages / Netlify / Vercel.
