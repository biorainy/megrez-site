# Megrez Marketing Site

This is a standalone static landing page for Megrez.

## Why this format

- Easy to host on Cloudflare Pages, Netlify, or Vercel
- No framework lock-in
- Fast to iterate while the product and messaging are still moving

## Local preview

From this folder:

```bash
python3 -m http.server 8787
```

Then open:

```bash
http://localhost:8787
```

## Deploy to Cloudflare Pages

Use Git integration and configure the project as a plain static site.

- Framework preset: `None`
- Production branch: `main`
- Build command: `exit 0`
- Build output directory: `.`

After the first deploy, Cloudflare will host the site at `<project-name>.pages.dev`.

## Before publishing

Update these items in [index.html](/Users/bli/Projects/Megrez/megrez-site/index.html):

- Add your real domain once you choose hosting

## Recommended free hosting

- Cloudflare Pages
- Vercel Hobby

Because this folder is fully static, either can deploy it directly.
