# TrueForm Concrete Construction — Astro

**Quality Concrete Construction LLC d/b/a TrueForm Concrete Construction LLC** — Gastonia, NC

Minimal, elegant homepage — whitespace-heavy, SEO-optimized, now on **Astro 4**.

## Stack
- Astro 4 (static)
- No frameworks — pure Astro + CSS

## Dev
```bash
npm install
npm run dev    # http://localhost:4321
npm run build  # -> dist/
npm run preview
```

## Structure
```
src/pages/index.astro   # Homepage
src/layouts/Layout.astro # SEO + global styles
public/                  # Static assets
```

## Deploy
`dist/` is static — deploy to Cloudflare Pages / Netlify / Vercel.

## SEO
- Title/meta + OG + canonical
- LocalBusiness schema with d/b/a disclosure
- areaServed: Gastonia + 11 cities
