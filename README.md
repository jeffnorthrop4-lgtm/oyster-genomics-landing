# Oyster Genomics landing page

Responsive, hero-only landing page for Oyster Genomics.

## Files

- `index.html`: hero, styles, and decorative floating-particle animation.
- `favicon.svg`: site icon.
- `netlify.toml`: publishes the repository root with no build step or dependencies.

## Local preview

From this directory, run `python3 -m http.server 8080`, then open http://localhost:8080.

## Netlify

Use the existing [oyster-genomics-landing Netlify project](https://app.netlify.com/projects/oyster-genomics-landing/overview) for this repository.

- Production site: https://oyster-genomics-landing.netlify.app/
- Production branch: `main`
- Publish directory: `.`
- Build command: none
- Environment variables: none

With the repository linked in Netlify, pushes to `main` publish automatically through continuous deployment. Check the project's Deploys page to confirm each release.

The particle animation respects reduced-motion preferences. Fonts are loaded from Google Fonts, with system fallbacks.
