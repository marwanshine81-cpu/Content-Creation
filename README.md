# Marwan Mohamed Ahmed — CV Website

A single-page interactive CV/portfolio site.

## Files
- `index.html` — the entire site (HTML, CSS, and JS in one file)

## How to publish with GitHub Pages
1. Create a new repository on GitHub (e.g. `marwan-cv`).
2. Upload `index.html` to the repo (drag-and-drop on the GitHub web UI works fine, or use git commands below).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a live URL like `https://<your-username>.github.io/marwan-cv/` within a minute or two.

## Using git from the command line
```bash
cd cv-site
git init
git add .
git commit -m "Initial CV site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then enable Pages as described above.

## Notes
- The "edit" panel (pencil icon) lets you set a passphrase, update your photo, phone, and email, and upload evidence documents. These are saved in the browser's `localStorage`, so they persist for you on that browser/device only — they won't sync across different visitors or devices. If you want the edits to be visible to anyone who visits the site, you'd need a small backend or a service like Firebase to store that data instead.
- The "Download PDF" button uses the browser's print dialog (`window.print()`) — no extra setup needed.
