# ruisuphd.github.io

Personal website of Rui Su — AI Engineer, PhD Candidate at Maynooth University, Founder of [Intonation Labs](https://www.intonationlabs.com).

Live at **[www.ruisuphd.com](https://www.ruisuphd.com)** (GitHub Pages).

## Structure

- `index.html` — single-page site, plain HTML/CSS, no build step
- `photo.jpg` — profile photo
- `papers/` — downloadable PDFs of publications
- `certs/` — downloadable PDFs of Coursera certificates
- `CNAME` — custom domain for GitHub Pages

## Deployment

Pushing to `main` deploys automatically via GitHub Pages (Settings → Pages → Deploy from branch `main`, `/ (root)`).

### Custom domain DNS

At the domain registrar for `ruisuphd.com`:

| Type  | Name | Value              |
|-------|------|--------------------|
| CNAME | www  | ruisuphd.github.io |
| A     | @    | 185.199.108.153    |
| A     | @    | 185.199.109.153    |
| A     | @    | 185.199.110.153    |
| A     | @    | 185.199.111.153    |

Then in repo Settings → Pages: set custom domain `www.ruisuphd.com` and enable **Enforce HTTPS**.
