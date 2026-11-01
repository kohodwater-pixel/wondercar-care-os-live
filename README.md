# WONDER car Care Center OS

Standalone GitHub Pages demonstration for the WONDER car integrated car care center.

## Demo features
- Separate manager and cashier interface previews.
- Cashier checkout requires customer name and phone.
- Scan membership QR with the device camera where supported, or enter the membership code manually.
- Membership packages show remaining visits and expiry; each redemption logs the cashier, branch, and time.
- Manager-only customer database, segments, subscriptions, and CSV exports.
- Sales, expenses, customers, memberships, redemption ledger, and period report exports.
- Service direct-cost entry and estimated profitability reporting.

## Open
Open index.html in a browser or publish the repository root with GitHub Pages. Camera access needs HTTPS and browser permission. QR generation uses a CDN script and falls back to showing the membership code.

## Important
This is a frontend demo. Data is stored in this browser. Role separation and subscription balances are not synchronized securely between devices. Production requires backend authentication, transactional membership redemption, secure storage, backups, and Apple/Google Wallet server integrations.
