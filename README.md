# Red Flag Rush

A fast swipe-card cybersecurity awareness game built for Woodside Cyber Awareness Month. Swipe right (or tap ✓) to trust, swipe left (or tap ✕) to block, across 14 realistic phishing, smishing, deepfake, and social-engineering scenarios.

Single self-contained `index.html` — no build step, no dependencies beyond Google Fonts.

## Push to a new GitHub repo

```bash
cd red-flag-rush-repo
git init
git add index.html README.md
git commit -m "Add Red Flag Rush cyber awareness game"
git branch -M main
git remote add origin https://github.com/<your-username>/red-flag-rush.git
git push -u origin main
```

(Create the empty repo on GitHub first — no README/license/gitignore — so the push above doesn't hit a conflict.)

## Turn on GitHub Pages

1. On GitHub, open the repo → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)` → **Save**.
4. Your game goes live at `https://<your-username>.github.io/red-flag-rush/` within a minute or two.

Same flow you used for Paste or Pass — public repo works fine since there's no backend or private data involved here (the game keeps score locally in the browser only).
