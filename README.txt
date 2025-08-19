# Dragon Rider: Sky of Vows — iPhone (PWA) Instructions

This folder is a **Progressive Web App (PWA)**. Host it anywhere with static hosting, then open the URL in Safari on iPhone and **Add to Home Screen** for a full-screen app experience.

## Quick Deploy Options

### 1) GitHub Pages
1. Create a new repo (public).
2. Upload the contents of this folder.
3. In Settings → Pages → Source: `main` → `/root`.
4. Open the site URL in Safari on iPhone.
5. Share → Add to Home Screen.

### 2) Netlify (drag & drop)
1. Go to netlify.com → Drop your folder to create a new site.
2. Open the site URL in Safari on iPhone.
3. Share → Add to Home Screen.

### 3) Vercel
1. Create a new project from this folder.
2. Open the site URL in Safari.
3. Share → Add to Home Screen.

### 4) Local Wi‑Fi (no accounts)
On your PC/Mac in the folder, run:
- Python 3: `python -m http.server 8000`
- Then on iPhone Safari go to `http://YOUR-COMPUTER-IP:8000`
- Add to Home Screen.

## Notes
- Works offline after first load (via `sw.js`).
- Entire dragon+rider image is embedded; no external files.
- If you update files, bump the `CACHE` version in `sw.js`.