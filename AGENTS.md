# BambuHui Agent Instructions

This repo contains the BambuHui project — a Material Design 3 interface and documentation site.

## Structure

- `design/` — complete design contract (app, site, tokens, components, fonts, assets)
- `design/design-source/` — read-only original design reference; do not edit
- `design/desktop/` — legacy Electron shell (reference only)

## Build locally

```powershell
node design/scripts/compose-site.mjs _site
```

## Deploy

`.github/workflows/deploy.yml` publishes to GitHub Pages on every push to `main`.

## Rules

- Do not edit `design/design-source/`
- Every commit ends with `Co-Authored-By: Claude Fable 5 <noreply@anthropic.com>`
