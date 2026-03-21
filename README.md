# SimpleKit Mortgage vs Invest Calculator

Static SimpleKit app for comparing two uses of extra cash flow:

- make extra mortgage payments
- invest the same amount instead

The app is built with plain `index.html`, `styles.css`, and `app.js`, keeps the existing SimpleKit visual language, and preserves the Google Analytics head snippet from the template.

## What It Includes

- Canadian-oriented mortgage vs invest comparison
- live side-by-side results
- payoff timing and mortgage interest comparison
- SVG charts for net worth, mortgage balance, investment growth, and outcome summary
- break-even return estimate and sensitivity table
- educational copy, Canadian context, FAQ content, related tool links, and support CTA
- local persistence with `localStorage`

## Defaults

Starter defaults model a realistic Canadian homeowner scenario:

- Mortgage balance: `425000`
- Mortgage rate: `4.75%`
- Years left: `22`
- Monthly payment: `2700`
- Extra monthly amount: `500`
- Home value: `640000`
- Expected annual investment return: `5.5%`
- Time horizon: `10 years`
- Account type: `TFSA`
- Tax drag: `0%`
- MER: `0.25%`
- Home growth: `2%`
- Inflation: `2%`

## Files

- `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/index.html`: page structure, SEO copy, analytics snippet
- `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/styles.css`: SimpleKit theme styles and responsive layout
- `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/app.js`: calculator logic, rendering, charts, tracking hooks
- `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/manifest.webmanifest`: install metadata
- `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/sitemap.xml`: sitemap starter
- `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/robots.txt`: robots rules and sitemap reference

## Before Production Deploy

Before production deploy:

- replace `https://replace-with-live-domain.invalid/` in `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/index.html`, `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/app.js`, and `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/sitemap.xml`
- update `ROUTES.relatedTools` in `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/app.js` if your published suite uses different public URLs than the current sibling-folder structure
- replace `TEMPLATE.socialImageUrl` in `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/app.js` and the matching tags in `/Users/AshleySkinner/Documents/00_Engineering/04_Code/36_Mortgage Investment Simple Kit/index.html` if you want a dedicated PNG/JPG share card instead of `icons/icon.svg`
