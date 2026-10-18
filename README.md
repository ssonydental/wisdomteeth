# wisdomteeth.ssonydental.com

Static wisdom teeth removal landing page for Smile Services of New York.

## Deploy with GitHub Pages
1. Create a new repo (e.g. `ssonydental/ssny-wisdomteeth`) and upload every file in this folder to the root (keep the `assets/` folder and the hidden `.nojekyll` file).
2. Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)` > Save.
3. In your DNS, add a CNAME record: `wisdomteeth` -> `ssonydental.github.io`.
4. Settings > Pages > Custom domain: `wisdomteeth.ssonydental.com`, then tick Enforce HTTPS once the certificate is issued.

The `CNAME` file keeps the custom domain set across deploys.

## Still to fill in
- Privacy Policy URL in index.html (search "fill in").

## Dentist review before launch
- Food list (250 items) in the food check
- Dry socket time frames: 24 hours before, 72 hours after, 7 days full
- The six causes in the signs checker

## After go-live
- Confirm https://wisdomteeth.ssonydental.com/ loads with the padlock, then submit the sitemap in Google Search Console.
- Verify GTM fires and the pain picker, signs checker, food check and FAQ search push to dataLayer.
