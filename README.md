# My Household Budget (Android installable web app)

## Included
- Mobile-friendly household budget dashboard
- Regular income and bills (weekly, fortnightly, every 4 weeks, monthly, quarterly, yearly, or one-off)
- Edit, pause, and delete regular items
- Manually add/edit/delete one-off income and spending
- 12-month day-by-day cashflow forecast with daily closing balances
- Low-balance warning threshold and monthly lowest-balance figures
- Starting balance, JSON backup/restore, and CSV export
- Offline caching after the first visit

## Install on Android
A Progressive Web App must be served from a secure HTTPS website to be installable. These files are ready to host:
1. Upload the contents of this folder to a static HTTPS host (for example, a private GitHub Pages site or another static web host).
2. Open the hosted `index.html` in Chrome on your Android phone.
3. Open Chrome's menu (⋮) and choose **Install app** or **Add to Home screen**.
4. After the first successful load, the app can work offline.

You can also open `index.html` directly to test it, but direct-file opening does not provide the full install/offline PWA experience.

## Privacy and data
Budget information is stored in the browser's local storage on the phone. It is not sent to a bank or to this app's author. Export a JSON backup regularly. Clearing Chrome site data can erase the budget. Import the JSON backup on a replacement phone/browser.

## Forecast assumptions
- Regular items repeat from the date entered.
- Monthly and longer frequencies preserve the day of month where possible (e.g. a 31st rolls to the last valid day).
- Forecast shows the opening balance plus dated income and outgoings.
- Variable spending is included only after you manually record it.
- This is a planning tool, not a bank feed or financial advice.
