# Bambu Lab A1 Savings Tracker

A real-time collaborative web application designed to track shared progress toward purchasing a Bambu Lab A1 3D printer. Powered by GitHub Pages and Google Firebase.

---

## Features

- Real-Time Synchronization: Instant live data reflection across devices powered by Google Cloud Firestore listeners.
- Google Authentication: Separate user logins via Firebase Auth with automated profile name and photo resolution.
- Dynamic Progress Tracking: Visual progress indicator recalculating remaining balance and completion percentages toward the $399.00 target.
- Individual Contribution Breakdown: Automatic aggregation calculating exact dollar amounts and percentage share contributed per user.
- Quick Presets: Rapid deposit triggers ($5, $10, $20, $50) alongside manual custom value inputs.
- Audit History Feed: Chronological timestamped event ledger detailing recent contributions.
- Confetti Celebration: Dynamic particle trigger upon full completion of the financial target.

---

## Tech Stack

- Frontend: HTML5, CSS3 (Modern Dark Theme, Flexbox/Grid), Vanilla JavaScript (ES Modules)
- Hosting: GitHub Pages
- Backend & Database: Google Cloud Firestore (v10 modular SDK)
- Identity Management: Firebase Authentication (Google OAuth Provider)
- External Libraries: Canvas-Confetti (CDN)

---

## Project Structure

```text
├── index.html       # Application entry point (Markup, UI styles, Firebase client logic)
└── README.md        # Project documentation
