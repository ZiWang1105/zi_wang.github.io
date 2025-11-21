# Quick Start Guide 🚀

## What's Been Created

Your personal website has been generated based on the `elgce.github.io` template and populated with information from your resume. Here's what you have:

### ✅ Complete Website Structure
- **Main page** (`index.html`) with all your information
- **Professional styling** (`css/style.css`) with gold/yellow theme
- **Profile section** with photo, name, title, and links
- **12 publications** from your resume
- **4 work experiences** (NVIDIA, CMU, SJTU)
- **Education section** (CMU MS, SJTU BS)
- **News section** with recent highlights
- **Competitions & Skills** sections

### 📁 Files Created
```
zi_wang.github.io/
├── index.html           ✅ Main website page
├── README.md            ✅ Detailed documentation
├── DEPLOYMENT.md        ✅ GitHub Pages deployment guide
├── QUICKSTART.md        ✅ This file!
├── CNAME                ✅ Domain configuration
├── .gitignore           ✅ Git configuration
├── cv.pdf               ⚠️  Replace with your CV!
├── css/
│   └── style.css        ✅ Styling
└── images/
    └── profile.jpg      ⚠️  Replace with your photo!
```

## 🎯 Next Steps (5 Minutes)

### 1. Preview Your Site Locally

A local server is already running! Visit:
**http://localhost:8888**

### 2. Replace Important Files

```bash
# Replace profile photo (use a square image, ~500x500px)
cp /path/to/your/photo.jpg /home/ziwang/projects/zi_wang.github.io/images/profile.jpg

# Replace CV
cp /path/to/your/cv.pdf /home/ziwang/projects/zi_wang.github.io/cv.pdf
```

### 3. Update Social Media Links

Edit `index.html` around lines 98-129 to add your actual URLs:
- Google Scholar profile
- GitHub profile  
- Twitter/X profile
- LinkedIn profile

### 4. Customize (Optional)

- **Colors**: Edit `css/style.css` to change the gold theme
- **Content**: Edit `index.html` to add/remove sections
- **Introduction**: Update the "About Me" paragraph (line ~142)

## 🌐 Deploy to GitHub Pages (10 Minutes)

### Simple 3-Step Process:

```bash
cd /home/ziwang/projects/zi_wang.github.io

# 1. Initialize git
git init
git add .
git commit -m "Initial commit: Personal website"

# 2. Create repository on GitHub named: YOUR-USERNAME.github.io
# (Do this at github.com/new)

# 3. Push to GitHub (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git branch -M main
git push -u origin main
```

**Your site will be live at:** `https://YOUR-USERNAME.github.io` (within 5-10 minutes)

See `DEPLOYMENT.md` for detailed instructions.

## 📝 Quick Edits Guide

### Update Publications

Find the publications section in `index.html` (around line 439) and add/edit entries:

```html
<div class="publication row w-100">
    <div class="section-1 w-100">
        <span>Your Paper Title,</span>
        <span class="text-muted publication-date">2025,</span>
        <span class="text-muted publication-name">Conference Name</span>
    </div>
    <div class="section-2 text-muted w-100">
        <span>Author One</span>
        <span class="separator">,</span>
        <span>Author Two</span>
    </div>
    <div class="section-3 w-100">
        <a class="main_color text-decoration-none rounded" 
           href="URL" target="_blank">pdf</a>
    </div>
</div>
```

### Update News

Add news items around line 290:

```html
<li>
    <i data-feather="file-text"></i>
    <a href="URL">Your News Title</a>
    <span class="secondary_font text-muted">, Month Year.</span>
</li>
```

### Change Colors

In `css/style.css`:
- Line 8: `#E8B004` (main gold color)
- Line 13: `#EFAFAD` (hover pink color)
- Line 51-52: Modify theme colors

## 🔍 What's Included from Your Resume

### ✅ Publications (12 papers)
1. VIRAL (In Submission) - with Tairan He et al.
2. Opening the Sim-to-Real Door (In Submission)
3. Collision Scenario Integration (IROS 2025 Oral)
4. Editable Scene Simulation (CVPR 2024 Highlight)
5. TBP-Former (CVPR 2023)
6. SONIC (In Submission)
7. ASAP (RSS 2025)
8. DriveSuprim (AAAI 2026)
9. Generalized Trajectory Scoring (Technical Report)
10. ZTRS (In Submission)
11. DialogueNeRF (Visual Intelligence)
12. Interruption-Aware Cooperative Perception (IEEE TIV)

### ✅ Experience
- NVIDIA (Full Time, Feb 2025 - Present)
- NVIDIA Intern (May 2024 - Aug 2024)
- CMU Research Assistant (Jan 2024 - Dec 2024)
- SJTU Research Assistant (Mar 2022 - Nov 2023)

### ✅ Education
- Carnegie Mellon University (MS Computer Vision, GPA: 4.0/4.0)
- Shanghai Jiao Tong University (BS AI, GPA: 89/100)

### ✅ Achievements
- 1st Place: CVPR E2E Autonomous Driving Challenge (2025)
- 2nd Place: LJ Cup Infrared Object Detection (2021)

### ✅ Skills
- Programming: Python, C/C++, Matlab, ROS, PyTorch, TensorFlow
- Robots: Unitree G1, H1
- Tools: Git, LaTeX, Docker, Ubuntu
- Simulators: MuJoCo, IsaacGym/Sim/Lab

## 📚 Documentation

- **README.md** - Comprehensive customization guide
- **DEPLOYMENT.md** - Detailed deployment instructions
- **QUICKSTART.md** - This file (quick reference)

## ⚠️ Important Notes

1. **Profile Photo**: Currently using a placeholder - MUST replace!
2. **CV File**: Currently using template's CV - MUST replace!
3. **Social Links**: Update with your actual profile URLs
4. **Testing**: Always test locally before deploying
5. **Mobile**: Site is responsive and mobile-friendly

## 🎨 Template Credits

- **Original Template**: [Avicenna](https://github.com/hadisinaee/avicenna) (MIT License)
- **Reference Site**: [elgce.github.io](https://elgce.github.io) by Qingwei Ben
- **Framework**: Bootstrap 4.5.3
- **Icons**: Feather Icons + Academicons

## 🆘 Need Help?

1. **Local Preview**: http://localhost:8888 (already running!)
2. **Template Issues**: Check `README.md`
3. **Deployment Issues**: Check `DEPLOYMENT.md`
4. **GitHub Pages Docs**: https://docs.github.com/en/pages

## 🎉 You're All Set!

Your professional academic website is ready. Just replace the profile photo and CV, then deploy to GitHub Pages. Good luck! 🚀

---

**Created**: November 21, 2025  
**For**: Zi Wang (wang.zi2865@gmail.com)  
**Local Preview**: http://localhost:8888

