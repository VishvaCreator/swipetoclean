# Swipe to Clean — Website (GitHub Pages)

This folder contains the static website for **Privacy Policy**, **Terms of Use**, and **Contact**, suitable for GitHub Pages.

## Deploy to GitHub Pages

1. **Push this repo** (including the `docs/` folder) to GitHub.

2. **Enable GitHub Pages**
   - Open your repo on GitHub → **Settings** → **Pages**.
   - Under **Build and deployment** → **Source**, choose **Deploy from a branch**.
   - **Branch**: `main` (or your default branch).
   - **Folder**: Choose the folder where your site files actually are:
     - **Files in the repo root** (e.g. `index.html` at top level) → choose **"/ (root)"**.
     - **Files inside `docs/`** → choose **"/docs"**.
   - Click **Save**.

3. **Wait 1–2 minutes.** Your site will be at:
   - `https://<username>.github.io/<repo-name>/`
   - Example: `https://vishvacreator.github.io/swipetoclean/`

## Not working? Try this

- **Wrong folder:** If your `index.html`, `privacy.html`, etc. are in the **root** of the repo (like in swipetoclean), you must set **Folder** to **"/ (root)"** in Settings → Pages. If it’s set to `/docs`, the site will be blank or 404.
- **Add `.nojekyll`:** In the same place as your site (root or inside `docs/`), add an empty file named `.nojekyll`. This makes GitHub serve plain HTML without Jekyll. In the root repo view, click **Add file** → **Create new file**, name it `.nojekyll`, then **Commit**.
- **Check the URL:** Use `https://<your-username>.github.io/swipetoclean/` (with the repo name and trailing slash).
- **Wait:** After changing settings, wait 1–2 minutes and refresh.

## Before you go live

- **Contact email:** In `contact.html`, replace `support@example.com` with your real support email.

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
cd docs && python3 -m http.server 8000
```

Then visit: http://localhost:8000

## Pages

| File        | Purpose        |
|------------|----------------|
| `index.html`  | Home with links to all pages |
| `privacy.html`| Privacy Policy |
| `terms.html`  | Terms of Use   |
| `contact.html`| Contact        |
