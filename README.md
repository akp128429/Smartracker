# PhoneGuard Universal

Personal lost-phone recovery assistant. Provides official recovery links and a permission-based **local-only** location snapshot. It cannot locate a lost phone unless tracking was configured beforehand.

## Run
```bash
npm install
npm start
```
Open http://localhost:3000.

## Deploy to Render
Create a Render Blueprint from this repository's `render.yaml`.

**Privacy:** Location snapshots remain in the current browser's localStorage; the server does not collect or sync device coordinates. No Gmail password or OTP is requested. For actual lost devices use Google Find Hub, Apple Find My, and India's CEIR portal.
