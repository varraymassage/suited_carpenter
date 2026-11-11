# Suited Carpenter LLC — Luxury Website

A static, responsive website for Suited Carpenter LLC. No build tools or paid hosting required.

## Files
- `index.html` — content and contact links
- `styles.css` — responsive luxury styling
- `script.js` — automatic copyright year
- `assets/logo.png` — selected logo
- `CNAME` — custom domain for GitHub Pages

## New GitHub repository
1. Go to https://github.com/new and create a **public** repository named `suited-carpenter-luxury` (or another name).
2. Extract the ZIP and upload the **contents** of this folder, not the folder itself. `index.html` must be in the repository root.
3. Commit the files.
4. Under **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
5. Under Pages → Custom domain, enter `suitedcarpenter.com` and Save (the `CNAME` file is already included).

## Namecheap DNS (when ready to publish)
In Namecheap → Domain List → Manage → Advanced DNS, add GitHub Pages apex A records:
- A | @ | 185.199.108.153
- A | @ | 185.199.109.153
- A | @ | 185.199.110.153
- A | @ | 185.199.111.153
- CNAME | www | YOUR-GITHUB-USERNAME.github.io

Replace YOUR-GITHUB-USERNAME with your actual GitHub username. Remove conflicting `@` A records or `www` records, but do not delete unrelated mail records. DNS may take time to propagate. Enable **Enforce HTTPS** in GitHub Pages once available. GitHub's authoritative documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Notes
- Text buttons launch an SMS conversation with a prefilled message; customers must attach photos themselves in their messaging app.
- Static GitHub Pages cannot accept file uploads without an additional backend service.
- SEO is prepared for the local area, but search ranking is not guaranteed.
