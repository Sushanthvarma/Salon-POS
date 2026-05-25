# Salon POS — Live Demo by **Plate Pixel**

A production-grade Point of Sale + ERP for salons & spas, built as a portfolio
piece by **[Plate Pixel](https://www.instagram.com/platepixelstudio/)**.

> **Live demo:** https://sushanthvarma.github.io/Salon-POS/
> Anyone can sign up with email + password and explore the full admin panel.

---

## What this demo shows

A complete, installable Progressive Web App that runs on phone, tablet and desktop:

- **Billing & Receipts** — multi-service cart, GST, discounts, split-staff
  attribution, UPI / cash / card payment methods, printable & PDF receipts.
- **Staff Counter** — fast attendance check-in, daily footfall, today's
  transactions.
- **Admin ERP** — month dashboards (revenue, expenses, P&L, footfall),
  service & price catalog, staff & salary management, fixed expenses, EMI
  tracking, CapEx, expense logging by category.
- **Appointments** — calendar booking with reminders.
- **Reports & Exports** — CSV + PDF exports for dashboard, sales, expenses,
  payroll, advances, analytics.
- **Role-based access** — Admin / Supervisor / Staff permission tiers
  (currently disabled in demo mode so visitors get full access).
- **Offline-first** — Firestore IndexedDB persistence + a shadow queue so the
  app keeps working without network and re-syncs on reconnect.
- **Installable** — add to home screen on iOS / Android / desktop Chrome and
  it runs like a native app (PWA + service worker).

---

## Tech stack

| Layer            | Choice                                              |
| ---------------- | --------------------------------------------------- |
| Frontend         | Vanilla HTML/CSS/JS, single-file PWA                |
| Auth             | Firebase Authentication (Google + Email/Password)   |
| Database         | Cloud Firestore (real-time, offline persistence)    |
| Hosting          | GitHub Pages                                        |
| Offline / PWA    | Service Worker, IndexedDB cache, Web App Manifest   |
| PDFs             | jsPDF + AutoTable (client-side, no server)          |

No backend server. No build step. Open `index.html` and it runs.

---

## Try it in 30 seconds

1. Open **https://sushanthvarma.github.io/Salon-POS/**
2. Tap **Try the Demo** → enter any email + a 6-char password → **Create Account**.
3. You land on the Salon dashboard with full admin rights. Bill a service,
   add an expense, open the admin panel, run a P&L report.
4. (Optional) On Chrome desktop / Android, tap the install icon in the URL
   bar — it runs offline like a native app.

> Demo mode shares one Firestore project across all visitors so you can see
> multi-user real-time sync in action. For a private deployment, set
> `DEMO_MODE = false` in `index.html` and add your own Firebase config.

---

## About Plate Pixel

**Plate Pixel** builds custom web & mobile software for small businesses —
POS systems, ERPs, customer portals, dashboards. This Salon POS is one of
several portfolio pieces showcasing what we can ship end-to-end.

**Follow / DM us on Instagram — [@platepixelstudio](https://www.instagram.com/platepixelstudio/)**  
Founder: Sumanth · [sumanth.g1111@gmail.com](mailto:sumanth.g1111@gmail.com)

---

## License

This repository is published as a portfolio demonstration. Code shown for
evaluation — please contact Plate Pixel before reuse in commercial projects.
