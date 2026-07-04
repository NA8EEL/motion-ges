# Deploy this static site to Vercel

This project serves static files from the `public/` folder. `vercel.json` maps the site root to `public/intex.html`.

Quick steps to deploy from the project root:

1. Install the Vercel CLI (if you don't have it):

```powershell
npm install -g vercel
```

2. Log in to Vercel (opens browser):

```powershell
vercel login
```

3. Deploy (interactive first-time; use `--prod` for a production deploy):

```powershell
vercel --prod
```

Notes:
- The included [vercel.json](vercel.json) routes `/` to `public/intex.html` and serves other files from `public/`.
- If you want automatic deployments from GitHub, push this repo to GitHub and connect it in the Vercel dashboard.
- To test locally, run `vercel dev` (requires Vercel CLI).

If you want, I can initialize a git repo and run the first `vercel --prod` deploy for you.
