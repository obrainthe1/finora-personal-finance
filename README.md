# Finora Personal Finance

A lightweight React + Vite personal finance tracker with Zambian Kwacha (ZMW) formatting, local browser storage, JSON backup/restore, and a basic installable PWA/offline shell.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

Deploy the generated `dist/` directory to Netlify or another static host.

## Offline and data notes

- Transactions are saved in this browser's localStorage; clearing browser data can delete them.
- Export a JSON backup regularly and keep it somewhere safe.
- The service worker caches the same-origin app shell after the first online visit. Test offline behavior on the deployed HTTPS site.
- This is a local-only starter: it does not sync between devices and does not connect to bank accounts.
- The SVG icon in `public/icon.svg` is a placeholder brand icon. Replace it with your supplied original artwork if you want an exact match.

## Current scope

This repository starts with income/expense entry, category/date/note fields, filtering, deletion, summaries, and backup/restore. Budgets, multiple accounts, debt/net-worth tools, PDF exports, and the previously discussed full Finora package are not included in this starter yet.
