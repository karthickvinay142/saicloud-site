SAI Cloud Infra - Website Package
Files included:
- index.html, about.html, services.html, experience.html, certifications.html, contact.html
- css/style.css
- assets/logo.svg
- CNAME (saicloudinfra.com)
- docs/deploy_github_pages.md

How to deploy:
1. Create a GitHub repository and push these files to the repository root.
2. Enable GitHub Pages (branch: main, folder: / (root)).
3. Add CNAME as shown to set custom domain. Add A records in your DNS provider pointing to GitHub Pages IPs:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   and add CNAME for 'www' to point to <your-github-username>.github.io
4. Optionally enable HTTPS in Pages settings after DNS propagates.
Notes:
- For local testing, remove leading slash in CSS and asset paths (use relative paths: css/style.css and assets/logo.svg).
- Contact form uses mailto:. For production consider Formspree or Netlify forms.
