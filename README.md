# Zi Wang - Personal Website

This is the personal website for Zi Wang, Research Engineer at NVIDIA.

## 🚀 Quick Start

This website is built using plain HTML, CSS, and JavaScript. No build process is required!

### Local Development

Simply open `index.html` in your web browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then visit `http://localhost:8000` in your browser.

## 📝 Customization Guide

### 1. Profile Picture

Replace `/images/profile.jpg` with your own profile picture. For best results:
- Use a square image (e.g., 500x500px)
- JPG or PNG format
- The image will be displayed as a circle

### 2. Personal Information

Edit `index.html` to update:
- **Name**: Line 57-58
- **Title/Affiliation**: Lines 67-72
- **Email**: Line 74-76
- **Introduction**: Lines 139-143

### 3. Social Media Links

Update social media links (lines 98-129):
- Google Scholar
- GitHub
- Twitter
- LinkedIn
- CV (replace `cv.pdf` with your own PDF)

### 4. Research Interests

Edit the interests list (lines 157-173)

### 5. Education

Modify education entries (lines 183-263)

### 6. News Section

Add/edit news items (lines 290-393)

### 7. Publications

Edit publications starting at line 439. Each publication follows this structure:

```html
<div class="publication row w-100">
    <div class="section-1 w-100">
        <span>Paper Title,</span>
        <span class="text-muted publication-date">Year,</span>
        <span class="text-muted publication-name">Venue</span>
    </div>
    <div class="section-2 text-muted w-100">
        <!-- Authors -->
    </div>
    <div class="section-3 w-100">
        <!-- Links: pdf, code, website, etc. -->
    </div>
</div>
```

### 8. Experience Section

Edit work experience entries following the same structure as publications.

### 9. Styling

To change colors and fonts, edit `/css/style.css`:
- Main color (gold): `#E8B004` 
- Hover color (pink): `#EFAFAD`
- Text color: `#071013`

## 📁 File Structure

```
zi_wang.github.io/
├── index.html          # Main HTML file
├── cv.pdf             # Your CV (replace this)
├── README.md          # This file
├── css/
│   └── style.css      # Stylesheet
└── images/
    └── profile.jpg    # Profile picture (replace this)
```

## 🌐 Deployment

### GitHub Pages

1. Create a repository named `username.github.io` (replace `username` with your GitHub username)
2. Push this code to the repository
3. Your site will be live at `https://username.github.io`

### Custom Domain

If you want to use a custom domain:
1. Create a file named `CNAME` in the root directory
2. Add your domain name to it (e.g., `www.yourname.com`)
3. Configure DNS settings with your domain provider

## 📦 Dependencies

This website uses:
- [Bootstrap 4.5.3](https://getbootstrap.com/) - CSS framework
- [Feather Icons](https://feathericons.com/) - Icon set
- [Academicons](https://jpswalsh.github.io/academicons/) - Academic icons
- [Google Fonts](https://fonts.google.com/) - Typography

All dependencies are loaded via CDN, so no installation is required.

## 📄 License

Template based on [Avicenna](https://github.com/hadisinaee/avicenna) (MIT License)

## 🤝 Credits

- Original template by Qingwei Ben: [elgce.github.io](https://elgce.github.io)
- Template design: [Avicenna](https://github.com/hadisinaee/avicenna)

