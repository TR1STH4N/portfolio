# Tr1sth4n — Video Editor Portfolio

A single-page portfolio site with a DaVinci Resolve–style editor mockup, hover effects on every button and box, and light/dark mode.

## Files

```
index.html                 the whole site (HTML + CSS)
assets/preview.gif         animated preview shown in the editor screen
.nojekyll                  tells GitHub Pages to serve files as-is
.github/workflows/pages.yml  auto-deploys the site on every push to main
```

## Launch on GitHub Pages

1. Create a new repository on GitHub (e.g. `tr1sth4n.github.io` or any name).
2. Upload everything in this folder to the repository root (keep the folder structure), or push it with git:
   ```bash
   git init
   git add .
   git commit -m "Launch site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
3. In the repo go to **Settings → Pages**, and under **Build and deployment** set **Source** to **GitHub Actions**.
4. Push (or run the workflow from the **Actions** tab). When it finishes, your site is live at
   `https://<your-username>.github.io/<repo>/`
   (or `https://<your-username>.github.io/` if the repo is named `<your-username>.github.io`).

Prefer no workflow? Delete `.github/` and set **Source** to **Deploy from a branch → main / (root)** instead.

## Customize

- Swap the editor preview by replacing `assets/preview.gif` (16:9 works best).
- Social links and text are in `index.html`.
