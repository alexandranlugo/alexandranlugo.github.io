# 🚀 QUICK START: Get Your Portfolio Live in 30 Minutes

**Goal**: Get `alexandralugo.com` live with a professional portfolio ASAP.

---

## ⏱️ 30-Minute Launch Plan

### ✅ Minutes 0-10: Add Essential Files

1. **Add Your Resume**
   - Export your resume as PDF
   - Name it: `Alexandra_Lugo_Resume.pdf`
   - Save in `assets/` folder

2. **Add Placeholder Images**
   - Go to Unsplash.com
   - Download 3 images:
     - Search "technology background" → save as `images/bg.jpg`
     - Search "workspace" → save as `images/about-bg.jpg`  
     - Search "data visualization" → save as `images/music-dna-map.jpg`
   - Copy same image for other projects temporarily:
     ```bash
     cp images/music-dna-map.jpg images/altristotle-demo.jpg
     cp images/music-dna-map.jpg images/velocityx-clusters.jpg
     cp images/music-dna-map.jpg images/sallie-mae-governance.jpg
     ```

**Status Check**: You now have all required files! ✅

---

### ✅ Minutes 10-20: Push to GitHub

```bash
# Initialize Git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Create GitHub repo (do this at github.com/new)
# Name: alexandranlugo.github.io
# Make it Public

# Connect and push
git branch -M main
git remote add origin https://github.com/alexandranlugo/alexandranlugo.github.io.git
git push -u origin main
```

**Status Check**: Code is on GitHub! ✅

---

### ✅ Minutes 20-25: Enable GitHub Pages

1. Go to: `https://github.com/alexandranlugo/alexandranlugo.github.io`
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar)
4. Under "Source": Select `main` branch, `/ (root)` folder
5. Click **Save**
6. Wait 2 minutes
7. Visit: `https://alexandranlugo.github.io`

**Status Check**: Site is live on GitHub Pages! ✅

---

### ✅ Minutes 25-30: Connect Custom Domain

#### In GitHub:
1. Settings → Pages → Custom domain
2. Enter: `alexandralugo.com`
3. Check **Enforce HTTPS**
4. Click **Save**

#### In Your Domain Registrar:
(Wherever you bought alexandralugo.com - GoDaddy, Namecheap, etc.)

**Option A - CNAME (Easier):**
```
Type: CNAME
Name: www
Value: alexandranlugo.github.io
```

**Option B - A Records (More Reliable):**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A  
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

**Status Check**: Domain configured! ✅

Wait 10-30 minutes for DNS to propagate, then visit `alexandralugo.com`

---

## 🎉 You're Live!

Your portfolio is now accessible at:
- ✅ `https://alexandralugo.com`
- ✅ `https://www.alexandralugo.com`  
- ✅ `https://alexandranlugo.github.io`

---

## 📋 Post-Launch Checklist

### Immediate (Do Today):
- [ ] Test site on mobile phone
- [ ] Test site on desktop browser
- [ ] Click all navigation links
- [ ] Download resume to verify PDF works
- [ ] Check that external links (LinkedIn, GitHub) work

### This Week:
- [ ] Add real project screenshots (replace placeholders)
- [ ] Add professional photo to About section
- [ ] Proofread all text for typos
- [ ] Get feedback from 2-3 people
- [ ] Update resume to include portfolio link

### Update Your Materials:
```
Resume Header:
Portfolio: alexandralugo.com

LinkedIn Summary:
Check out my portfolio: alexandralugo.com

Email Signature:
Alexandra Lugo | Data Scientist
alexandralugo.com
```

---

## 🔧 Troubleshooting

**Q: Site isn't loading at alexandralugo.com**
- Wait 24-48 hours for DNS propagation
- Try incognito/private browsing mode
- Clear browser cache (Cmd/Ctrl + Shift + R)

**Q: Images aren't showing**
- Make sure images are in `images/` folder
- Check file names match exactly (case-sensitive!)
- Push changes to GitHub: `git add . && git commit -m "Add images" && git push`

**Q: Resume download not working**
- Ensure PDF is named exactly: `Alexandra_Lugo_Resume.pdf`
- Make sure it's in `assets/` folder
- Push to GitHub

**Q: Navigation broken**
- Check browser console (F12) for JavaScript errors
- Ensure all JavaScript files are present
- Try refreshing the page

**Q: Site looks broken on mobile**
- Give it time - GitHub Pages needs to rebuild (5-10 mins)
- Try a different browser
- Clear cache and try again

---

## 💡 Pro Tips

1. **Don't Wait for Perfect**: Launch with placeholder images, improve later
2. **Mobile First**: Most recruiters view on mobile - test there first
3. **Keep Updating**: Add new projects every 2-3 months
4. **Track Visits**: Add Google Analytics later to see who's visiting
5. **Share Everywhere**: LinkedIn, resume, email signature, job applications

---

## 🎯 What's Next?

Now that your portfolio is live:

1. **Update job applications** - Add portfolio link to every application
2. **Post on LinkedIn** - Share your new portfolio with network
3. **Email mentors/professors** - Ask for feedback
4. **Apply to dream jobs** - You're now more competitive!

---

## 📧 Support

If you get stuck:
- Check `README.md` for detailed instructions
- Check `DEPLOYMENT_CHECKLIST.md` for step-by-step guide
- Check `IMAGE_GUIDE.md` for image help
- Search GitHub Issues for common problems

---

**Congratulations! Your portfolio is live! 🎉**

Now go apply to those dream jobs at Spotify, BCG, DoorDash, and everywhere else. You've got a professional portfolio that showcases your skills - time to put it to work!

Good luck! 🚀
