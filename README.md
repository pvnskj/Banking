# Spending Compass

A local-first personal spending dashboard. Open `index.html` in a browser or deploy it as a static website.

## Features
- Import CSV and supported XLSX transaction exports
- Explore spending by merchant, category, account, and month
- Track groceries, work cafeteria, delivery, travel, car payments, EV charging, and vehicle registration
- View fund transfers separately from everyday expenses
- Track card purchases net of refunds without treating card repayments as new expenses
- Review budgets, savings, and spending versus income

## Privacy and safety
This repository is public. **Do not commit bank statements, personal transactions, or account details.** Imported transactions and settings are stored locally in the browser through localStorage; they do not automatically sync across browsers. Browser storage is not encryption and is accessible to scripts running on the same origin. Do not enable a public deployment on a shared device with sensitive imported data.

Default savings and income values are intentionally zero; enter your own amounts locally.

## Known limitations
Actual finance totals depend on complete account statements and correct classification. Bank-specific formats and refunds may need review. The app has not been verified end-to-end with all account statements.
