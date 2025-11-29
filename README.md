# Social Media Scheduler - Legal Pages

This repository contains the legal and support pages for Social Media Scheduler.

## Pages Included

- **index.html** - Homepage with app overview
- **privacy-policy.html** - Privacy Policy
- **terms-of-service.html** - Terms of Service
- **support.html** - Support & FAQ page

## Setup on GitHub Pages

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Name it something like `social-scheduler-legal` or your app name
   - Make it **Public** (required for free GitHub Pages)

2. **Push these files to the repository**
   ```bash
   cd legal-pages
   git init
   git add .
   git commit -m "Initial commit - legal pages"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Select "Deploy from a branch"
   - Branch: Select `main` and `/ (root)`
   - Click Save

4. **Your URLs will be:**
   ```
   https://YOUR_USERNAME.github.io/YOUR_REPO/
   https://YOUR_USERNAME.github.io/YOUR_REPO/privacy-policy.html
   https://YOUR_USERNAME.github.io/YOUR_REPO/terms-of-service.html
   https://YOUR_USERNAME.github.io/YOUR_REPO/support.html
   ```

## Customization Required

Before publishing, update the following in each file:

### All Files
- Replace `support@yourdomain.com` with your actual email address

### Optional Customizations
- Update the app name if different from "Social Media Scheduler"
- Modify the color scheme in the CSS (currently purple gradient)
- Add your logo instead of the emoji
- Update the copyright year and entity name

## Using a Custom Domain (Optional)

1. Purchase a domain (e.g., from Namecheap, Google Domains, etc.)
2. Add a `CNAME` file to this repository containing your domain:
   ```
   www.yourdomain.com
   ```
3. Configure DNS settings at your domain registrar:
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
4. In GitHub repo Settings → Pages, enter your custom domain

## For TikTok Developer Portal

When submitting your app for review, use these URLs:

- **Privacy Policy URL:** `https://YOUR_USERNAME.github.io/YOUR_REPO/privacy-policy.html`
- **Terms of Service URL:** `https://YOUR_USERNAME.github.io/YOUR_REPO/terms-of-service.html`

## License

These templates are provided for use with your Social Media Scheduler application.
