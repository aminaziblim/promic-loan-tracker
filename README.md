# SusuTrack PWA — Monthly Susu Collection

A mobile-friendly Progressive Web App starter for a susu company.

## Features
- Register and edit customers, phone numbers, locations and monthly targets
- Record monthly contributions and withdrawals in Ghana cedis (GH₵)
- Customer balances and printable customer statements
- Monthly reports and contribution target progress
- Search and filter transactions
- Export transaction records as CSV
- Download and restore a JSON backup
- PWA manifest and service worker for installability and offline app shell

## Run locally
PWAs generally require `localhost` or HTTPS; opening `index.html` directly as a `file://` URL will not enable service-worker installation.

### Simple local server with Python
1. Extract this ZIP.
2. Open a terminal in the extracted folder.
3. Run: `python -m http.server 8000`
4. Open `http://localhost:8000` in Chrome or Edge.

To install, use the browser's Install app option when available, or the browser menu's **Install app / Add to Home Screen**.

## Important limitations
- This is a prototype. Data is stored in local browser storage on one device and does not automatically sync across staff devices.
- It does not implement secure login, role permissions, server-side audit logs, encrypted backups, or cloud storage.
- For real customer funds, deploy with HTTPS, a secure shared database, authentication and role-based access, immutable transaction logs, validated backups, and proper security testing before production use.
- Always verify transactions and reconcile cash before making financial decisions.
