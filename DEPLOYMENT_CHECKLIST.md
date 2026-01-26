# 🚀 Portfolio Deployment Checklist

Use this checklist to ensure everything is ready before deploying your portfolio.

## ✅ Phase 1: Required Files (Do These First!)

### JavaScript Libraries
- [ ] Download jQuery from: https://code.jquery.com/jquery-3.6.0.min.js
  - Save as: `assets/js/jquery.min.js`
- [ ] Download browser.min.js from: https://cdnjs.cloudflare.com/ajax/libs/jquery.browser/0.1.0/jquery.browser.min.js
  - Save as: `assets/js/browser.min.js`
- [ ] Download breakpoints.min.js and util.js from HTML5 UP Dimension template
  - OR use the CDN alternative in README

**QUICK FIX:** Instead of downloading, add these CDN links to `index.html` before `</body>`:
```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

### CSS Files
- [ ] Download Font Awesome from: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css
  - Save as: `assets/css/fontawesome-all.min.css`
  - Also download the webfonts folder

**QUICK FIX:** Add this to `<head>` in index.html:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

### Resume PDF
- [ ] Export your current resume as PDF
- [ ] Name it: `Alexandra_Lugo_Resume.pdf`
- [ ] Save it in: `assets/` folder

---

## ✅ Phase 2: Add Project Images

Create or gather these images and save them in the `images/` folder:

### Required Images:
- [ ] `bg.jpg` - Background image (abstract/tech-themed, 1920x1080px)
- [ ] `overlay.png` - Texture overlay (optional, can use a placeholder)
- [ ] `about-bg.jpg` - Professional photo or workspace (800x500px)
- [ ] `music-dna-map.jpg` - Regional Music DNA visualization screenshot
- [ ] `altristotle-demo.jpg` - Altristotle interface screenshot
- [ ] `velocityx-clusters.jpg` - VeloCityX clustering visualization
- [ ] `sallie-mae-governance.jpg` - Data governance dashboard/workflow

### Image Tips:
- Use screenshots from your actual projects
- Keep file sizes under 500KB (compress at tinypng.com)
- Format: JPG for photos, PNG for screenshots with text
- Dimensions: 800-1200px width is perfect

### Where to Find Placeholders (if needed):
- Unsplash.com (search: "data visualization", "tech workspace")
- Your own project repos (take screenshots of notebooks/dashboards)
- Canva (create simple visuals if projects don't have images yet)

---

## ✅ Phase 3: Customize Content

### Update Links in index.html:
- [ ] Line ~145: Regional Music DNA GitHub link
- [ ] Line ~168: Altristotle GitHub link  
- [ ] Line ~191: VeloCityX GitHub link
- [ ] Verify all project descriptions match your actual work

### Double-Check Contact Info:
- [ ] Email: alexandranlugo@gmail.com ✓
- [ ] Phone: (786) 566-6465 ✓
- [ ] LinkedIn: linkedin.com/in/lugoalexandra/ ✓
- [ ] GitHub: github.com/alexandranlugo ✓

---

## ✅ Phase 4: GitHub Repository Setup

### Create Repo:
- [ ] Go to github.com/new
- [ ] Name: `alexandranlugo.github.io` (this is important for custom domain!)
- [ ] Make it Public
- [ ] Don't initialize with README (you already have one)

### Push Your Code:
```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/alexandranlugo/alexandranlugo.github.io.git
git push -u origin main
```

- [ ] Code is pushed to GitHub
- [ ] Repository is public
- [ ] Check files loaded correctly online

---

## ✅ Phase 5: Deploy to GitHub Pages

### Enable GitHub Pages:
- [ ] Go to repo Settings → Pages
- [ ] Source: Deploy from branch `main` / `root`
- [ ] Click Save
- [ ] Wait 2-3 minutes
- [ ] Test site at: `https://alexandranlugo.github.io`

### Connect Custom Domain:
- [ ] In GitHub: Settings → Pages → Custom domain
- [ ] Enter: `alexandralugo.com`
- [ ] Check "Enforce HTTPS"
- [ ] In your domain registrar (where you bought the domain):
  - [ ] Add CNAME record: `alexandranlugo.github.io`
  - [ ] OR add A records:
    ```
    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153
    ```
- [ ] Wait 10-30 minutes for DNS propagation
- [ ] Test at: `https://alexandralugo.com`

---

## ✅ Phase 6: Quality Checks

### Test on Devices:
- [ ] Desktop (Chrome)
- [ ] Desktop (Safari/Firefox)
- [ ] Mobile (iPhone)
- [ ] Mobile (Android)
- [ ] Tablet (iPad)

### Check Functionality:
- [ ] All navigation links work
- [ ] Projects open/close smoothly
- [ ] Resume downloads correctly
- [ ] All external links work (LinkedIn, GitHub)
- [ ] Images load properly
- [ ] No broken layouts

### Content Review:
- [ ] Proofread all text (use Grammarly)
- [ ] Check for typos in project descriptions
- [ ] Verify all technical terms are spelled correctly
- [ ] Ensure all numbers/stats are accurate

### Performance:
- [ ] Site loads in under 3 seconds
- [ ] Images are compressed (under 500KB each)
- [ ] No console errors (check with F12)

---

## ✅ Phase 7: Go Live!

### Update Your Materials:
- [ ] Add `alexandralugo.com` to resume header
- [ ] Update LinkedIn profile with portfolio link
- [ ] Add to email signature (optional)
- [ ] Update cover letter template

### Announce It:
- [ ] LinkedIn post about new portfolio
- [ ] Tell your network (professors, mentors, friends)
- [ ] Share in NYU career groups/Slack channels

### Job Applications:
- [ ] Include portfolio link in applications
- [ ] Add to "Additional Materials" sections
- [ ] Mention in cover letters

---

## ⏱️ Time Estimate Breakdown

- **Phase 1-2** (Files & Images): 2 hours
- **Phase 3** (Customization): 1 hour  
- **Phase 4-5** (Deployment): 1 hour
- **Phase 6** (Testing): 1 hour
- **Phase 7** (Launch): 30 minutes

**Total: ~5.5 hours** (spread over 2-3 days is ideal)

---

## 🆘 If You Get Stuck

**Quick Wins:**
1. Use CDN links instead of downloading files (faster!)
2. Use placeholder images from Unsplash temporarily
3. Deploy to Netlify instead of GitHub Pages (easier DNS)

**Common Issues:**
- **Images not showing**: Check file paths, file names must match exactly
- **Site not loading**: Wait 24 hours for DNS, try incognito mode
- **JavaScript errors**: Use CDN links from README
- **Mobile looks broken**: Make sure viewport tag is in `<head>`

---

## 🎉 Success Criteria

You'll know you're ready when:
1. ✅ Site loads at alexandralugo.com on all devices
2. ✅ All 4 projects have images and descriptions
3. ✅ Resume downloads when clicking the button
4. ✅ Navigation works smoothly (no errors)
5. ✅ You've shared it with at least 3 people for feedback

---

**You've got this! 🚀**

Each checkbox completed gets you closer to standing out in the job market. Take it one step at a time, and don't hesitate to ask for help if needed.

Good luck!
