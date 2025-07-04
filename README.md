# lettersforjustice.github.io
# #JoeysLaw Website

Official campaign site advocating for justice for Joseph Lagerman.

---

## Hosted on GitHub Pages

Current URL:  
[https://lettersforjustice.github.io](https://lettersforjustice.github.io)

---

## Custom Domain Setup

We’ve configured the custom domain:  
**josephs-law.space**

### GitHub Pages Configuration

1. Ensure a `CNAME` file exists at the repository root containing:
2. Go to **Settings > Pages** and confirm the custom domain is set to `josephs-law.space`.
3. Make sure the site is published from the `main` branch (or whichever branch you use for deployment).

---

## DNS Settings (at your domain registrar)

- **CNAME record**  
- Host: `www`  
- Points to: `lettersforjustice.github.io`

- **A records** (for root domain `@`)  
- 185.199.108.153  
- 185.199.109.153  
- 185.199.110.153  
- 185.199.111.153

- **Optional URL Redirect Record**  
- Redirect root domain `@` → `http://www.josephs-law.space`

---

## Accessing the Site

- GitHub Pages (default):  
[https://lettersforjustice.github.io](https://lettersforjustice.github.io)

- Custom Domain:  
[https://josephs-law.space](https://josephs-law.space)  
[https://www.josephs-law.space](https://www.josephs-law.space)

---

## Troubleshooting

- DNS changes may take 24–48 hours to propagate.
- If you see a GitHub 404 page, check:
- Your DNS records
- Your GitHub Pages settings
- The `CNAME` file (must exactly match your domain)

---

## How to Update the Website

- Edit your HTML, CSS, or content files in the GitHub repo.
- Commit and push changes to your deployment branch (`main` by default).
- GitHub Pages will automatically rebuild and publish your site.

---

Thanks for supporting **#JoeysLaw**.
