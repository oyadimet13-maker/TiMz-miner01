# TIMZ Viral — starter project

A mobile-friendly, installable web app prototype for organizing task notes, keeping an offline queue, and recording a manually verified coin balance.

## Included
- Responsive Android-friendly interface
- Local task queue and task history
- Local coin tracker
- Online/offline status
- Service-worker caching for offline reopening after the first successful load
- Local browser storage; no TikTok password collection

## Important limitation
This project intentionally does **not** automate TikTok likes, log into TikViral, or claim coins automatically. Automated engagement may violate platform rules, and no official TikViral integration has been configured. Add only an integration that TikViral explicitly permits and documents.

## Run locally
Requires Node.js 18+.

```bash
npm install
npm run dev
```

Open the local URL shown by Vite. For a production build:

```bash
npm run build
npm run preview
```

## Install on Android
Host the production build over HTTPS, open the site in Chrome on Android, then use the browser menu and choose **Add to Home screen** or **Install app** (wording varies).

## Data
Tasks and the recorded coin total are stored in this browser on this device. Clearing browser site data removes them. This starter has no cloud sync or account system.
