# Alun Future Studio

Static landing page for https://futurestudio.com.br, hosted on GitHub Pages.

Plain HTML and CSS; no JavaScript, build, package manager, or external runtime dependencies. The logo and favicon preserve the existing Future Studio brand assets. The Space Grotesk font is self-hosted under its SIL Open Font License (see assets/OFL.txt).

## Development

Run `python3 -m http.server 8765` in this directory, then open http://localhost:8765.

## Deployment

GitHub Pages publishes the root of the `main` branch. Changes go live after pushing to `main`.

Custom domain: `futurestudio.com.br`. `www.futurestudio.com.br` redirects to the apex through GitHub Pages. DNS is managed in Cloudflare.

The former Lovable site is preserved during migration for rollback. The separate leads/trial project is not part of this repository.
