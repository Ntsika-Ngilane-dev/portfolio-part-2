# Quick Customization Guide

## 🎨 Essential Changes to Make

### **1. Update Hero Section (Hero)**
📍 **File**: `index.html`, lines 38-54

```html
<!-- CHANGE THIS: -->
<h1 class="display-3 fw-bold mb-3">I am Your Name</h1>
<!-- TO THIS: -->
<h1 class="display-3 fw-bold mb-3">I am Sarah Johnson</h1>

<!-- CHANGE THIS: -->
<p class="lead fs-4 mb-0">Web Developer & Digital Innovator</p>
<!-- TO THIS: -->
<p class="lead fs-4 mb-0">UX/UI Designer & Web Developer</p>
```

---

### **2. Update Profile Image**
📍 **File**: `index.html`, line 80

Replace the Unsplash URL with your own image URL:
```html
<!-- Before: -->
<img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&h=400&fit=crop" 
     alt="Profile picture">

<!-- After (upload to Imgur or similar, paste URL): -->
<img src="https://your-image-url.jpg" 
     alt="Profile picture">
```

---

### **3. Update Contact Details**
📍 **File**: `index.html`, lines 82-84

```html
<h3 class="h5 fw-bold mb-3">Your Name</h3>
<p class="mb-2"><strong>Profile:</strong> Web Developer</p>
<p class="mb-2"><strong>Phone:</strong> +1 (555) 123-4567</p>
<p class="mb-3"><strong>Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a></p>
```

Replace with your actual details:
```html
<h3 class="h5 fw-bold mb-3">Sarah Johnson</h3>
<p class="mb-2"><strong>Profile:</strong> UX/UI Designer</p>
<p class="mb-2"><strong>Phone:</strong> +1 (555) 987-6543</p>
<p class="mb-3"><strong>Email:</strong> <a href="mailto:sarah@example.com">sarah@example.com</a></p>
```

---

### **4. Update Skills Badges**
📍 **File**: `index.html`, lines 93-101

Replace the badges with your actual skills:
```html
<!-- Before: -->
<span class="badge bg-primary me-2 mb-2">HTML5</span>
<span class="badge bg-primary me-2 mb-2">CSS3</span>
<span class="badge bg-primary me-2 mb-2">Bootstrap</span>

<!-- After: -->
<span class="badge bg-primary me-2 mb-2">Figma</span>
<span class="badge bg-primary me-2 mb-2">Prototyping</span>
<span class="badge bg-primary me-2 mb-2">UX Research</span>
<span class="badge bg-primary me-2 mb-2">Wireframing</span>
```

---

### **5. Update About Me Bio**
📍 **File**: `index.html`, lines 104-112

Replace with your story (keep it under 160 words):
```html
<!-- Before: -->
<p class="text-muted lh-lg">
    I'm a passionate web developer...
</p>

<!-- After: -->
<p class="text-muted lh-lg">
    I'm a design-focused developer who bridges the gap between beautiful aesthetics 
    and functional code. With 3+ years of experience in web design and development, 
    I've worked with startups and established companies to create digital experiences 
    that users love. My expertise spans responsive design, modern CSS, and interactive 
    UI components using Bootstrap and vanilla JavaScript.
</p>
```

---

### **6. Update Projects**
📍 **File**: `index.html`, lines 125-312

Replace each project section. Here's the template:

```html
<!-- Project Card -->
<div class="col-lg-4 col-md-6">
    <div class="project-card card h-100 border-0 shadow-sm overflow-hidden">
        <!-- Replace image URL -->
        <img src="YOUR_PROJECT_IMAGE_URL" 
             alt="Your project description" class="card-img-top" 
             style="object-fit: cover; height: 250px;">
        <div class="card-body">
            <!-- Update title -->
            <h5 class="card-title fw-bold">Your Project Title</h5>
            <!-- Update subtitle -->
            <p class="card-text small text-muted">Built with HTML, CSS & Bootstrap</p>
            <div class="d-flex gap-2">
                <!-- Update project URL -->
                <a href="https://your-project-url.com" target="_blank" 
                   rel="noopener noreferrer" class="btn btn-primary btn-sm w-100">
                    View Website
                </a>
                <!-- Update GitHub URL -->
                <a href="https://github.com/username/project-repo" target="_blank"
                   rel="noopener noreferrer" class="btn btn-outline-secondary btn-sm">
                    <i class="bi bi-code-slash"></i>
                </a>
            </div>
        </div>
    </div>
</div>
```

