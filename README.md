# Nouman's App

Offline first personal finance and property ledger for iPhone.

## Deployment
The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the site to GitHub Pages whenever the main branch changes.

If Pages is not enabled, open **Settings → Pages** in this repository and choose **GitHub Actions** under **Build and deployment**. The site address will then be:

`https://alisaddamai.github.io/noumans-app/`

## Install on iPhone
1. Open the published link in Safari.
2. Tap Share, then Add to Home Screen.
3. Enable Open as Web App and tap Add.

## Privacy and backups
Transactions, property records and attached files are stored in IndexedDB on the current device. The app does not send them to a server. Export a backup regularly and restore it on a new device. Safari website data can be removed by iOS or by the user, so local storage is not a substitute for backups.

## PDF
Use Print / PDF and choose the system print or Save as PDF option available on the device.

Developed by Humam and Co.
