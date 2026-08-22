# Snead Comfort Solutions — sneadcomfort.com

Marketing site for Snead Comfort Solutions, an owner-operated certified HVAC company
(repairs, installations, system changeouts, quarterly maintenance) run by Wesley Snead.

## What's here

- `index.html` — the whole site, a single self-contained page (styles inline, fonts from Google Fonts).
- `assets/logo-5-final.svg` — **the final logo** (Wesley's pick): wide lime/blue diamond with italic SCS.
  Brand colors: lime `#8CC63F`, brand blue `#1B5CA8`, deep blue `#0F3563`. Typefaces: Kanit Black Italic (SCS monogram), Poppins (wordmark and site).
- `assets/logo-1-diamond-monogram.svg` … `logo-4-wordmark.svg` — first-round concepts, kept for reference
  (these use the original navy/ember palette).
- `assets/favicon.svg` — browser tab icon.
- `CNAME` — points GitHub Pages at sneadcomfort.com.

## Business details

- **Phone**: (660) 254-4556 — appears in the header, hero, maintenance band, and contact
  section as `tel:+16602544556` links, so it dials on tap from a phone.
- **Email**: sneadcomfort@gmail.com
- **Service area**: Maryville, MO and surrounding areas.

To change any of these later, search `index.html` for `6602544556`, `sneadcomfort@gmail.com`,
or `Maryville` — and update the `<meta name="description">` tag too, which repeats the phone
number and town for search engines.

Still optional: add Wesley's HVAC license/cert number to the footer if Missouri requires it
on advertising.

## Going live

1. **Enable GitHub Pages** (one time, needs repo admin): repo **Settings → Pages →
   Build and deployment → Source: "Deploy from a branch"** → Branch:
   `claude/snead-comfort-website-necqx4`, folder `/ (root)` → Save.
   The site appears at `https://kiddeke.github.io/snead-comfort/` within a minute or two.
2. **Point the domain**: at your registrar, add these DNS records for sneadcomfort.com —
   four A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`,
   `185.199.111.153`, plus a CNAME record for `www` → `kiddeke.github.io`.
   The `CNAME` file in this repo tells Pages the custom domain automatically.
3. Back in Settings → Pages, confirm **Custom domain** shows `sneadcomfort.com` and
   tick **Enforce HTTPS** once the certificate is issued (can take up to an hour).

Any other static host (Netlify, Cloudflare Pages) works too — just serve this folder.

## Logo note

The SVG logos use the Barlow Condensed font by name. Browsers with the site open render
it correctly; for print/embroidery vendors, export a version with text converted to
outlines (any vector editor: select text → "convert to path/outlines").
