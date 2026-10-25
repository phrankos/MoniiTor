# MoniiTor Project Brief

## Problem
Current spreadsheet-based personal expense tracking is tedious to maintain and not conducive on mobile. There is a need to remember expenses while on the go and log them when a desktop is accessible instead of being available anytime. Additionaly, there is a need for storing financial data locally instead of storing in the cloud.

## Target user
- Primary: Me.
- Secondary: Privacy-conscious individuals who want alternatives to similar apps that store financial data in the cloud.

## Goals
- PWA: Installable on phone home screen, launched standalone.
- Local-storage: All the user's financial data is only stored locally.
- Works offline: App shell and core functionality work with no network connection.

## Non-goals
- No bank account linking
- No multi-user accounts
- No cloud backend
- No native app stores (PWA install only)

## MVP scope
- CRUD for accounts (Fund Sources)
- CRUD for transactions
- CRUD for categories
- Summary view (Dashboard with account balances)
- Offline persistence across refreshes and restarts.

## Backlog
- Encrypted export/import
- Device-to-device sync (Perhaps QR handshake + WebRTC, or relay that sees only ciphertext)
- Charts/Graphs and trends views

## Constraints
- Zero budget
- Solo developer
- Free hosting only (Vercel, Netlify, or GitHub Pages).

## Success criteria
1. Add an expense while offline; data persists after closing and reopening the app.
2. Edit and delete an expense; summary updates correctly.
3. App loads and functions with network disabled (airplane mode test passes).
4. Data survives browser refresh and device restart.
5. App is installable on Android Chrome and desktop Chrome (install prompt appears or "Install" appears in browser menu).
