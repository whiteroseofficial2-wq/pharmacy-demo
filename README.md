# WhiteRose PharmaOS — Smart Pharmacy Management (Interactive Demo)

Static, browser-only demo of a pharmacy management system for Indian medical stores. **Sample data only — not for real pharmacy operations.**

## Features
Dashboard (KPIs, charts, alerts), POS with FEFO batch selection and printable invoice, inventory (search, filter, sort, pagination, add/adjust/delete, CSV export), batch & expiry (30/60/90-day filters, write-offs), purchases (stock added only on receipt), suppliers and payments, customers, prescriptions (demo records), sales history, returns with linked records, reports with date range and CSV, staff/role matrix (UI simulation), activity log, settings, JSON backup/restore/reset.

## Technologies
HTML5, CSS3, vanilla JavaScript, Chart.js (CDN, with fallback), localStorage. No backend, build step or API keys.

## Test locally
Open `index.html` in a browser (or run `python -m http.server` in this folder).

## Deploy to GitHub Pages
1. Create a new public repository on GitHub.
2. Upload `index.html`, `README.md` and `.nojekyll` to the repository root.
3. Go to Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. After a minute your demo is live at `https://USERNAME.github.io/REPOSITORY/`

## Limitations
- localStorage is not a secure database; data is specific to each browser and device.
- GitHub Pages has no backend, authentication, multi-user data or server-side access control; roles are a UI simulation.
- Invoices are demo documents, not legally compliant GST invoices. Profit figures are estimates.
- Not suitable for real dispensing or accounting. Dispensing must follow applicable Indian laws.

## Reset the demo
Settings → Reset demo data (or clear this site's localStorage).
