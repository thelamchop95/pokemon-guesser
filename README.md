# Who's That Pokemon? — Stat Guesser

A browser game: read a Pokemon's height, weight, and Pokedex entry, then guess its name. Wrong guesses reveal hints (type, then generation); the artwork and name reveal on a correct guess or after three misses. Covers ~115 Pokemon across Generations 1–9, with a metric/imperial unit toggle.

It's a single static `index.html` file — no build step, no backend, no dependencies beyond a CDN-hosted icon font and Pokemon artwork.

## Deploy to GitHub Pages

1. Create a new repo on GitHub (or use an existing one).
2. From this folder:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add Pokemon stat guesser game"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: go to **Settings → Pages**, set "Source" to the `main` branch and `/ (root)` folder, then save.
4. Your game will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Run locally

Just open `index.html` in a browser — no server required.
