# Fixedpost — Paid Detail Platform Landing Page

Landing page for the Fixedpost platform, built around **NYC PASSPort EPIN 05626P0001 — NYPD Paid Detail Application and Software Platform**.

## Structure

- `site/index.html` — the landing page. Fully self-contained (single file, no build step); fonts load from Google Fonts.
- `documents/` — the 13 public solicitation documents downloaded from the [PASSPort RFx page](https://passport.cityofnewyork.us/page.aspx/en/bpm/process_manage_extranet/31953): the RFP, Addendum 1, Appendix A, Schedule A, Price Proposal workbook, security requirements, and all riders.

## Run locally

Open `site/index.html` in a browser, or:

```bash
cd site && python3 -m http.server 8734
```

## Deploy

Deployed on Vercel from the `site/` directory:

```bash
cd site && vercel --prod
```
