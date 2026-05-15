# Unity Focus Website

Static, single-page site for Unity Focus, the creative studio behind Sparko Sweets.
The site is a portfolio: Sparko Sweets is presented as the studio's flagship case study.

## Stack
Plain HTML, CSS, and vanilla JS. No build step. Deployed via GitHub Pages
(`CNAME` points the custom domain `unityfocus.co` at the repo).

## Run locally
Open `index.html` directly in a browser, or serve the folder:

```bash
cd ~/Documents/unity-focus-website
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Files
- `index.html`, page markup. Sections: Hero, The Work (Sparko case study), Studio, Founders, What's next, Footer
- `styles.css`, all styles, mobile-first. Palette: navy `#262666`, warm cream `#f3efe5`, electric blue `#4f6bff`
- `main.js`, sticky nav scroll behavior and mobile menu toggle
- `images/`, local image assets
- `CNAME`, GitHub Pages custom domain

## Placeholders to fill in
Draft copy is marked with `<!-- DRAFT COPY -->` comments and the manifesto with
`<!-- PLACEHOLDER MANIFESTO -->`. Write the real manifesto before going live.

Four image slots have no asset yet and are marked `<!-- IMAGE PENDING -->`:
- Two case study facets (Packaging system, Custom brand activations) render text-only.
  Each comment explains how to restore the 2-column image layout.
- The two founder cards render without portraits. Add one by inserting
  `<figure class="founder__portrait"><img .../></figure>` as the first child of
  `.founder` (its styling is already in `styles.css`).

All case study photography is served locally from `images/` (no external hotlinks).
The Sparko source files are square product shots and crop to fit; replace with wider
hi-res shots when available.
