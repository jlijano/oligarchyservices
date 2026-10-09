# Oligarchy Services — GitHub Pages fallback

This public repository contains a **static, independent fallback landing page** for Oligarchy Services.

- Primary site: https://oligarchyservices.com
- Intended fallback: https://jlijano.github.io/oligarchyservices/
- Source: `index.html`; publication workflow: `.github/workflows/pages.yml`.

## Enable the fallback
In **Settings → Pages**, set **Build and deployment → Source: GitHub Actions**. The workflow deploys on commits to `main`. Confirm the public URL after the workflow succeeds.

This is **not** a full mirror of the private/sandbox site: PHP, login, customer data, forms, and administration features are not supported by GitHub Pages. Avoid committing credentials or sensitive website data. Keep Hostinger DNS pointed at the primary hosting system; the github.io fallback remains independently available. Domain failover is not automatic.

## Maintenance
Update `index.html` as public site messaging changes. Check the Pages Actions workflow and confirm the fallback URL periodically.
