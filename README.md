# Estimate for Leesa — Next Finish Carpentry

Public host for the 127 lf deck cable-railing proposal.

Source of truth (private):
`luizhbr/next-finish-carpentry` → `client-proposals/estimateforLeesa/index.html`

## Publish on Cloudflare Pages (recommended)

1. Open [Cloudflare Dashboard](https://dash.cloudflare.com) → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
2. Authorize GitHub and select **next-finish-carpentry** (or this public repo if you copied `index.html` here).
3. Build settings:
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`
   - Root directory: `client-proposals/estimateforLeesa` (only if you connected the private repo)
4. Deploy. Share the `*.pages.dev` URL with Leesa.

Direct upload option: Workers & Pages → Create → Pages → Upload assets → drop the folder that contains `index.html`.

## GitHub Pages (backup)

Put `index.html` in the root of this repo, then Settings → Pages → Deploy from branch `main` / root.
Live URL will be:
https://luizhbr.github.io/estimate-for-leesa/

<!-- cert-bump 2026-09-18 -- keep custom domain CNAME active -->
