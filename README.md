
# AJK Electrical & Air Conditioning Website

## Current Status
**DO NOT INDEX** — This site is blocked from search engines.

- `robots.txt` disallows crawling.
- All HTML pages contain `<meta name="robots" content="noindex, nofollow">`.

## Going Live
1. Change `<meta name="robots" content="noindex, nofollow">` to `index, follow` in all HTML files.
2. Update `robots.txt` to:
   ```
   User-agent: *
   Allow: /
   ```
3. Submit sitemap to Google Search Console.

## Structure
- index.html — Home
- services.html — Services overview
- service-areas.html — Hub page linking to suburb pages
- electrician-<suburb>.html — 10 suburb landing pages
- contact.html — Contact form/details
- booking.html — Booking page (TidyCal embed)
- privacy.html, terms.html — Legal pages
- /assets/ — Logos/images
- /css/style.css — Stylesheet
