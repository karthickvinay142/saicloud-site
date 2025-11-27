GitHub Pages Deployment (quick)
1. Initialize git in folder and push to GitHub:
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
2. In GitHub repo -> Settings -> Pages -> Choose main branch, root -> Save
3. Add custom domain: saicloudinfra.com in Pages settings or keep CNAME file
4. In Namecheap (or your DNS), add A records (four GitHub IPs) and CNAME for www -> <your-username>.github.io
5. Wait for DNS to propagate and enable HTTPS if available.
