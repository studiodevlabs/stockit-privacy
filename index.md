# Privacy Policy — StockIt

**Last updated:** June 2026

---

## The Short Version

StockIt does not collect, store, transmit, or sell any of your personal data or financial information. Everything stays on your phone. We have no servers. We cannot see your data even if we wanted to.

---

## What Data StockIt Accesses

### Data you enter yourself
- Stock transactions (buy, sell, dividend)
- Holdings, price overrides, portfolio notes
- Fixed deposits, recurring deposits, and interest rates
- Gold holdings (physical, SGB, ETF)
- Mutual fund units and purchase NAV
- Retirement account balances (NPS, EPF, PPF)

All of this data is stored **only on your device**, encrypted using AES-256 with a key stored in the Android Keystore. It never leaves your device unless you explicitly choose to back it up to your own Google Drive account.

### Data fetched automatically
- **Stock prices:** Live prices are fetched from Yahoo Finance's public API. Only the ticker symbol (e.g., "HDFCBANK.NS") is sent — your holdings, quantities, and portfolio value are never transmitted.
- **Mutual Fund NAV:** Fetched from api.mfapi.in (AMFI's public API). Only the scheme code (e.g., "120503") is sent. No personal data is transmitted.
- **CSV import:** Broker CSV files are parsed entirely on your device using JavaScript. Files never leave your phone.

---

## What Data StockIt Does NOT Collect

- ❌ No name, email, phone number, or identity
- ❌ No device identifiers sent to any server
- ❌ No location data
- ❌ No analytics or usage tracking (no Firebase, Mixpanel, or equivalent)
- ❌ No crash reporting that transmits data (no Sentry, Crashlytics, or equivalent)
- ❌ No advertising identifiers
- ❌ No portfolio holdings, quantities, or values on any server
- ❌ StockIt has no servers — there is no backend to store your data on

---

## Google Drive Backup (Optional)

If you connect Google Drive, StockIt uploads a backup file to your own Google Drive account. This is:
- **Opt-in only** — not enabled by default
- **Encrypted** — the backup is encrypted using AES-256 before leaving your device, tied to your Google account
- **Your account, your file** — StockIt cannot read your backup. Only you can decrypt it by signing in with the same Google account
- **Your control** — you can delete the backup from your Drive at any time

StockIt requests two Google API scopes:
- `drive.file` — to create and update the backup file
- `drive.metadata.readonly` — to list your Drive folders so you can choose where to save the backup

StockIt cannot access any other files in your Google Drive.

---

## App Lock & Biometric

If you enable App Lock, StockIt uses Android's built-in biometric or device credential system. No biometric data is stored by StockIt. Authentication is handled entirely by the Android operating system.

---

## Offline Operation

StockIt is designed to work fully offline. All features except live price updates work without an internet connection. Enabling airplane mode and opening the app will demonstrate that no data is transmitted during normal use.

---

## Third-Party Services

| Service | Purpose | Data shared |
|---|---|---|
| Yahoo Finance (query1.finance.yahoo.com) | Live stock prices | Ticker symbols only (e.g., "HDFCBANK.NS") |
| api.mfapi.in | Mutual fund NAV | Scheme codes only (e.g., "120503") |
| Google Drive API | Optional encrypted backup | Encrypted JSON file to your own Drive account |
| Google OAuth | Sign in for Drive backup | Email address (used locally to derive encryption key) |

No analytics, advertising, or crash reporting services are used.

---

## Data Safety (Google Play)

| Data type | Collected | Shared |
|---|---|---|
| Financial info | No | No |
| Personal info | No | No |
| Device identifiers | No | No |
| Usage data | No | No |

---

## Children's Privacy

StockIt is not directed at children under 13. We do not knowingly collect any data from children.

---

## Changes to This Policy

If this policy changes, the updated date at the top of this page will reflect the change. Since we collect no personal data, material changes are unlikely.

---

## Contact

If you have questions about this privacy policy, contact:
**studiodevlabs@gmail.com**
