# Psych E&M Note Builder

A lightweight, browser-based tool for structuring psychiatric E&M documentation with suggested CPT coding (99213/99214) and 2026 billing add-ons (+90833, +G2211).

## Features

- **MDM scoring** — 2-of-3 rule (problems, data, risk) mapped to low or moderate complexity
- **Time-based coding** — Optional override when total time is documented
- **Billing add-ons** — +90833 psychotherapy (16–37 min) and +G2211 longitudinal care
- **Template presets** — ADHD, Anxiety, Depression, Anxiety + ADHD
- **Note generation** — Copy-ready output for pasting into the EHR
- **No PHI** — Checkbox-driven; no patient identifiers ever entered or stored
- **Dark/light mode** — Respects system preference, toggle available

## Deployment

This is a single `index.html` file. No build step, no dependencies, no backend.

Hosted via GitHub Pages.

## Disclaimer

This tool is a **prototype** for documentation support only. It does not replace clinical judgment, payer-specific billing rules, or compliance review. Final coding decisions are the responsibility of the billing provider.
