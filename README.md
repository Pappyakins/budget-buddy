# Budget Buddy (standalone)

A single-file, dependency-free budgeting web app with biweekly or monthly pay periods. Open `index.html` in any
modern browser — or host it anywhere static (GitHub Pages, Netlify, etc.).

## Features

- **Pay periods, your way** — biweekly or monthly; set pay amount + pay date and
  periods generate automatically. Browse current and past periods, each with its own ledger.
- **Income & expense tracking** — quick-add with amount, category, note, date;
  entries are editable and deletable. Paycheque auto-added each period.
- **Category budgets** — per-period limits with progress bars and over/near-limit warnings.
- **Dashboard** — income vs spent vs remaining, savings rate, spending-by-category
  donut chart (inline SVG), income-vs-spending trend across the last 6 periods.
- **Money Coach** — rule-based advice from your real numbers: 50/30/20 analysis,
  savings-rate feedback, top spending drivers, budget alerts, emergency-fund
  guidance, saving streaks. Includes a "not professional financial advice" disclaimer.
- **Savings goals** — targets with add/withdraw flows that post to your ledger.
- **Recurring bills** — defined once, suggested one-tap each period until added.
- **CSV export** of all transactions.
- **Currency setting** (default CAD; USD/GBP/EUR/NGN supported).
- **Onboarding** — friendly 2-step setup on first run.
- **Privacy** — everything stored in the browser's `localStorage`; no server, no tracking.

## Notes

- No build step, no external requests — works offline from `file://`.
- To reset, use More → Danger zone → Reset all data (or clear site storage).
