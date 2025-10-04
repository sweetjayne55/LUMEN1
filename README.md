# VPF App Starter

This repo is ready for **one‑click deploy to Netlify**.

## Quick start
1. Push this folder to a new GitHub repo, for example: `https://github.com/yourname/vpf-app`.
2. Open **deploy-link.html** (included in this folder), paste your GitHub repo URL, and click **Generate & Go**.
   - It will open your personalized **Deploy to Netlify** link in a new tab.
3. Netlify will clone → install → build → deploy.

## Manual deploy button (optional)
If you prefer to paste a static button in your README after you know your repo URL, use:

```md
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=YOUR_GITHUB_REPO_URL)
```

Replace `YOUR_GITHUB_REPO_URL` with your actual GitHub repo URL, e.g. `https://github.com/yourname/vpf-app`.

---

### Project info
- Framework: React + Vite
- Build: `npm run build`
- Output dir: `dist`
- VPF manifest publishes to: `/.well-known/vpf/manifest.json`

### Where to put your VPF file
Already included at: `public/.well-known/vpf/manifest.json`.
