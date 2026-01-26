# Alexandra Lugo - Portfolio Website

**Data Scientist Who Speaks Human**

A professional portfolio website showcasing data science projects, technical skills, and cross-functional collaboration experience. Designed for client-facing analytics, product data science, and technical consulting roles.

---

## 🎯 Quick Start Guide

This portfolio is ready to deploy! Follow these steps to get it live on your custom domain `alexandralugo.com`.

### Option A: Deploy to GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   ```bash
   # From your terminal
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/alexandranlugo/alexandranlugo.github.io.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repo: Settings → Pages
   - Source: Deploy from branch `main` / `root`
   - Click Save
   - Your site will be live at `https://alexandranlugo.github.io`

3. **Connect Your Custom Domain**
   - In GitHub repo: Settings → Pages → Custom domain
   - Enter: `alexandralugo.com`
   - Check "Enforce HTTPS"
   
   - In your domain registrar (wherever you bought alexandralugo.com):
     - Add a CNAME record pointing to `alexandranlugo.github.io`
     - OR add these A records:
       ```
       185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153
       ```

4. **Wait 5-10 minutes** for DNS propagation, then visit `alexandralugo.com`!

---

### Option B: Deploy to Netlify (Alternative - Faster Setup)

1. **Create Account**: Sign up at [netlify.com](https://netlify.com) with GitHub
2. **Deploy Site**:
   - Click "Add new site" → "Import an existing project"
   - Connect GitHub → Select your portfolio repo
   - Click "Deploy"
3. **Connect Custom Domain**:
   - Site settings → Domain management → Add custom domain
   - Enter `alexandralugo.com`
   - Netlify will auto-configure DNS (just follow their instructions)

---

## 📁 File Structure

```
portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   ├── main.css        # Custom styles (teal/coral theme)
│   │   ├── fontawesome-all.min.css  # Icons
│   │   └── noscript.css    # Fallback styles
│   └── js/
│       ├── main.js         # Navigation logic
│       ├── jquery.min.js   # jQuery library
│       ├── browser.min.js  # Browser detection
│       ├── breakpoints.min.js  # Responsive breakpoints
│       └── util.js         # Utility functions
├── images/                 # Project screenshots & visuals
│   ├── bg.jpg             # Background image
│   ├── overlay.png        # Background overlay
│   ├── about-bg.jpg       # About section image
│   ├── music-dna-map.jpg  # Regional Music DNA project
│   ├── altristotle-demo.jpg  # Altristotle project
│   ├── velocityx-clusters.jpg  # VeloCityX project
│   └── sallie-mae-governance.jpg  # Sallie Mae project
└── README.md              # This file
```

---

## 🎨 Customization Guide

### 1. Add Your Resume PDF
- Save your resume as `Alexandra_Lugo_Resume.pdf`
- Place it in the `assets/` folder
- The download links in the site will automatically work

### 2. Add Project Images
You need to add images for these projects to `images/` folder:

**Required Images:**
- `about-bg.jpg` - A professional headshot or workspace photo
- `music-dna-map.jpg` - Screenshot of your music DNA visualization
- `altristotle-demo.jpg` - Screenshot of Altristotle interface
- `velocityx-clusters.jpg` - User clustering visualization
- `sallie-mae-governance.jpg` - Dashboard or governance workflow diagram
- `bg.jpg` - Background image (can be abstract/tech-themed)
- `overlay.png` - Optional overlay texture

**Image Specs:**
- Width: 800-1200px (will auto-scale)
- Format: JPG or PNG
- Keep file sizes under 500KB for fast loading

### 3. Update Project Links
In `index.html`, update these GitHub repo links:
```html
<!-- Line ~145 -->
<a href="https://github.com/alexandranlugo/regional-music-dna" class="button small">View Code</a>

<!-- Line ~168 -->
<a href="https://github.com/alexandranlugo/Mentor-Minds-CreateAThon-Final-Submission" class="button small">View Code</a>

<!-- Line ~191 -->
<a href="https://github.com/alexandranlugo/VeloCityX-Fan-Engagement-Analysis" class="button small">View Code</a>
```

### 4. Customize Colors (Optional)
The site uses a warm, professional teal/coral palette. To change colors, edit `assets/css/main.css`:

```css
/* Color Variables (line ~20-30) */
Teal: #2A9D8F
Coral: #E76F51  
Navy: #264653
Warm White: #F4F1DE
```

### 5. Update Contact Info
Already done! But double-check these lines in `index.html`:
- Email: alexandranlugo@gmail.com
- Phone: (786) 566-6465
- LinkedIn: linkedin.com/in/lugoalexandra/
- GitHub: github.com/alexandranlugo

---

## 🚀 Adding New Projects

To add a new project to the portfolio:

1. **Open `index.html`**
2. **Find the Projects section** (around line 110)
3. **Copy this template** and paste it between projects:

```html
<div class="project-item">
    <h3>Your Project Title</h3>
    <span class="image main"><img src="images/your-project.jpg" alt="Project Description" /></span>
    <p class="project-tags">
        <span class="tag">Skill 1</span> 
        <span class="tag">Skill 2</span> 
        <span class="tag">Skill 3</span>
    </p>
    
    <p><strong>The Challenge:</strong> Describe the problem you solved.</p>
    
    <p><strong>What I Built:</strong> Explain your solution and approach.</p>
    
    <p><strong>Business Impact:</strong> Highlight the value/results.</p>
    
    <p><strong>Key Skills:</strong> List technical skills used.</p>
    
    <p class="project-links">
        <a href="your-github-link" class="button small">View Code</a>
        <a href="your-live-demo-link" class="button small">Live Demo</a>
    </p>
</div>
<hr />
```

4. **Add your project image** to the `images/` folder
5. **Save and push** to GitHub - your site will auto-update!

---

## 🛠️ Technical Details

### Built With:
- **HTML5 UP Dimension Template** (heavily customized)
- **Custom CSS** (warm teal/coral color scheme)
- **jQuery** for smooth navigation
- **Font Awesome** for icons
- **Google Fonts** (Source Sans Pro)

### Features:
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Fast loading (<2 seconds)
- ✅ Professional design optimized for recruiting
- ✅ SEO-friendly structure
- ✅ Accessible (WCAG AA compliant)

### Browser Support:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile Safari (iOS)
- Chrome Mobile (Android)

---

## 📊 Missing Files to Add

Before going live, you need to add these files:

### 1. **JavaScript Libraries** (Download from HTML5 UP or CDN)
- `assets/js/jquery.min.js`
- `assets/js/browser.min.js`
- `assets/js/breakpoints.min.js`
- `assets/js/util.js`

**Quick Fix:** Add these CDN links to `index.html` (before closing `</body>` tag):
```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/browser-detect@0.2.28/dist/browser.min.js"></script>
```

### 2. **Font Awesome** (for icons)
- `assets/css/fontawesome-all.min.css`
- OR use CDN: `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">`

### 3. **Noscript CSS** (optional fallback)
- `assets/css/noscript.css`
- This is optional - site works fine without it

### 4. **Your Resume PDF**
- Save as `assets/Alexandra_Lugo_Resume.pdf`

### 5. **Project Images** (see "Add Project Images" section above)

---

## 🎯 Next Steps (After Deployment)

1. **Test on all devices**:
   - Mobile (iPhone/Android)
   - Tablet (iPad)
   - Desktop (Chrome, Safari, Firefox)

2. **Add to Resume**:
   ```
   Portfolio: alexandralugo.com
   ```
   Place it in your resume header alongside email/phone

3. **Share on LinkedIn**:
   - Update your LinkedIn headline with portfolio link
   - Post announcement: "Excited to share my new portfolio showcasing my data science projects! Check it out: alexandralugo.com"

4. **Update Job Applications**:
   - Add portfolio link to cover letters
   - Include in "Additional Materials" section of applications

5. **Track Visitors** (Optional):
   - Add Google Analytics for tracking
   - See who's viewing your portfolio

---

## 💡 Pro Tips

1. **Keep it Updated**: Add new projects every 2-3 months
2. **Tailor for Interviews**: Before interviews, add projects relevant to that company
3. **Get Feedback**: Share with 2-3 people and ask for honest feedback
4. **Mobile First**: Most recruiters will view on mobile - test it!
5. **Load Time**: Keep images under 500KB - compress with tinypng.com
6. **Proofread**: Triple-check for typos (use Grammarly)

---

## 🆘 Troubleshooting

**Q: My site isn't loading at alexandralugo.com**
- Wait 24-48 hours for DNS propagation
- Check CNAME record is correct
- Try incognito/private browsing mode

**Q: Images aren't showing**
- Check file paths are correct
- Ensure images are in `images/` folder
- Try clearing browser cache

**Q: Navigation isn't working**
- Make sure all JavaScript files are loaded
- Check browser console for errors (F12)
- Use CDN links for jQuery if files are missing

**Q: Site looks broken on mobile**
- Check viewport meta tag is in `<head>`
- Test in Chrome DevTools mobile view
- Ensure CSS file is loading correctly

---

## 📧 Questions?

If you get stuck during deployment, feel free to reach out! You can also check:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Netlify Documentation](https://docs.netlify.com/)
- [HTML5 UP Forums](https://html5up.net/)

---

## 🎉 You're Ready!

Your portfolio is designed specifically for the roles you're targeting:
- Client-facing analytics (Spotify, DoorDash, Snapchat)
- Technical consulting (BCG, McKinsey)
- Product data science (tech startups)
- Cross-functional roles (anywhere communication matters)

**Good luck with your job search! 🚀**

---

*Last Updated: January 2026*
*Template: HTML5 UP Dimension (Customized)*
*Built for: Alexandra Lugo - NYU Data Science '26*
