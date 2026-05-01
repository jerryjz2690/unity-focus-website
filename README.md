# Unity Focus Website

Static, single-page site for Unity Focus, a Los Angeles-based sweets and snacks company.

## Stack
Plain HTML, CSS, and vanilla JS. No build step.

## Run locally
Open `index.html` directly in a browser, or serve the folder:

```bash
cd ~/Documents/unity-focus-website
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Files
- `index.html`, page markup
- `styles.css`, all styles, mobile-first
- `main.js`, sticky nav scroll behavior and mobile menu toggle
- `images/`, drop product and brand photography here (currently using placehold.co placeholders)

## Replacing product images
Each product card uses a placeholder from `placehold.co`. To swap in real photography,
add files to `images/` and update the `src` attributes inside `index.html`.
