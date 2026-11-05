# MYBGA website

The live site for MYBGA (Making Your Business Great Again), Sydney.

## What's here
- `index.html` is the main website.
- `samples/` holds the sample sites shown in the Work section. They are marked `noindex` so search engines don't list the made-up businesses.
- `favicon.png`, `apple-touch-icon.png` and `og.jpg` are the tab icon, phone home-screen icon and link-preview image.

## Publishing
The site is served by GitHub Pages from the `main` branch (Settings, then Pages, then "Deploy from a branch", `main`, `/ (root)`).
Any change pushed to `main` goes live within a minute or two.

## Before launch
- Paste the Formspree form address into `FORM_ENDPOINT` near the bottom of `index.html`.
- When the domain is ready, update the `og:image` and `og:url` addresses in `index.html` and add a `CNAME` file containing the domain.
