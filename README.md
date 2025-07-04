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
2. Verify in **Settings > Pages** that the custom domain is set to `josephs-law.space`.  
3. The site is published from the `main` branch (or your chosen deployment branch).

---

## DNS Settings (at your domain registrar)

- **CNAME record**  
Host: `www`  
Points to: `lettersforjustice.github.io`

- **A records** (for root domain `@`):  
- 185.199.108.153  
- 185.199.109.153  
- 185.199.110.153  
- 185.199.111.153  

- **Optional URL Redirect Record**  
Redirect root domain `@` → `http://www.josephs-law.space`

---

## Accessing the Site

- GitHub Pages default:  
[https://lettersforjustice.github.io](https://lettersforjustice.github.io)

- Custom domain URLs:  
[https://josephs-law.space](https://josephs-law.space)  
[https://www.josephs-law.space](https://www.josephs-law.space)

---

## Troubleshooting

- DNS changes may take 24-48 hours to propagate.  
- If you see a GitHub 404 error, check your GitHub Pages settings and DNS records.  
- Make sure your `CNAME` file exactly matches your custom domain.

---

## How to Update the Website

- Edit HTML, CSS, or content files in the repository.  
- Commit and push changes to the deployment branch (`main` by default).  
- GitHub Pages auto-builds and publishes your updates.

---

Thanks for supporting **#JoeysLaw**!
