# MYBGA website

The live site for MYBGA (Making Your Business Great Again), Sydney.

## What's here
- `index.html` is the main website.
- `samples/` holds the sample sites shown in the Work section. They are marked `noindex` so search engines don't list the made-up businesses.
- `favicon.png`, `apple-touch-icon.png` and `og.jpg` are the tab icon, phone home-screen icon and link-preview image.

## Publishing
The site is hosted on Netlify (https://mybga-site.netlify.app), connected to this repo. Every push to `main` deploys automatically.
Any change pushed to `main` goes live within a minute or two.

## Before launch
- Paste the Formspree form address into `FORM_ENDPOINT` near the bottom of `index.html`.
- When the domain is ready, update the `og:image` and `og:url` addresses in `index.html` and add a `CNAME` file containing the domain.
