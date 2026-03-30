# Radar — Logistics Real Estate Scanner

## Deploy to Vercel

1. Upload this folder to a new GitHub repository called `radar`
2. Go to vercel.com → New Project → Import from GitHub
3. Select the `radar` repo
4. No build settings needed — Vercel detects static HTML automatically
5. Click Deploy

## After deploying

Add your Vercel URL to the Mapbox token allowlist:
1. Go to account.mapbox.com/tokens
2. Click your token
3. Add `https://radar-[yourproject].vercel.app` under Allowed URLs
4. Also add `http://localhost:*` for local testing

## Files
- `index.html` — the full Radar application
- `vercel.json` — Vercel routing config
