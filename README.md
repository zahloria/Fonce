# Fonce

> Showcase what you sell.

A creator commerce platform where influencers curate dropshipped products with their own markup. Audiences shop through a tasteful, customizable showcase.

## Live demo

Open `index.html` in any modern browser. No build step, no dependencies, no server required.

## What's included

This is the single-file working prototype of Fonce. All app logic, styles, and UI live in `index.html`.

**Core features:**
- Creator sign-up + dashboard
- Product import from source URLs (CJDropshipping, Spocket, Modalyst, Printful, Printify, Trendsi, Zendrop)
- Public showcase with 3 layout templates (grid, editorial, minimal)
- 13 themes including 5 VIP textured themes (Cement, Starry, Marble, Velvet, Linen) with Live ambient mode
- 12 curated font pairings
- Custom color, gradient, and image backgrounds
- Cross-creator cart + checkout flow
- Fonce Rewards (5% cashback for VIP buyers, 90-day expiration)
- Per-product reviews with creator replies
- Phone preview demo for marketing landing page

**Data storage:** Browser localStorage only. The prototype has no backend; each user's data lives in their own browser.

## Approved product sources

Fonce only auto-fills and works reliably with platforms that have proper APIs or open metadata:

**Dropshipping:**
- CJdropshipping
- Spocket
- Zendrop
- Modalyst
- Trendsi

**Print on Demand:**
- Printful
- Printify

AliExpress, Amazon, Etsy, Walmart, and eBay are not supported — either due to anti-scraping protection, lack of fulfillment APIs, or ToS violations.

## Roadmap (production)

This prototype demonstrates the experience. A production launch requires:
- Real backend (Next.js + Supabase recommended)
- Stripe Connect for split payments (creator payouts + platform fee)
- CJDropshipping API for real order fulfillment
- Email service (Resend)
- File storage for product/profile images (Cloudflare R2 or S3)
- Florida LLC + Stripe business verification
- Trademark search

## Branding

Brand colors:
- Background ombre: `#0a0a14 → #1a1430 → #3d1f47 → #722844 → #b03f48 → #de6e3a → #e8a04a → #1a1410`
- Accent gold: `#d4af37`
- Cream: `#f5efe4`

## License

All rights reserved. © Fonce.