---

### **7. Update Social Links**
📍 **File**: `index.html`, lines 206-220

Replace your social media URLs:
```html
<!-- Instagram -->
<a href="https://instagram.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" ...>

<!-- GitHub -->
<a href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" ...>

<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR_PROFILE" target="_blank" rel="noopener noreferrer" ...>
```

---

### **8. Update Footer Attribution**
📍 **File**: `index.html`, line 351

```html
<!-- Before: -->
<p class="text-center text-white mb-0">
    Developed by <strong>Your Name</strong> using Bootstrap, for portfolio purposes. © 2024
</p>

<!-- After: -->
<p class="text-center text-white mb-0">
    Developed by <strong>Sarah Johnson</strong> using Bootstrap. © 2024 | All Rights Reserved
</p>
```

---

## 🎨 Color Customization

### **Change Primary Color**
📍 **File**: `styles.css`, line 2

```css
/* Current: Blue */
--primary-color: #0d6efd;

/* Change to: */
--primary-color: #8b5cf6;  /* Purple */
/* or */
--primary-color: #ec4899;  /* Pink */
/* or */
--primary-color: #14b8a6;  /* Teal */
```

**All buttons and highlights will automatically update!**

---

### **Change Navbar & Footer Colors**
📍 **File**: `styles.css`, lines 95-109

```css
.navbar {
    background-color: var(--white);
    /* Change to: */
    background-color: #f8f9fa;  /* Light gray */
}

.footer {
    background-color: var(--dark-color);
    /* Change to: */
    background-color: #2d3748;  /* Dark blue-gray */
}
```

---

## 🖼️ Image Replacement Guide

### **Using Unsplash (Free)**
1. Go to [unsplash.com](https://unsplash.com)
2. Search for image (e.g., "office workspace")
3. Click image → Click "Copy link"
4. Paste into `src` attribute

### **Using Imgur (Personal Images)**
1. Go to [imgur.com](https://imgur.com)
2. Click "Upload"
3. Select your image
4. Copy the URL
5. Paste into `src` attribute

### **Using Local Files**
Create `images/` folder and upload:
```html
<img src="images/my-photo.jpg" alt="Profile">
```

---

## 📝 Project Ideas to Feature

Add your real projects or create new ones:

**Real Projects:**
- ✅ College assignments
- ✅ Personal projects
- ✅ Freelance work
- ✅ Open source contributions
- ✅ Hackathon projects

**If Starting Out:**
- Clone popular sites (Tesla, Netflix)
- Build a landing page
- Create a restaurant menu
- Make a photography portfolio
- Build a weather app (no API needed for demo)

---

## 🎯 Final Checklist Before Publishing

- [ ] All text updated with your information
- [ ] Profile image added
- [ ] Projects updated with real/demo projects
- [ ] Social links point to your profiles
- [ ] No placeholder text remains
- [ ] Colors customized to your brand
- [ ] Tested on mobile
- [ ] Tested dark mode
- [ ] Tested print view
- [ ] Links all working

---

## 📱 Deploy Your Updated Portfolio

### **GitHub Pages**
```bash
cd c:\Users\Arwe\Documents\portfolio-part-2
git add .
git commit -m "Update portfolio with personal info"
git push
```

### **Netlify**
1. Go to Netlify
2. Drag and drop updated folder
3. Done!

---

## ✨ Pro Tips

1. **Update Regularly** - Add new projects every month
2. **Optimize Images** - Compress before uploading
3. **Use Real Content** - Avoid placeholder text
4. **Mobile First** - Always test on phones
5. **Keep It Simple** - Don't overload with too many sections
6. **Share on LinkedIn** - Post a quick update when you deploy

---

Need more help? Check:
- 📖 README.md - Full documentation
- 🚀 DEPLOYMENT.md - How to go live
- 💻 styles.css - All CSS variables

**Good luck! 🚀**
