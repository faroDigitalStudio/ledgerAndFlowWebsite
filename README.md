# Ledger & Flow — Marketing Site (Static)

Public-facing website built for Ledger & Flow with a clean, conversion-first layout and a simple path to booking a discovery call.

- Live site: https://ledgerandflow.com/

## Current state
This site is considered production-ready for current business needs:
- Clear service overview + trust signals
- Consistent branded styling (green CTAs)
- Strong primary conversion path (Calendly)
- Static hosting compatible (no backend required)

## Goals
- Drive discovery calls via Calendly
- Explain services quickly (bookkeeping first, with optional advisory support)
- Provide verification paths (ProAdvisor + Credly badges)
- Keep the site fast, stable, and easy to maintain

## Key links
- Discovery call: https://calendly.com/ledgerandflow/financial-health-check
- QuickBooks ProAdvisor: https://proadvisor.intuit.com/app/accountant/search?searchId=dylan-todd
- Email: mailto:hello@ledgerandflow.com

## Tech stack
- HTML / CSS / JS
- Bootstrap + Bootstrap Icons
- AOS (scroll animations)
- Google Analytics (GA4)
- JSON-LD structured data (AccountingService)

## Project structure
- `index.html` — main landing page
- `assets/css/main.css` — styling (includes Bootstrap button color overrides for brand consistency)
- `assets/js/main.js` — interactions/behavior
- `assets/img/` — images, badges, OG assets, logo

## Hosting + contact
- Static deployment (GitHub Pages)
- Contact via:
  - Calendly booking link
  - Email (`mailto:`)
- No web form or server-side dependencies

## SEO + analytics
- Canonical + robots meta
- Open Graph + Twitter card metadata
- JSON-LD structured data
- GA4 via gtag

## Version tracker
- v0.1.0 (2025-12-15)
  - Rework template into a Ledger & Flow landing page with a Calendly-first funnel
  - Remove PHP/contact form dependencies for static hosting
  - Update metadata (SEO, OG/Twitter) and structured data (JSON-LD)
- v0.1.1 (2025-12-21)
  - Tighten hero and CTA messaging
  - Add logo + icon accents for platform credibility
  - Standardize CTA styling by overriding Bootstrap primary/outline colors to match brand green

## Future enhancements (optional)
- Add `sitemap.xml`, `robots.txt`, and `404.html`
- Add a lightweight blog/resources section (static)
- Continue copy refinements as services evolve