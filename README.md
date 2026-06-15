# Youngren Consulting — Website

Single-page marketing site for Youngren Consulting, LLC — AI & data readiness consulting for mid-market companies.

**Live at https://youngrenconsulting.com**

## Files

- `youngren_consulting.html` — the source single-page site (self-contained: inline CSS, JS, and base64 images).
- `index.html` — deploy copy served by GitHub Pages. Keep it in sync with `youngren_consulting.html` on every change.
- `CNAME` — custom domain config for GitHub Pages (managed by GitHub; do not edit by hand).

## Local preview

Open `youngren_consulting.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/youngren_consulting.html
```

## Hosting

Hosted on GitHub Pages (builds from `main`, root) with the custom domain
`youngrenconsulting.com` (Enforce HTTPS on). DNS lives at Namecheap: four `A`
records on the apex pointing at GitHub's Pages IPs (185.199.108–111.153) and a
`www` CNAME to `tim-yoco.github.io`. Pushing to `main` redeploys automatically.
