# WealthPath IRR Dashboard

WealthPath is a self-contained personal finance dashboard for tracking investments, estimating internal rate of return (IRR), and reviewing long-term wealth planning outcomes in the browser.

## Overview

This project is a single-file web app that helps you:

- Track investments across property, shares, ETFs, crypto, gold, bonds, term deposits, and cash
- Estimate IRR from purchase price, current value, fees, distributions, and holding period
- Review income, expenses, superannuation, and retirement planning inputs in one place
- Compare portfolio performance against benchmark-style assumptions
- Import and export profile data as JSON for backup, restore, or migration

## Project structure

- [index.html](index.html) — the complete app UI, styles, logic, and embedded dashboard features
- [README.md](README.md) — usage and deployment notes

## Run locally

Because the app is fully static, you do not need a build step or backend server.

1. Open [index.html](index.html) in a browser.
2. Choose **New User** to create a fresh profile, or **Existing User** to restore saved JSON data.
3. Add your investments, income, expenses, and retirement-related inputs.
4. Use the dashboard pages to review portfolio summaries, projections, and wealth planning outcomes.

## Key features

- Portfolio tracking for multiple asset classes
- IRR estimation based on capital movement and distributions
- Goal and household planning views
- Sensitivity analysis panel for scenario testing
- Local browser persistence using `localStorage`
- JSON import/export for data portability

## Deployment

### GitHub Pages

To publish the app on GitHub Pages:

1. Push the repository to GitHub.
2. Open the repository's **Settings** page.
3. Go to **Pages**.
4. Set the source branch to the branch containing the app.
5. Use the root folder (`/`) as the publish directory.
6. Save the configuration and wait for the site to publish.

Then open the Pages URL provided by GitHub.

> Make sure [index.html](index.html) is present at the repository root before publishing.

## Data and privacy

- The app stores data locally in the browser.
- No server-side database or API is required.
- Exported data remains on your device unless you choose to share it manually.

## Notes

- This project is intentionally lightweight and portable.
- It is best suited for personal finance tracking and scenario exploration rather than multi-user production hosting.
- If you want to modify the dashboard behavior or visuals, update the logic and styles directly in [index.html](index.html).
