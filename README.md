# WealthPath

WealthPath is a self-contained, browser-based portfolio dashboard for tracking personal investments and reviewing a simple summary of the user’s current financial position.

Open `index.html` directly in a browser — no server, no npm, and no build step are required.

## How it works
- Start on the Overview page and enter your name and age.
- Click `Track Investments` to go to the Investments page and add holdings such as property, shares, crypto, gold, gold bonds, bonds, term deposits, or cash.
- Use the sidebar to import your data from JSON at any time.
- Export is available from the Summary page after you have added investments and income.
- View the Summary page to review your current allocation and see suggested rebalancing based on your selected risk profile.

## Features
- Simple Overview flow with name, age, and investment entry
- Investment tracking for 8 asset types, including new bond support
- Property form with auto-calculated EMI and annual tax rebate support
- Investment forms now support cash flow inputs for non-property holdings
- Summary page with:
  - current portfolio allocation
  - recommended allocation based on age and selected risk profile
  - rebalanced asset guidance
  - key insights and portfolio summary
- Desired Risk Profile options: Conservative, Balanced, Growth, High Growth
- LocalStorage persistence for saved data
- JSON import from the sidebar and JSON export from the Summary page
- Responsive layout with desktop sidebar and mobile hamburger menu
- Inline CSS and JavaScript for easy hosting on GitHub Pages or opening directly from disk

## GitHub Pages
1. Push this repo to GitHub.
2. Open your repository Settings → Pages.
3. Set Branch to `main` and Folder to `/ (root)`.
4. Save and wait for GitHub to publish the site.

## Disclaimer
This app provides general financial insights only and does not constitute personal financial advice. Users should seek guidance from a qualified and licensed financial adviser or certified wealth planner before making financial decisions.
