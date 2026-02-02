# Lawn Care Website

This repository contains the website and supporting infrastructure for a small, local lawn care business.

The site is intentionally simple: a static frontend for credibility and discoverability, plus a minimal backend endpoint to handle contact form submissions securely.

This is a working business asset, not a reusable library or demo project.

---

## Tech Stack

- Static frontend: HTML, CSS, minimal JavaScript
- Hosting: Azure Static Web Apps
- Backend: Azure Functions (contact form API)
- Infrastructure: Bicep
- CI/CD: GitHub Actions

---

## Structure

src/web/ - Static website (HTML/CSS/JS)
src/api/ - Azure Functions backend
infra/ - Bicep infrastructure definitions


---

## Local Development

### Frontend
Open files in `src/web/` directly in a browser, or serve with any static file server.

### Backend (API)
Requires Azure Functions Core Tools.

Environment variables for email delivery are defined via application settings and are not committed to the repo.

---

## Deployment

The site is deployed via GitHub Actions to Azure Static Web Apps.

`main` represents the currently deployed version.  
Active development occurs on `dev` and is squash-merged into `main`.

---

## Notes

This project favors simplicity, reliability, and low operational overhead over framework complexity.


