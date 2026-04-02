# Ledger & Flow Website (Static)

Production-ready marketing site for Ledger & Flow. Built to be fast, clean, and conversion-focused, with a clear path to booking a discovery call and verification links (ProAdvisor + Credly badges).

- Live site: https://ledgerandflow.com/

## Status
- Current state: complete for current business needs
- Last updated: 2026-04-01

## What this site does
- Drives discovery calls via Calendly (primary CTA)
- Explains services clearly (bookkeeping first, plus optional advisory support)
- Adds trust signals (Credly badges + QuickBooks ProAdvisor listing)
- Includes a light cross-link to mobile notary services (secondary offering)
- Runs fully static (GitHub Pages friendly, no backend required)

## Key links
- Discovery call: https://calendly.com/ledgerandflow/financial-health-check
- QuickBooks ProAdvisor: https://proadvisor.intuit.com/app/accountant/search?searchId=dylan-todd
- Email: mailto:hello@ledgerandflow.com
- Mobile notary: https://thergvnotary.com

## Notable implementation details
- Brand palette aligned to logo (green primary with gold accents)
- CTA/button styling standardized site-wide for a consistent brand look
- Mobile hero CTA layout fixed (centered and uniform stacking)
- Icon layout tightened in key sections (services/credibility/contact)
- FAQ loads collapsed by default

## Tech stack
- HTML / CSS / JS
- Bootstrap + Bootstrap Icons
- AOS (scroll animations)
- Google Analytics (GA4)
- JSON-LD structured data (AccountingService)

## Project structure
- `index.html` - main landing page
- `assets/css/main.css` - styling (includes CTA/button overrides + brand polish)
- `assets/js/main.js` - interactions/behavior
- `assets/img/` - logo, badges, OG assets, page imagery

## Hosting
- Static deployment (GitHub Pages)
- Contact handled via:
  - Calendly booking link
  - Email (`mailto:`)
- No server-side dependencies

## Version tracker
- v0.1.0 (2025-12-15)
  - Replace coming-soon page with a full marketing site and booking funnel
  - Remove form/backend dependencies for static hosting
  - Add SEO metadata, OG/Twitter, GA4, and JSON-LD
- v0.1.1 (2025-12-21)
  - Add logo and credibility accents (icons + badges)
  - Standardize CTA styling for consistent brand presentation
- v0.1.2 (2026-04-01)
  - Align styling to logo palette (green + gold)
  - Fix mobile hero CTA alignment and spacing
  - Improve icon layout in credibility/contact sections
  - Ensure FAQ loads closed by default
  - Add a subtle notary cross-link as a secondary offering