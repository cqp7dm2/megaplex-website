# Megaplex minimal single-page website

This package is a static website prepared for GitHub Pages. It does not require
Node.js, Bootstrap, a database, or a build step.

The design uses one full-screen hero image with subtle loading, background drift
and status animations. It stays within one screen and does not scroll.

## Upload to GitHub

1. Create a new public GitHub repository.
2. Upload everything inside this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

The included `CNAME` file is already set to `megaplex.it.com`. After GitHub
Pages is active, configure the domain's DNS records using the values shown by
GitHub Pages.

## Files

- `index.html` — complete one-screen website and all styling
- `assets/megaplex-hero.png` — hero artwork
- `assets/og.png` — social sharing artwork
- `CNAME` — custom-domain setting for GitHub Pages
