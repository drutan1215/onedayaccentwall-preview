# One Day Accent Wall

One-page website for [onedayaccentwall.com](https://onedayaccentwall.com) — fireplace accent walls, electric fireplaces, and media walls installed in one day by Square One Home Solutions.

- Static site: `index.html` + `images/`, no build step.
- Hero features an interactive "Build Your Wall" configurator; selections prefill the quote form.
- Hosted on GitHub Pages.

## Connecting the custom domain

1. In the repo: Settings → Pages → Custom domain → enter `onedayaccentwall.com`.
2. At your DNS provider, add A records for `@` pointing to GitHub Pages IPs (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a CNAME record for `www` pointing to `drutan1215.github.io`.
3. Enable "Enforce HTTPS" once the DNS check passes.
