Srvc Foullowrs — README (Strict Zero-Cost Architecture)
============================================================
Business: Srvc Foullowrs — خدماتك الرقمية لنمو حساباتك
WhatsApp: +212 681-560808 | Stack: Single index.html (HTML + Tailwind CDN + Vanilla JS)

ZERO-COST BREAKDOWN
- Hosting: Cloudflare Pages ............... $0/month (unlimited bandwidth, free SSL)
- Database: Browser localStorage .......... $0/month (no paid DB service)
- Orders: WhatsApp wa.me deep links ....... $0/month (no API key, no Twilio)
- Plugins / APIs: none .................... $0/month
- Domain DNS: Cloudflare free tier ........ $0/month
TOTAL: $0.00 / month — no subscriptions, no credit card required.

FREE DEPLOYMENT (Cloudflare Pages) — 5 minutes
Option A: Direct Upload
  1. Save this project as index.html
  2. dash.cloudflare.com > Workers & Pages > Create > Pages > Upload assets
  3. Drag & drop index.html > Deploy > get free https://*.pages.dev URL
  4. Optional: attach your own domain via Cloudflare DNS (free)
Option B: GitHub (auto-redeploy on every push)
  1. Create a free GitHub repo, upload index.html
  2. Cloudflare Pages > Connect to Git > select repo > Deploy

HOW TO EDIT (no paid tools)
- Fast: Admin panel on the site (password: admin123 — change ADMIN_PASSWORD in code!)
  Edit services/prices, coupons, branding, WhatsApp number. Data saves in localStorage.
  Use Admin > Backup & Export to download JSON backup or the full project (.html).
- Code: open index.html in VS Code/Notepad. Search "defaultState()" for prices,
  "TRANSLATIONS" for text, "212681560808" for the WhatsApp number.

FEATURES
- Arabic (RTL) / French (LTR) / English (LTR) — switcher in header
- Service catalog with platform filters + live search + sorting
- Automatic price calculator (per-1000 pricing, quantity presets)
- Discount coupons with minimum-subtotal rules
- One-click WhatsApp order message generation
- Admin panel: services, prices, branding, coupons, export/import
- Fully responsive, dark premium UI, no external paid services