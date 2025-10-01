# DPP Demo — Aurora Wool Blend Overcoat

This folder contains a minimal Digital Product Passport (DPP) demo for a coat.

Files:
- `index.html` — human‑readable page (also embeds JSON‑LD for machines).
- `dpp.json` — machine‑readable DPP payload.
- `dpp_qr.png` — QR code pointing to https://your-domain.example/dpp/coat-aurora-01/index.html (replace domain after hosting).

## Quick hosting (GitHub Pages)
1. Create a public repo, e.g., `dpp-coat-demo`.
2. Put these files at the root or in `docs/`. If using `docs/`, set Pages source to `docs/`.
3. Enable GitHub Pages. You will get a URL like `https://<user>.github.io/dpp-coat-demo/`.
4. Update links inside `index.html` and `dpp.json` if you want to use GS1 Digital Link style.
5. Re-generate the QR to point to the final URL.

## Quick hosting (Cloudflare Pages)
1. Create a new project; upload this folder as a static site.
2. Your site will be deployed at a URL like `https://<project>.pages.dev/`.
3. Update the links and QR if desired.

## GS1 Digital Link (example)
- https://your-domain.example/01/09506000134352/21/AURORA0001

