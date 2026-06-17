# House

[![Deploy site](https://github.com/nhall/house/actions/workflows/deploy.yml/badge.svg)](https://github.com/nhall/house/actions/workflows/deploy.yml)
[![Issues closed](https://img.shields.io/github/issues-closed/nhall/house?color=4ECBA0&label=fixed)](https://github.com/nhall/house/issues?q=is%3Aissue+is%3Aclosed)
[![Issues open](https://img.shields.io/github/issues/nhall/house?color=F4923A&label=open)](https://github.com/nhall/house/issues)
[![Last fix](https://img.shields.io/github/last-commit/nhall/house?label=last+activity)](https://github.com/nhall/house/commits/main)
[![Site](https://img.shields.io/website?url=https%3A%2F%2Fnhall.github.io%2Fhouse%2F&label=dashboard)](https://nhall.github.io/house/)
[![Built with Astro](https://img.shields.io/badge/built%20with-Astro-FF5D01?logo=astro&logoColor=white)](https://astro.build)

A bug tracker for my house — open issues are things that need fixing, closed issues are things that got fixed.
**[View the dashboard →](https://nhall.github.io/house/)**

## What's in here

- **Issues** — the actual bug list. Labels cover location (Exterior, Basement, Utility Room, etc.) and type (Plumbing, HVAC, Electrical, Cosmetic, Structural, Landscaping).
- **[Paint colors](documents/paint-colors.md)** — interior Behr and exterior Benjamin Moore palette.
- **Manuals** — HVAC system documentation.
- **Site** — an Astro dashboard that reads the issues from the GitHub API at build time and renders stats, open items, and recent fixes.

## Site

The dashboard lives in `site/` and deploys to GitHub Pages via GitHub Actions on every push to `main`. It also rebuilds nightly at 8am UTC to pick up any issue activity.

## Dependencies

Dependabot keeps the Astro version current with weekly PRs.
