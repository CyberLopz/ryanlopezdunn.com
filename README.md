# Ryan Lopez-Dunn Cybersecurity Portfolio

A static cybersecurity portfolio and resume website for Ryan Lopez-Dunn, Security Engineer.

## Files

- `index.html` - Site content, SEO metadata, Open Graph metadata, and page structure.
- `styles.css` - Responsive dark cybersecurity theme with accessible contrast.
- `script.js` - Mobile navigation, sticky header state, current year, and reduced-motion-friendly reveal behavior.
- `assets/og-image.svg` - Lightweight security-themed visual used by the hero panel and Open Graph metadata.

## Local Preview

Because this is plain HTML, CSS, and JavaScript, you can open `index.html` directly in a browser.

For a local server preview, run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deploying With GitHub Pages

This site is served by GitHub Pages, building from the `main` branch.

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Set the branch to `main` and the folder to `/ (root)`.
4. The custom domain `ryanlopezdunn.com` is already configured via the `CNAME` file in this repo.
5. Every push to `main` triggers an automatic rebuild and deploy.

## Customization

- Add certification names to the Certifications section as needed.
- Replace `assets/og-image.svg` with a custom PNG preview image if a social platform requires PNG-only Open Graph images.
