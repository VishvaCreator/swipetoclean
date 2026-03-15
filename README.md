# Swipe to Delete — Website (GitHub Pages)

This folder contains the static website for **Privacy Policy**, **Terms of Use**, and **Contact**, suitable for GitHub Pages.

## Deploy to GitHub Pages

1. **Push this repo** (including the `docs/` folder) to GitHub.

2. **Enable GitHub Pages**
   - Open your repo on GitHub → **Settings** → **Pages**.
   - Under **Build and deployment** → **Source**, choose **Deploy from a branch**.
   - **Branch**: `main` (or your default branch).
   - **Folder**: `/docs`.
   - Click **Save**.

3. **Wait a minute or two.** Your site will be live at:
   - `https://<username>.github.io/<repo-name>/`

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
