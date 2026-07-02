# Ashtar Infinity — Website

A single-page site for Ashtar Infinity (Web Development, Data Science & AI, Flutter Mobile Apps). Pure HTML/CSS/JS — no build step, no dependencies to install.

## Files
- `index.html` — the whole site
- `assets/mark.png` — the infinity icon (used in the nav + favicon)
- `assets/logo.png` — full logo with wordmark (spare, not currently used on the page)

## Put it live on GitHub Pages for free

1. **Create a new repo** on GitHub, e.g. `ashtar-infinity-website` (public repo, no need to add a README/gitignore).

2. **Push this folder to it.** From inside this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/ashtar-infinity-website.git
   git push -u origin main
   ```

3. **Turn on Pages:**
   - On GitHub, open the repo → **Settings** → **Pages** (left sidebar).
   - Under "Build and deployment" → Source, choose **Deploy from a branch**.
   - Branch: `main`, folder: `/ (root)` → **Save**.

4. Wait ~1 minute, then refresh that Pages settings page — it will show your live URL:
   ```
   https://<your-username>.github.io/ashtar-infinity-website/
   ```

That's it — no server, no build, free hosting. Any time you push a change to `main`, the live site updates automatically in about a minute.

## Editing later
Everything is in `index.html` (structure + styles + a small canvas animation, all inline). Text content — services, team names/roles, LinkedIn links, contact email — is plain HTML, so you can edit it directly on GitHub (pencil icon on the file) without touching any code you don't need to.
# Ashtar-Infinity
