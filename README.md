# trackmidolla — free GitHub Pages version

This is the simple personal version of trackmidolla. It does **not** need Cloudflare, GoCardless, API keys or a business account.

## What it does
- Business / Personal / Expenses totals
- Add, edit and delete transactions
- Select multiple transactions and bulk-categorise or delete
- Import Monzo CSV files
- Import Lloyds Bank CSV files
- Imported transactions start as **UNSORTED** so you can select and categorise them
- Duplicate protection for repeated CSV imports
- £ GBP currency
- Dark black + lime-green typewriter style
- Installable on iPhone Home Screen as a PWA
- Data is stored locally in the browser on the device

## Put it on GitHub Pages
1. Open your `trackmidolla` repository on GitHub.
2. Replace the existing files with the files in this folder. Upload the files themselves, not this ZIP.
3. Make sure `index.html` is in the main/root of the repository.
4. In GitHub: **Settings → Pages → Deploy from a branch → main → /(root) → Save**.
5. Wait a few minutes, then open your GitHub Pages address in Safari.
6. On iPhone: **Share → Add to Home Screen → Add**.

Your address will be:
`https://YOUR-GITHUB-USERNAME.github.io/trackmidolla/`

## Bank CSV imports
Export transactions from Monzo or Lloyds as CSV, then use **BANKS** inside trackmidolla. The importer looks for common date, description and amount/debit/credit columns. Your CSV is read locally in the browser and is not uploaded to a server.
