# Beacon Wire — Operations Dashboard

A web dashboard built from the Beacon Wire master Google Sheet (invoicing, bookkeeping and inventory for a small wire products business). Every customer, price, vendor and transaction in it is made up.

**What it shows:** cash collected, expenses, net income, bank balance, open and overdue receivables, inventory weeks of supply with reorder alerts, top customers, and a searchable invoice log. Change the "As of" date and every figure is recalculated as of that date.

**Stack:** static HTML, CSS and JavaScript plus Chart.js. No build step. Deployed on Vercel.

- `index.html`: the app
- `data.json`: demo data exported from the spreadsheet
- `chart.umd.min.js`: Chart.js 4.4.1 (MIT)
