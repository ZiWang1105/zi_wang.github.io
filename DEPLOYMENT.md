# Deployment Guide

## Quick Links
- **Template Source**: [elgce.github.io](https://elgce.github.io)
- **Created**: November 2025
- **For**: Zi Wang's Personal Website

## Step-by-Step GitHub Pages Deployment

### 1. Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the `+` icon in the top right → "New repository"
3. **Important**: Name it `<your-username>.github.io`
   - Example: If your GitHub username is `ziwang`, name it `ziwang.github.io`
4. Set it to **Public**
5. Do **NOT** initialize with README (we already have files)
6. Click "Create repository"

### 2. Push Your Code

```bash
cd /home/ziwang/projects/zi_wang.github.io

# Initialize git repository
git init

# Add all files
git add .

# Make first commit
git commit -m "Initial commit: Personal website"

# Add remote (replace YOUR-USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait a few minutes for deployment

Your site will be live at: `https://<your-username>.github.io`

## Custom Domain Setup (Optional)

If you own a custom domain (e.g., `www.ziwang.com`):

### Update CNAME File

Edit the `CNAME` file in your repository:

```
www.yourname.com
```

### Configure DNS

Add these records with your domain provider:

**For apex domain (yourname.com):**
```
Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

**For www subdomain:**
```
Type: CNAME
Name: www
Value: your-username.github.io.
```

## Updating Your Site

After making changes:

```bash
git add .
git commit -m "Update content"
git push
```

Changes will appear within a few minutes.

## Before You Deploy - Checklist

- [ ] Replace `images/profile.jpg` with your photo
- [ ] Replace `cv.pdf` with your actual CV
- [ ] Update social media links with your actual URLs
- [ ] Update email and contact information
- [ ] Review all publications for accuracy
- [ ] Check all external links work correctly
- [ ] Test locally before pushing
- [ ] Update CNAME with your domain (if using custom domain)

## Testing Locally

```bash
cd /home/ziwang/projects/zi_wang.github.io

# Option 1: Python 3
python3 -m http.server 8000

# Option 2: Python 2
python -m SimpleHTTPServer 8000

# Option 3: PHP
php -S localhost:8000

# Option 4: Node.js (if you have it)
npx http-server -p 8000
```

Then visit: http://localhost:8000

## Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after first push
- Check GitHub Pages settings
- Verify repository name is correct: `username.github.io`

### Images Not Showing
- Check file paths (should be `/images/profile.jpg`)
- Ensure images are committed to git
- Try clearing browser cache

### Custom Domain Not Working
- Verify DNS records are correct
- Allow 24-48 hours for DNS propagation
- Check CNAME file exists and has correct domain

## Maintenance Tips

1. **Regular Updates**: Update your publications and news regularly
2. **Broken Links**: Check links periodically
3. **Analytics**: Consider adding Google Analytics
4. **SEO**: Update meta tags in `<head>` section
5. **Backup**: Keep a local backup of your site

## Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Custom Domain Guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/)
- [Feather Icons](https://feathericons.com/)

## Support

For issues with:
- **GitHub Pages**: [GitHub Support](https://support.github.com)
- **Template**: Check [Avicenna GitHub](https://github.com/hadisinaee/avicenna)
- **This Website**: Contact wang.zi2865@gmail.com

