# Business Expense Tracker

A clean, Apple-style expense tracker for business costs. It runs entirely in your browser as a single file.

## Features

**Dashboard**
- Year total, this month (with change vs last month), monthly average and upcoming scheduled costs
- Monthly totals chart for the year. Tap a month to see its expenses.
- Totals by category with share of spend. Tap a category to see its expenses.
- Category-by-month table with row and column totals

**Add**
- **Attach a PDF** invoice or receipt: the app reads it and fills in the amount, date, payee, and (when it can tell) the category and payment method. The PDF stays attached to the expense and can be viewed anytime. Scanned PDFs without text attach fine but need the details typed in.
- Record amount, category, date, who you paid and how you paid, plus an optional note
- Any date works: past months, this month or future months
- **Repeat monthly** creates a series of monthly entries (rent, subscriptions, payroll). Pick a past start date to backfill or a future one to schedule ahead.
- Remembers payees and fills in the usual category and payment method
- Add your own categories

**Expenses**
- Grouped by month with monthly subtotals
- Filter by month and category, search by payee or note
- Tap any expense to edit or delete it (including the rest of a monthly series)
- Export to CSV, download a backup, restore from a backup

## Running it

Open `index.html` in any browser. No install or build step needed.

To use it from your phone or any computer, turn on **GitHub Pages**: Settings → Pages → Deploy from a branch → `main` / root. On iPhone, open the site in Safari and use Share → Add to Home Screen for an app-like icon.

## Your data

Expenses are saved in the browser's local storage, and attached PDFs in the browser's IndexedDB, on the device you use. They don't sync between devices automatically. Use **Back up all data** regularly (backups from the site include attached PDFs), and **Restore from backup** to move data to another device.
