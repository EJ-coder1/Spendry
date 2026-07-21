# Spendry

**Spendry** is a mobile-first, offline-friendly personal finance PWA for tracking income, expenses, budgets, and savings with a clean, fast interface built for everyday use.

## Why Spendry

Spendry is designed to make money tracking feel simple instead of heavy. It focuses on the essentials:

- Track income and expenses quickly
- Organize spending by categories and budgets
- Work offline with local storage
- Support multiple currencies and languages
- Offer a premium upgrade flow for Pro features

## Key Features

- **Offline-first PWA** — usable without a constant internet connection
- **Fast mobile UI** — optimized for small screens and low-end Android devices
- **Income / expense tracking** — capture transactions in seconds
- **Budgets and summaries** — see where money goes at a glance
- **Multi-currency support** — display and track values in different currencies
- **Multi-language support** — built for a global audience
- **Custom themes** — personalize the app experience
- **Pro / unlock flow** — supports upgrade and code-based activation
- **Local storage** — no account required for basic offline use

## Built With

- Vanilla HTML
- Vanilla CSS
- Vanilla JavaScript
- localStorage
- PWA-friendly architecture

## Getting Started

### Run locally

Open `index.html` in a browser.

For the best experience, serve the project through a local web server so PWA features work correctly.

Example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### Install on Android

1. Open the app in Chrome or another PWA-compatible browser
2. Tap **Install** or **Add to Home screen**
3. Launch it like a normal app

## How Spendry Stores Data

Spendry is designed around client-side storage for offline usage.

- Transactions and settings are stored locally
- App state is saved in the browser
- No sign-in is required for core use
- Clearing browser data will remove local app data

## Pro / Unlock Flow

Some features may be gated behind a Pro upgrade flow.

Current purchase and unlock steps are handled through the app's own upgrade process. If payment verification is required, follow the instructions shown in the app before expecting access to unlock-only features.

## Privacy

Spendry is built to minimize friction and keep basic usage local to the device.

- No account is required for basic use
- Data stays on the device unless the user chooses to contact support or complete an upgrade flow
- Users should understand that browser storage is not a backup system

## Supported Platforms

Spendry works best on:

- Android phones
- Mobile browsers
- PWA standalone mode
- Modern desktop browsers

## Project Structure

A typical project setup includes:

```text
index.html
manifest.json
sw.js
icons/
LICENSE
README.md
```

## Notes

- Spendry is optimized for mobile-first use.
- Because it is a web app, browser developer tools can still inspect client-side code.
- Sensitive validation should never rely only on client-side checks.
- Keep backups of important financial data if you use the app heavily.

## Roadmap

Possible next improvements:

- Better onboarding
- Stronger backup and restore flow
- More detailed analytics
- Improved subscription verification
- Better error handling for offline and low-memory devices

## License

See the `LICENSE` file for the project license.

## Support

For questions, bug reports, or unlock help, use the contact method shown inside the app.

---

Built for people who want a fast, calm way to track money.
