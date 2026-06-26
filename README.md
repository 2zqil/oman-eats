# 🍴 Oman Eats

A swipe-to-discover restaurant finder for Oman. Browse a deck of restaurants Tinder-style, save the ones you like, and the app ranks your **best choice** based on your taste.

Everything lives in a single `index.html` — no build step, no dependencies.

## Features
- 🃏 Draggable swipe cards (mouse **and** touch) with live "Yum/Nope" stamps
- ⌨️ Keyboard controls: **←** pass · **→** save · **↓ / Z** undo
- 🏷️ Filter by cuisine
- 🏆 Taste model ranks saved spots → crowns your best choice (with sparkle burst)
- 📱 Mobile layout (bottom sheet) + 💻 desktop layout (live sidebar)
- 💾 Saves your picks in the browser (localStorage)
- ✨ Smooth spring animations throughout
- Data lives in the **ORDS** (Oman Restaurant Database System) object — edit the `restaurants` array to add your own.

## Run locally
Just double-click `index.html`.

## Host on GitHub Pages (free)
1. Create a new repository on GitHub (e.g. `oman-eats`).
2. Upload `index.html` (drag it into the repo's "Add file → Upload files", then commit).
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)` → **Save**.
6. Wait ~1 minute. Your site is live at:
   `https://<your-username>.github.io/<repo-name>/`

### Or via command line
```bash
cd "oman eats"
git init
git add index.html
git commit -m "Oman Eats"
git branch -M main
git remote add origin https://github.com/<your-username>/oman-eats.git
git push -u origin main
```
Then enable Pages in Settings → Pages as above.
