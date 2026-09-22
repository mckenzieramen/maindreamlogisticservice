# MAINDREAM LOGISTIC SERVICES — Fleet Management Web App

This is a premium web prototype built from the supplied `Trip-Data-for-upgrade (1).xlsx` workbook structure.

## Source-derived calculation mapping
- 10% Cut: `Trip Rate * 10%` (from Trip Data column AC).
- Total Gross: `Trip Rate - 10% Cut - Gas - Upgrades/Maintenance - Cash Bond + Reimburse Expenses + Adds on`.
- Total Expenses: `Driver Rate + Helper 1 Rate + Helper 2 Rate + Gas + Upgrades/Maintenance`.
- Total Net Income: `Trip Rate - Total Expenses - 10% Cut - Cash Bond`.

The workbook contains `#REF!` in some expense formulas. The workbook's `Search & Check` sheet exposes column Z as `Upgrades/Maintenance`, so this prototype uses that field as the missing reference and explicitly documents the mapping in Settings. Verify this mapping against your intended accounting rule before production use.

## Included modules
Dashboard, Trips & Deliveries, Trucks-ready navigation, Drivers/Employees, Salary/Payroll, Expenses, Loans, Maintenance & Documents, Clients, Invoices, Payments Collected, Reports, Settings.

## Deployment
Static HTML/CSS/JS. Can be hosted on Cloudflare Pages, GitHub Pages, Netlify, or similar static hosting.
