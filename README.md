# MyWholeHQ — marketing site

**Status: LIVE build (Nov 20, 2026).** Owner approved building and launching the site on Nov 20, 2026.
Hosted on GitHub Pages from this repo; custom domain **mywholehq.com** (DNS at Namecheap).

## Files

- `index.html` — the whole site (single page): hero → pain points → module grid → who it's for → setup → security → pricing → invite form → footer
- `style.css` — all styling (mobile-first; breakpoints at 620px and 900px)
- `thanks.html` — landing page after the invite form submits
- `404.html` — custom not-found page
- `favicon.svg` — navy tile "M" with copper dot
- `CNAME` — GitHub Pages custom domain (mywholehq.com)

## Facts baked in (verified Nov 20, 2026)

- **Pricing:** Founding plan **$29/month per business, unlimited users**, every feature included.
- **Trial:** 14 days free, starts at business setup, **no card required**.
- **Onboarding is invite-only** in the app (no public self-signup) — the site's CTA is "Request your invite."
- **No AI features at launch** — the app ships with AI disabled; the site must never advertise AI features.
- Invite form posts via **FormSubmit** to newlifegc.indy@gmail.com (same service as the NLGC site form), redirecting to thanks.html. First submission may trigger a one-time FormSubmit activation email to that inbox — confirm it once.
- Privacy / Terms links point at the app's own pages (app.mywholehq.com/privacy, /terms) — single source of truth; do not copy them here.
- App sign-in: https://app.mywholehq.com/

## Placeholders

- **Logo:** no final logo yet. Header/footer use a text wordmark with an "M" tile; swap spots are marked with `<!-- LOGO SPOT (placeholder) -->` comments in `index.html`.
- **Hero preview panel** is a pure CSS/SVG illustration, not a screenshot. Replace with real screenshots when the product UI is ready to show publicly.
- **No testimonials, customer counts, or metrics** — none exist to publish yet. Do not add any that aren't real and approved.

## DNS (Namecheap, mywholehq.com)

- Apex `@` → GitHub Pages A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `www` → CNAME ambriLopata.github.io
- `app` → CNAME mywholehq.onrender.com (**the live app — never touch**)
- Optional later: point getwholehq.com at this domain as a redirect.

## Notes

- No external assets: no stock photos, no web fonts, no trackers. Visuals are CSS/SVG only.
- Palette: deep navy + white with a warm copper accent (matches the app brand).
