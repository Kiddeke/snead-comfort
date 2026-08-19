# Snead Comfort Solutions — sneadcomfort.com

Marketing site for Snead Comfort Solutions, an owner-operated certified HVAC company
(repairs, installations, system changeouts, quarterly maintenance) run by Wesley Snead.

## What's here

- `index.html` — the whole site, a single self-contained page (styles inline, fonts from Google Fonts).
- `assets/logo-1-diamond-monogram.svg` — Wesley's original idea refined: double-stroked diamond with SCS.
- `assets/logo-2-split-diamond.svg` — heat chevron + cooling chevron forming a diamond around SCS (used on the site).
- `assets/logo-3-vent-badge.svg` — navy shirt-patch badge with vent louvers.
- `assets/logo-4-wordmark.svg` — horizontal lockup for headers, invoices, truck doors.
- `assets/favicon.svg` — browser tab icon.
- `CNAME` — points GitHub Pages at sneadcomfort.com.

## Before launch — replace the placeholders

1. **Phone number**: `(555) 555-0134` / `tel:+15555550134` appears in the header, hero,
   maintenance band, and contact section. Search `index.html` for `555` and replace all.
2. **Service area**: the contact section says "Your Town & Surrounding Areas".
3. **Email**: `wesley@sneadcomfort.com` — set this mailbox up on the domain, or change it.
4. **License number**: add Wesley's HVAC license/cert number to the footer if required in your state.

## Deploying to sneadcomfort.com

Enable GitHub Pages on this repo (Settings → Pages → deploy from branch), then in your
domain registrar point sneadcomfort.com at GitHub Pages (A records `185.199.108.153`,
`.109.`, `.110.`, `.111.` and a `www` CNAME to `<username>.github.io`). The `CNAME` file
here handles the rest. Any other static host (Netlify, Cloudflare Pages) works too —
just serve this folder.

## Logo note

The SVG logos use the Barlow Condensed font by name. Browsers with the site open render
it correctly; for print/embroidery vendors, export a version with text converted to
outlines (any vector editor: select text → "convert to path/outlines").
