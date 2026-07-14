# pennora.org

The public website for **Pennora** — a simple, private personal finance tracker for
income, expenses, savings and investments.

This repository currently hosts the **"coming soon" landing page** while the product is
being built.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | The landing / under-construction page |
| `og-image.png` | Social share preview image (1200×630) |
| `robots.txt` | Crawler directives + sitemap reference |
| `sitemap.xml` | Sitemap for search engines |
| `CNAME` | Custom domain for GitHub Pages (`pennora.org`) |

## Hosting

Served via **GitHub Pages** from the `main` branch (root), with the custom domain
`pennora.org` and HTTPS enforced.

## Local preview

Open `index.html` directly in a browser, or run a simple static server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Email sign-ups

The "Notify me" form on the landing page posts to a form endpoint. Replace the
`REPLACE_WITH_FORM_ID` placeholder in `index.html` with a real
[Formspree](https://formspree.io) form ID (or another provider) to start collecting
sign-ups.

## Roadmap

- [x] Secure domain + enforce HTTPS
- [x] Publish under-construction landing page
- [x] SEO basics (OG image, sitemap, robots)
- [x] Email capture for launch list
- [ ] Move app data storage off local-only
- [ ] Split the app into separate HTML/CSS/JS
- [ ] Publish the live app
