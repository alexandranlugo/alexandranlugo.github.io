# 📸 Adding Images to Your Portfolio

Your portfolio needs images to look complete. Here's how to add them quickly!

---

## 🚀 Quick Option: Use Placeholders First, Real Images Later

You can deploy your portfolio NOW with placeholder images, then replace them with real screenshots later. Here's how:

### Step 1: Download Free Placeholder Images

Visit **Unsplash.com** and search for:
- "data visualization" (for project screenshots)
- "tech workspace" (for about-bg.jpg)
- "abstract technology" (for bg.jpg)

Download images and rename them as follows:

### Required Images:

1. **bg.jpg** (1920x1080px)
   - Background image for the entire site
   - Search: "abstract technology blue" or "data network"
   - Example: https://unsplash.com/s/photos/technology-background

2. **about-bg.jpg** (800x500px)
   - Your photo or a professional workspace
   - Search: "office desk" or use a professional photo of yourself
   - Example: https://unsplash.com/s/photos/workspace

3. **music-dna-map.jpg** (800x600px)
   - Regional Music DNA project screenshot
   - Search: "map data visualization" or "music data"
   - **BETTER**: Take a screenshot of your actual Jupyter notebook output!

4. **altristotle-demo.jpg** (800x600px)
   - Altristotle interface screenshot
   - Search: "chatbot interface" or "AI interface"
   - **BETTER**: Screenshot your actual Altristotle demo!

5. **velocityx-clusters.jpg** (800x600px)
   - User clustering visualization
   - Search: "data clustering" or "scatter plot"
   - **BETTER**: Screenshot your clustering analysis from Jupyter!

6. **sallie-mae-governance.jpg** (800x600px)
   - Data governance dashboard
   - Search: "dashboard analytics" or "data governance"
   - Can use a generic analytics dashboard image

---

## 💡 Best Practice: Use REAL Screenshots

The best images come from your actual projects! Here's how:

### From Jupyter Notebooks:

1. **Open your project** (e.g., Regional Music DNA notebook)
2. **Find the best visualization** (maps, charts, graphs)
3. **Screenshot it**:
   - Mac: Cmd + Shift + 4
   - Windows: Windows Key + Shift + S
   - Linux: Shift + PrtScn
4. **Crop and resize** to ~800px wide
5. **Save as JPG** with project name

### From Web Apps/Demos:

1. **Run your demo** (e.g., Altristotle)
2. **Open in browser**
3. **Take screenshot** of the interface
4. **Crop to show key features**
5. **Save and compress** (use tinypng.com)

---

## 🎨 Image Specifications

- **Format**: JPG for photos/backgrounds, PNG for screenshots with text
- **Width**: 800-1200px (will auto-scale responsively)
- **File Size**: Under 500KB each (compress at tinypng.com)
- **Quality**: 80-90% JPG quality is perfect

---

## 📁 Where to Save Images

Save all images in the `images/` folder:

```
portfolio/
└── images/
    ├── bg.jpg
    ├── about-bg.jpg
    ├── music-dna-map.jpg
    ├── altristotle-demo.jpg
    ├── velocityx-clusters.jpg
    └── sallie-mae-governance.jpg
```

---

## 🔧 What if I Don't Have Project Screenshots Yet?

**Option 1: Deploy with Placeholders**
- Use Unsplash images temporarily
- Replace later when you have real screenshots
- Site looks professional either way!

**Option 2: Create Simple Graphics**
- Use Canva.com (free)
- Create simple data viz mockups
- Takes 10-15 minutes per image

**Option 3: Skip Images Initially**
- Comment out the image lines in index.html
- Add them later when ready
- Site still works fine without images!

### To comment out an image temporarily:

In `index.html`, change this:
```html
<span class="image main"><img src="images/music-dna-map.jpg" alt="" /></span>
```

To this:
```html
<!-- <span class="image main"><img src="images/music-dna-map.jpg" alt="" /></span> -->
```

---

## ⚡ Fastest Path to Launch

1. **Download 3-4 placeholder images** from Unsplash (15 mins)
2. **Rename them** to match the filenames above
3. **Save in `images/` folder**
4. **Deploy your site** - it's live!
5. **Replace with real screenshots** later when you have time

---

## 🎯 Priority Order

If you're short on time, prioritize these images:

1. **bg.jpg** - Most important (site background)
2. **about-bg.jpg** - Second most important (your About page)
3. **music-dna-map.jpg** - Best project to showcase first
4. Others can wait!

With just these 3 images, your portfolio will look complete and professional.

---

**Don't let perfect be the enemy of good!** Launch your portfolio with placeholder images and improve it later. The important thing is getting it live so you can start using it in job applications.

Good luck! 🚀
