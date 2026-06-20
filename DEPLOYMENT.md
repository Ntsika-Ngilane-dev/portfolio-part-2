# Portfolio Deployment Guide

## 🚀 Quick Deployment Options

### **Option 1: Netlify (Easiest - Recommended)**

#### **Step 1: Create Netlify Account**
1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub, Google, or email

#### **Step 2: Deploy**
1. Click "Add new site" → "Deploy manually"
2. Drag and drop your entire `portfolio-part-2` folder
3. **Done!** Your site is live instantly

**Your URL will be**: `https://your-site-name.netlify.app`

#### **Step 3: Connect Custom Domain (Optional)**
- In Netlify Dashboard → Site settings → Domain management
- Add your custom domain (costs ~$10-15/year)

---

### **Option 2: GitHub Pages (Free, Integrated with Git)**

#### **Step 1: Create GitHub Repository**
1. Go to [github.com](https://github.com) → "New repository"
2. Name it: `portfolio-part-2` (or your desired name)
3. Make it **Public**
4. Click "Create repository"

#### **Step 2: Push Your Code**
```bash
# Navigate to your portfolio folder
cd c:\Users\Arwe\Documents\portfolio-part-2

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio commit"

# Add remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/portfolio-part-2.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### **Step 3: Enable GitHub Pages**
1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll to **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**

**Your URL will be**: `https://USERNAME.github.io/portfolio-part-2`

#### **Step 4: Verify**
- Wait 30-60 seconds for deployment
- Visit your GitHub Pages URL
- It should show your portfolio!

---

### **Option 3: Vercel (Alternative - Fast)**

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Add new project"
4. Select your repository
5. Deploy (auto-deploys on every push to main)

**URL**: `https://your-project.vercel.app`

---

## 📋 Pre-Deployment Checklist

Before deploying, make sure:

- [ ] **Update your name** in `index.html` (line 48, line 80)
- [ ] **Change your role** (line 49)
- [ ] **Update contact info** (lines 82-84)
- [ ] **Replace profile image** (line 80)
- [ ] **Update bio text** (around line 102)
- [ ] **Replace project links** with real project URLs
- [ ] **Test responsiveness** on mobile (DevTools F12 → Toggle device)
- [ ] **Test dark mode** (Windows Settings → Colors → Dark mode)
- [ ] **Test print view** (Ctrl+P → Save as PDF)
- [ ] **Check accessibility** (Tab through page with keyboard)

---

## 🔄 Post-Deployment Updates

### **Making Changes**

**For Netlify:**
1. Edit files locally
2. Drag and drop updated folder to Netlify
3. **OR** connect GitHub repo for auto-deploys

**For GitHub Pages:**
1. Edit files locally
2. Git commit and push:
```bash
git add .
git commit -m "Update portfolio"
git push
```
3. Changes appear in ~30 seconds

---

## 🎯 Social Media Links to Update

In `index.html`, update the social links (around line 206):

```html
<!-- Instagram -->
<a href="https://instagram.com/YOUR_USERNAME" ...>

<!-- GitHub -->
<a href="https://github.com/YOUR_USERNAME" ...>

<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR_PROFILE" ...>
```

---

## 🔍 Testing Your Portfolio

### **Desktop Testing**
- Chrome, Firefox, Safari, Edge
- Fullscreen (1920x1080)
- Zoom 90%, 100%, 110%

### **Mobile Testing (DevTools)**
1. Press `F12` in browser
2. Click device toggle (phone icon)
3. Test at: 360px, 568px, 768px, 1024px

### **Accessibility Testing**
1. Press `Tab` repeatedly - ensure all links/buttons are reachable
2. Check focus outlines are visible
3. Increase text size (Ctrl + Plus) - ensure responsive
4. Try dark mode - colors should look good

### **Print Testing**
1. Press `Ctrl+P` (or Cmd+P on Mac)
2. Click "Save as PDF"
3. Check: Single page, readable fonts, no clutter

---

## 🆘 Troubleshooting

### **Site Not Loading**
- Clear browser cache (Ctrl+Shift+Delete)
- Check file names are correct (index.html, styles.css, print.css)
- Ensure all image URLs are accessible

### **Styles Not Showing**
- Verify `styles.css` is in same folder as `index.html`
- Check Bootstrap CDN link works: Try opening it in browser
- Clear cache and reload (Ctrl+Shift+R)

### **Images Not Loading**
- Check image URLs are correct
- Ensure external URLs (Unsplash) are accessible
- Test in incognito window (avoids cache issues)

### **Mobile Menu Not Working**
- This is because Bootstrap JS is disabled (as per requirements)
- The mobile menu will show but may need manual toggle
- Consider using CSS-only hamburger menu if needed

---

## 📊 Performance Optimization

Your portfolio loads quickly because:
- ✅ No JavaScript dependencies
- ✅ CSS-only styling
- ✅ Optimized Bootstrap CDN
- ✅ License-free Unsplash images (compressed)
- ✅ Minimal external resources

---

## 🔐 Security & Best Practices

- ✅ No sensitive data in code
- ✅ HTML5 form validation only
- ✅ No backend/database required
- ✅ Static hosting is inherently secure
- ✅ HTTPS enabled automatically (Netlify/GitHub Pages)

---

## 📱 Domain Registration (Optional)

### **Get Custom Domain**
1. **Namecheap** - $7-15/year
2. **GoDaddy** - $10-20/year
3. **Google Domains** - $12/year

### **Connect to Netlify**
1. Netlify Dashboard → Site settings
2. Domain management → Add custom domain
3. Update DNS records (Netlify provides instructions)

### **Connect to GitHub Pages**
1. Edit `_config.yml` or add `CNAME` file
2. Add your domain name
3. Update DNS at your registrar

---

## ✅ Final Deployment Checklist

- [ ] All personal info updated
- [ ] Portfolio tested on mobile
- [ ] Dark mode tested
- [ ] Print view works (Ctrl+P)
- [ ] All links working
- [ ] Responsive design verified (360px-4K)
- [ ] Accessibility tested (keyboard navigation)
- [ ] Site deployed and live
- [ ] Share on LinkedIn
- [ ] Test URL in incognito window

---

## 🎉 You're Done!

Your professional portfolio is now live and ready to share with employers, clients, and your network!

**Next Steps:**
1. Keep it updated with new projects
2. Share on LinkedIn, GitHub, Twitter
3. Link in email signature
4. Send to companies you're interested in

---

## 📞 Support Resources

- **Bootstrap Docs**: https://getbootstrap.com/docs/5.0/
- **MDN Web Docs**: https://developer.mozilla.org/
- **Netlify Help**: https://docs.netlify.com/
- **GitHub Help**: https://docs.github.com/

---

**Good luck! 🚀**
