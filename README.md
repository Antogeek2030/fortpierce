# Fort Pierce Mold Specialists — Astro Site

Static Astro site for **fortpiercemoldspecialists.com**, optimized for Cloudflare Pages.

## Features
- Responsive, mobile-first design
- Forest green + amber/gold color theme
- OpenStreetMap embed pinpointing 3706 Okeechobee Rd, Fort Pierce, FL 34947
- SEO: meta tags, canonical, JSON-LD LocalBusiness schema, sitemap, robots.txt
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(772) 555-0199** — replace in source files (search for `7725550199` and `555-0199`).

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `fortpiercemoldspecialists.com`.
5. Submit `https://fortpiercemoldspecialists.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Site is fully static (`output: 'static'` by default) — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
