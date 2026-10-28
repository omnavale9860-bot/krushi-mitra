# Krushi Mitra

Krushi Mitra is a static prototype farming assistant with rule-based crop suggestions, a heuristic crop-photo colour check, and an estimated harvesting window. Its results are advisory and are not a substitute for local agricultural guidance.

## GitHub Pages deployment

The site is deployed from the `main` branch by the GitHub Actions workflow in `.github/workflows/pages.yml`.

1. In the repository's **Settings → Pages**, set the build and deployment source to **GitHub Actions** if it is not already set.
2. Push changes to `main`, or run the workflow manually from the **Actions** tab.
3. The live site is [https://omnavale9860-bot.github.io/krushi-mitra/](https://omnavale9860-bot.github.io/krushi-mitra/).

The `_headers` file and `vercel.json` are for other static hosting providers; GitHub Pages does not apply those host-specific settings.

## Optional configuration

- Replace `G-XXXXXXXXXX` in `index.html` with a real GA4 Measurement ID to enable analytics. Analytics will not report until this is configured.
- If you use a custom domain, update the canonical URL, Open Graph URL, `robots.txt`, and `sitemap.xml` to match it.
