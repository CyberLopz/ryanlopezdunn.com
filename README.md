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

## Deploying With Cloudflare Pages

1. Push this folder to a GitHub repository.
2. In Cloudflare, open **Workers & Pages**.
3. Choose **Create application**.
4. Select **Pages**.
5. Connect the GitHub repository.
6. Set the build configuration:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `/`
7. Deploy the site.
8. Add the custom domain `ryanlopezdunn.com` in the Cloudflare Pages domain settings.

## Customization

- Replace the LinkedIn placeholder in `index.html` when the profile URL is ready.
- Add certification names to the Certifications section as needed.
- Replace `assets/og-image.svg` with a custom PNG preview image if a social platform requires PNG-only Open Graph images.
