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

## Agent conversation vocabulary

Agents working in this repository use the shared private conversation vocabulary defined in
the maintainer's canonical agent instructions for every reply, including chat prose, visible
reasoning, status lines, and task or session titles. Read those instructions and apply them
in full. They are deliberately not restated here, because this file is part of this
repository's public record.

That vocabulary never appears in anything published. Keep it out of commit messages, branch
names, code, code comments, test names, documentation, this file, issues, pull requests,
discussions, release notes, published sites, logs, and every other file in this repository.
Published writing uses ordinary professional English, and exact technical identifiers always
keep their literal spelling. The single documented public-safe exception is named in those
canonical instructions; do not infer any other.

Scan any text bound for a public surface against that vocabulary before publishing it. A
reviewer cannot tell a correct release note from a leaking one by reading it, so the scan is
a step, not a habit.
