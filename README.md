# House

[![Deploy site](https://github.com/nhall/house/actions/workflows/deploy.yml/badge.svg)](https://github.com/nhall/house/actions/workflows/deploy.yml)

A bug tracker for my house — open issues are things that need fixing, closed issues are things that got fixed.

**[View the dashboard →](https://nhall.github.io/house/)**

## What's in here

- **Issues** — the actual bug list. Labels cover location (Exterior, Basement, Utility Room, etc.) and type (Plumbing, HVAC, Electrical, Cosmetic, Structural, Landscaping).
- **[Paint colors](documents/paint-colors.md)** — interior Behr and exterior Benjamin Moore palette.
- **Manuals** — HVAC system documentation.
- **Site** — an Astro dashboard that reads the issues from the GitHub API at build time and renders stats, open items, and recent fixes.

## Site

The dashboard lives in `site/` and deploys to GitHub Pages via GitHub Actions on every push to `master`. It also rebuilds nightly at 8am UTC to pick up any issue activity.
