# Shahid Aftab — Portfolio (Vercel Ready)

This folder contains a static site you can deploy to Vercel in seconds.

## Quick Deploy (GitHub method)
1. Create a new GitHub repo and upload all files in this folder.
2. Go to https://vercel.com → **Add New… → Project** → import your repo.
3. Framework Preset: **Other** (Static Site). No build command. Output directory: leave **empty**.
4. Click **Deploy**. Your site will be live on a vercel.app URL.

## Quick Deploy (Vercel CLI)
```bash
npm i -g vercel
vercel login
vercel # answer the prompts, select "Other" / Static
# For production URL:
vercel --prod
```

### Notes
- This is a static site (no build step). `index.html` is the entry point.
- `vercel.json` is optional here; it's included to enable clean URLs and caching headers.
- Your email and phone are visible on the page. If you want to hide or obfuscate them, edit `index.html` before deploying.
