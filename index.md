# Privacy Policy — StockIt

**Last updated:** May 2026

---

## The Short Version

StockIt does not collect, store, transmit, or sell any of your personal data or financial information. Everything stays on your phone.

---

## What Data StockIt Accesses

### Data you enter yourself
- Stock transactions (buy, sell, dividend, deposit, withdraw)
- Holdings, price overrides, portfolio notes
- Fixed deposit, gold, and retirement account details
- Mutual fund units and purchase NAV

All of this data is stored **only on your device**, encrypted using AES-256 with a key stored in the Android Keystore. It never leaves your device unless you explicitly choose to back it up to your own Google Drive account.

### Data fetched automatically
- **Stock prices:** Live prices are fetched from Yahoo Finance's public API. Your portfolio holdings are NOT sent to Yahoo Finance — only the ticker symbol (e.g., "HDFCBANK.NS") is used in the URL. This is equivalent to searching for a stock price on Google.
- **Mutual Fund NAV:** Fetched from api.mfapi.in (AMFI's public API). Only the scheme code is used. No personal data is sent.
- **CAS PDF parsing:** Performed entirely on your device using JavaScript. The PDF never leaves your phone.

---

## What Data StockIt Does NOT Collect

- ❌ No name, email, phone number, or identity
- ❌ No device identifiers sent to any server
- ❌ No location data
- ❌ No analytics or usage tracking (no Firebase, Mixpanel, or equivalent)
- ❌ No crash reporting that transmits data (no Sentry, Crashlytics, or equivalent)
- ❌ No advertising identifiers
- ❌ No portfolio data on any StockIt server (we don't have servers)

---

## Google Drive Backup (Optional)

If you connect Google Drive, StockIt uploads an encrypted JSON backup file to your own Google Drive account. This is:
- **Opt-in only** — disabled by default
- **Your account, your file** — StockIt does not have access to your Google Drive
- **Your data, your control** — you can delete the backup at any time

StockIt uses the Google Drive API with a scope limited to files it creates (`drive.file`). It cannot access other files in your Drive.

---

## Notifications

If you enable price alerts or daily summaries, StockIt schedules local notifications on your device. No notification content is sent to any server.

---

## Third-Party Services

| Service | Purpose | Data shared |
|---|---|---|
| Yahoo Finance (query1.finance.yahoo.com) | Live stock prices | Ticker symbols only (e.g., "HDFCBANK.NS") |
| api.mfapi.in | Mutual fund NAV | Scheme codes only (e.g., "120503") |
| Google Drive API | Optional backup | Encrypted JSON file to your own Drive |

No other third-party services are used.

---

## Children's Privacy

StockIt is not directed at children under 13. We do not knowingly collect any data from children.

---

## Changes to This Policy

If this policy changes, the updated date at the top of this page will reflect the change. Since we collect no data, material changes are unlikely.

---

## Contact

If you have questions about this privacy policy, contact:
**[your-email@example.com]**

---

## Where to Host This Policy

**Free options:**
1. **GitHub Pages** — Create a repo `yourname/stockit-privacy`, add this as `index.md`, enable Pages. URL: `https://yourname.github.io/stockit-privacy`
2. **Notion** — Paste this into a public Notion page. Free, instant.
3. **Google Sites** — Free, no coding, gives a credible URL

**Recommended:** GitHub Pages — takes 5 minutes, looks professional, permanent URL.
