# STACKED — money coach PWA

## Publish/update on GitHub Pages
1. Download and unzip this package.
2. Upload the files inside `stacked_pwa` to the root of your existing GitHub Pages repository, replacing the old versions.
3. Commit the changes and wait for Pages to deploy.
4. Open your existing STACKED URL and refresh. If the old version remains, close the installed app/tab and reopen it after a short wait.

## Included
- Editable spending, savings, cash and weekly-pay balances.
- Editable weekly budget.
- Multiple savings goals with targets, progress and saved amounts.
- Manual income/spending log; each entry updates the selected tracked balance.
- Last-30-day average income/spending estimates based on transactions you log.
- Basic money-coach suggestions based on your budget and logged transactions.
- Optional browser notifications and test/check-in alerts.
- Local browser storage and JSON backup export.

## Important limitations
- This is not connected to Nationwide or any bank. Balances and transactions are manual until a genuine Open Banking integration is implemented securely.
- Notifications can be requested and triggered from the app, but reliable automatic alerts while the app is closed require a push service/backend. No bank-event alerts are active.
- Data stays in the browser/device profile. It does not automatically sync between your PC and phone. Export a backup periodically.
- For safety, do not put bank credentials, Open Banking tokens, or SimpleFIN claim tokens into this repository or client-side code.
