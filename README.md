# Card Coach

A single self-contained HTML file — no build step, no dependencies to install.

## Put it on GitHub Pages

1. Create a new repo on GitHub (e.g. `card-coach`).
2. Add **`index.html`** (included here) to the root of the repo. That filename matters — GitHub Pages serves `index.html` as the site's home page.
3. Commit and push it to the `main` branch.
4. In the repo, go to **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**.
6. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
7. Wait a minute or two, then refresh the Pages settings page — it will show your live URL, typically:
   `https://<your-username>.github.io/<repo-name>/`

That's it. Any time you push a new `index.html` to `main`, the live site updates automatically (usually within a minute).

## Quick alternative (no GitHub account setup needed)

Drag `index.html` onto [netlify.com/drop](https://app.netlify.com/drop) for an instant public link — useful if you just want to test sharing it before setting up GitHub Pages.

## Files in this folder

- `index.html` — the app (same content as `card-coach.html`, just renamed to the filename GitHub Pages expects).
- `card-coach.html` — identical copy, in case you want to host it under a different filename or path.
