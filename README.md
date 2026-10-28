# EXO Talent Consultancy (fremworkcome)

Modern, high-performance consultancy landing page for **EXO Talent Consultancy** — Bridging Ethiopia’s digital divide with skills that last.

## Deployment on Vercel

This repository is pre-configured for instant zero-configuration deployment on **Vercel**:

### Option 1: Import via GitHub (Recommended)
1. Go to [vercel.com/new](https://vercel.com/new).
2. Connect your GitHub account and import `robel-hindeya/fremworkcome`.
3. Keep default settings (Framework preset: `Other`).
4. Click **Deploy**.

Every time you push new commits to the `main` branch, Vercel will automatically re-deploy your website.

### Option 2: Deploy with Vercel CLI
If you have the Vercel CLI installed:
```bash
npx vercel
```
Or for production deployment:
```bash
npx vercel --prod
```

## Structure

- `index.html` — The main entry point configured for web servers and Vercel.
- `Main.dc.html` — Design component artboard reference.
- `vercel.json` — Vercel routing rules, clean URLs, and asset cache headers.
- `assets/` — Images, photography, and icons.
- `vendor/` & `support.js` — React runtime rendering engine.
