# michaelkarel.com

Static site for michaelkarel.com, served by GitHub Pages. No build step.

Pages: `index.html` (home), `podcast.html`, `ministry.html`, `contact.html`. Shared styles are in `assets/site.css`.

## Deploy
1. Create a repo (for example `michaelkarel-com`) under the same GitHub account as the other sites and push these files to `main`.
2. Repo Settings > Pages: deploy from branch `main`, folder `/ (root)`. The `CNAME` file sets the custom domain.
3. At the DNS provider, point the apex `michaelkarel.com` to GitHub Pages with four A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153. Add a `www` CNAME record pointing to `<account>.github.io`.
4. When the certificate is ready, tick "Enforce HTTPS" in Pages settings.

## Before launch
- Replace `REPLACE-WITH-YOUR-HANDLE` in the LinkedIn link in `contact.html`.
