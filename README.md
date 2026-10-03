# Abdul Rauf Qureshi — Portfolio

Static portfolio site (plain HTML/CSS, no build step), hosted on DigitalOcean App Platform.

**Live:** https://stingray-app-mof8k.ondigitalocean.app/

## Local preview

Open `index.html` in a browser.

## Deploy

The App Platform spec is in `.do/app.yaml`. Every push to `main` redeploys automatically.

- **Console:** DigitalOcean → Apps → Create App → GitHub → `qrauf/AbdulRaufQureshi` (branch `main`). It is detected as a static site.
- **CLI:** `doctl apps create --spec .do/app.yaml`
