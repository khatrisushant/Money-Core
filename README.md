# Money Core

A robotic personal finance dashboard built with HTML, CSS and JavaScript.

## Run in VS Code

1. Extract the ZIP.
2. In VS Code, choose File > Open Folder and select the money-core folder containing index.html.
3. Open index.html in a browser, or use VS Code's Live Server extension.
4. Click Set starting balance, then add transactions.

No npm install or build is required. Fonts load from Google Fonts; the app still works with fallback fonts when offline.

## Files

- index.html: page structure
- style.css: styling and responsive layout
- script.js: transactions, budgets, charts and browser storage
- favicon.svg: browser icon

## Push to GitHub

Create an empty GitHub repository. Open a terminal in this folder and run:

```sh
git init
git add .
git commit -m "Add Money Core dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

Replace YOUR_USERNAME and YOUR_REPOSITORY with your own values. If using an existing repository, copy these files into its folder and commit/push using that repository's normal workflow. Do not run git init or add a new origin there.

## GitHub Pages

Keep index.html, style.css, script.js and favicon.svg in the repository root. In GitHub, open Settings > Pages. Choose Deploy from a branch, select main and / (root), then Save. GitHub will show the website URL once publication completes.

## Storage

Money amounts are calculated in integer cents. All financial data is saved in this browser on this device using localStorage. Each visitor has separate data. Data does not sync between devices or between the original hosted site and a GitHub Pages copy. Export JSON from Settings on the old site and import it on the new site to transfer your records. Browser data clearing can remove your records; keep backups. No account or backend is required.

## Features

- Starting balance, income, and expenses
- Tuition, car, miscellaneous, and custom categories
- Edit, delete, search, type/category/date filters
- Spending breakdown, balance timeline, monthly cash flow
- Monthly budgets and threshold warnings
- Full JSON export/import and CSV export
- Responsive desktop and mobile layout
