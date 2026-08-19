\# Maximcine Studios — Website



Landing page for Maximcine Studios / Nebula Strike: Galactic Assault, plus the `app-ads.txt` file needed to pass Google AdMob's app verification.



\## Files



\- `index.html` — one-page site (studio + game info, no build step, no dependencies)

\- `app-ads.txt` — required by AdMob to verify you're authorized to monetize this app



\## Notes



\- No build tools, no npm install — it's a static HTML file, so any static host works if you ever want to move off GitHub Pages (Netlify, Vercel, a custom domain, etc.)

\- If you switch domains later, just make sure `app-ads.txt` lands at the new domain's root and update the Website field in Play Console to match

