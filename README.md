# davidrachford.com

Static placeholder site for David Rachford, CPA. Single-file HTML, no build step.

## Files

- `index.html` — the landing page (all CSS inline, no dependencies)
- `CNAME` — custom domain for GitHub Pages / Cloudflare Pages
- `robots.txt`, `sitemap.xml` — basic SEO
- `.gitignore`

## Deploy (Cloudflare Pages)

1. Push this repo to GitHub.
2. In Cloudflare Pages: Create a project, connect the GitHub repo.
3. Build settings: framework preset = None, build command = (blank), output directory = `/`.
4. Add custom domain `davidrachford.com` in the Pages project, then point DNS.

## Deploy (GitHub Pages)

1. Push to GitHub.
2. Settings > Pages > Source = `main` branch, `/root`.
3. The `CNAME` file sets the custom domain automatically.

## Push to a remote

```
git remote add origin <your-repo-url>
git branch -M main
git push -u origin main
```
