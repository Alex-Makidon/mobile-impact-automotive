# Mobile Impact Automotive — Website

A lightweight, fast static site ready for GitHub Pages.

## Quick Start
1. Create a new public repo named **`mobile-impact-automotive`**.
2. Upload all files from this folder (or drag-drop the ZIP contents).
3. In GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
4. Select `main` as the branch and `/ (root)` for the folder. Save.
5. The site will be live at `https://<your-username>.github.io/mobile-impact-automotive/`.

## Custom Domain
1. Buy a domain (e.g., `mobileimpactauto.com`).
2. In **Settings → Pages → Custom domain**, enter `www.yourdomain.com`.
3. At your domain registrar, add DNS:  
   - `www` CNAME → `<your-username>.github.io`  
   - Apex `@` A → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
4. Back in GitHub Pages, check **Enforce HTTPS**.

## Edit Content
- **Logo:** replace `assets/logo.svg` and `assets/logo.png` with your final files.
- **Hero:** edit the headline and service line in `index.html`.
- **Services/Reviews:** update the cards, add more as needed.
- **Contact form:** replace the Formspree action with your form endpoint.
- **Map:** `iframe` already points to the Snellville address.
- **SEO:** Update the `og:image`, `robots.txt` domain, and `sitemap.xml` domain.

## Optional
- Add a `CNAME` file with `www.yourdomain.com` to lock the domain in the repo.
- Use Cloudflare Email Routing or Google Workspace for `info@yourdomain.com`.

---

Built with semantic HTML + small CSS for speed. No build step required.
