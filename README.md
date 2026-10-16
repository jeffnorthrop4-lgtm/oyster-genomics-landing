# Oyster Genomics landing page

Responsive static landing page based on the public content of oystergenomics.com.

## Files

- `index.html`: page, styles, interactive Switchpoint steps, and mobile navigation.
- `favicon.svg`: site icon.
- `netlify.toml`: publishes the repository root with no build step or dependencies.

## Local preview

From this directory, run `python3 -m http.server 8080`, then open http://localhost:8080.

## Netlify

Import the GitHub repository as a new Netlify project, deploy the `main` branch, and use `.` as the publish directory. No build command or environment variables are needed. Subsequent pushes to `main` publish through Netlify continuous deployment.

Contact links open an email client addressed to hello@oystergenomics.com. Fonts are loaded from Google Fonts, with system fallbacks.
