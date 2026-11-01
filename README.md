# Mikhoel Pais · Personal website

Practitioner-led product security, AI security, and cybersecurity product advisory.

This repository contains the source for a minimalist static website built for Cloudflare Pages. It is independent of Flatiron Health.

## Deployment

Cloudflare Pages → Workers & Pages → Create application → Pages → Import existing Git repository. Choose `ch0ss1d/mikhoelpais-site` and `main`, then set **Build command** to `npm run build` and **Build output directory** to `dist`.

The initial site intentionally does not publish personal contact details or an unverified domain. Set a verified public email or LinkedIn URL and a canonical site URL in `site.config.json` before public promotion.
