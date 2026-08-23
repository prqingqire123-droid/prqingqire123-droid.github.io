# Avincfix site

Static catalog for [Avincfix](https://play.google.com/store/apps/dev?id=7881961170768410776) on Google Play. Open `index.html` in a browser, or host it on GitHub Pages.

## Files

- `index.html` — page
- `styles.css` — layout and theme
- `share/posts.md` — short social copy

No build step. Tiny filter script lives at the bottom of `index.html`.

## Host on GitHub Pages (`avincfix.github.io`)

1. Sign in to GitHub as **Avincfix** (or an account that can create a repo under that user).
2. Create a **public** repository named exactly `avincfix.github.io` (User Pages require that name).
3. Upload these files to the **root** of the default branch (`main` or `master`):
   - `index.html`
   - `styles.css`
   - optionally `README.md` and the `share/` folder
4. In the repo: **Settings → Pages**. Source: **Deploy from a branch**. Branch: `main` (or `master`), folder: `/ (root)`. Save.
5. Wait a minute, then open `https://avincfix.github.io/`.

### Command-line option

```bash
git clone https://github.com/Avincfix/avincfix.github.io.git
cd avincfix.github.io
# copy index.html, styles.css (and share/ if you want) into this folder
git add index.html styles.css
git commit -m "Add Avincfix catalog site"
git push
```

Then enable Pages as in step 4 if it is not already on.

Custom domain is optional: add a `CNAME` file with your domain and point DNS as GitHub documents.

## Links

- Play developer: https://play.google.com/store/apps/dev?id=7881961170768410776
- GitHub: https://github.com/Avincfix
