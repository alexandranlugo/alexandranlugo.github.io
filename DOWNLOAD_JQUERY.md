# 📥 DOWNLOAD JQUERY MANUALLY

Since the network is restricted, you need to download jQuery manually:

## Method 1: Download jQuery (Recommended)

1. **Visit**: https://code.jquery.com/jquery-3.6.0.min.js
2. **Right-click** on the page → Save As
3. **Save** to: `assets/js/jquery.min.js`

## Method 2: Use CDN (Easiest!)

Instead of downloading, just add this line to `index.html` right before the closing `</body>` tag:

```html
<!-- Replace the local jQuery script with this CDN link -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="assets/js/browser.min.js"></script>
<script src="assets/js/breakpoints.min.js"></script>
<script src="assets/js/util.js"></script>
<script src="assets/js/main.js"></script>
</body>
</html>
```

**This is the fastest way to get your site working!** The CDN version will actually load faster for users anyway.

---

## Font Awesome Icons

### Method 1: Download Font Awesome
1. Visit: https://fontawesome.com/download
2. Download Free version
3. Extract and copy `css/all.min.css` to `assets/css/fontawesome-all.min.css`
4. Copy the `webfonts/` folder to `assets/webfonts/`

### Method 2: Use CDN (Easiest!)

Add this to `<head>` section in `index.html`:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

**Again, CDN is easier and faster!**

---

## ✅ Quick Setup with CDN (Recommended)

To get your portfolio working ASAP, just update `index.html`:

### 1. In the `<head>` section, add:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

### 2. Before the closing `</body>` tag, replace the script section with:
```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="assets/js/browser.min.js"></script>
<script src="assets/js/breakpoints.min.js"></script>
<script src="assets/js/util.js"></script>
<script src="assets/js/main.js"></script>
```

That's it! Your portfolio will work perfectly with these CDN links, and it'll actually be faster than hosting the files locally.
