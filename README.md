# homeofficesinternational.com

## Deploy

This is a static site (no build step). You can deploy via Netlify CLI or by pushing to the connected GitHub repo.

### Netlify CLI (manual deploy)

1) Link the repo to the Netlify site (only needed once):
```bash
netlify link --id 15254b08-0099-4b2e-877e-117a9e7f01aa
```

2) Deploy to production:
```bash
netlify deploy --prod --dir .
```

### GitHub auto-deploy

If the Netlify site is connected to GitHub, just commit and push. Netlify will publish automatically.

## Local preview

```bash
python3 -m http.server 8080
```
Then visit `http://localhost:8080/`.
