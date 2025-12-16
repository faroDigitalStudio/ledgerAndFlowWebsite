# Ledger & Flow Website

Public-facing marketing site for Ledger & Flow. Built to be fast, clear, and conversion-focused, with a direct path to a discovery call and trusted profile links.

- Site: https://ledgerandflow.com/

## What this site does
- Drives visitors to a 30-minute Financial Health Check (Calendly)
- Explains services quickly (bookkeeping, cleanup, payroll support, reporting)
- Adds trust signals (certification badges + directory listing)
- Works cleanly on GitHub Pages (no server requirements)

## Tech stack
- HTML / CSS / JS
- Bootstrap + Bootstrap Icons
- AOS (scroll animations)
- Google Analytics (GA4)
- JSON-LD structured data for an AccountingService

## Project structure
- `index.html` — main landing page
- `assets/css/main.css` — site styling
- `assets/js/main.js` — site behavior
- `assets/img/` — images, badges, OG image

## Hosting
- Static deployment via GitHub Pages
- Contact routing:
  - Calendly booking link
  - `mailto:` email link
- No web contact form included (keeps hosting simple and reliable)

## SEO + analytics
- Canonical + robots meta
- Open Graph + Twitter card metadata
- JSON-LD structured data
- GA4 tracking via gtag

## Version tracker
- v0.1.0 (2025-12-15)
  - Ship Ledger & Flow landing page with Calendly-first conversion flow
  - Remove PHP form dependencies for static hosting compatibility
  - Refresh metadata, structured data, and profile links

## Roadmap checklist
- [ ] Refine messaging and tone for clarity and fit
- [ ] Add `sitemap.xml` + `robots.txt` (recommended for indexing)
- [ ] Add `404.html` for GitHub Pages
- [ ] Optimize images and confirm OG image/share previews
- [ ] Accessibility pass (headings, contrast, focus states, nav)
- [ ] Add a simple privacy page if needed for analytics transparency
