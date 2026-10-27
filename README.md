# Portfolio site

A static site: `index.html` plus `img/`, `docs/` and `code/`. It doesn't need a build step.

## Publish it (pick one)

**Netlify Drop (fastest, about 2 min):** go to https://app.netlify.com/drop, sign in, and drag this whole
`portfolio-site` folder onto the page. You get a URL like `something.netlify.app`, which you can rename in the site settings.

**GitHub Pages (free, gives you `<username>.github.io`):**
1. Create a public repo named `<your-username>.github.io` on github.com.
2. Upload the contents of this folder (Add file → Upload files), or push it with git / GitHub Desktop.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.

Either one can use a custom domain later (for example `jorgeurruela.com`).

## Preview locally

    python -m http.server 8765

Then open http://localhost:8765.
