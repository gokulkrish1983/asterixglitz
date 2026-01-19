# AsterixGlitz Portfolio

A modern, responsive UX design portfolio website for Anuradha.

## 🚀 Free Hosting Options

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub account** at [github.com](https://github.com) if you don't have one

2. **Create a new repository:**
   - Click "New repository"
   - Name it `asterixglitz.github.io` (replace 'asterixglitz' with your username for a custom URL, or any name)
   - Keep it Public
   - Click "Create repository"

3. **Upload your files:**
   - Click "uploading an existing file"
   - Drag and drop ALL files and folders from this portfolio folder
   - Click "Commit changes"

4. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click Save

5. **Your site will be live at:** `https://yourusername.github.io/repositoryname`

### Option 2: Netlify

1. Go to [netlify.com](https://netlify.com) and sign up
2. Click "Add new site" → "Deploy manually"
3. Drag and drop the entire portfolio folder
4. Your site is live instantly!

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "New Project" → "Import Git Repository" or upload directly
3. Deploy!

## 📁 File Structure

```
portfolio/
├── index.html              # Homepage
├── images/                 # All images
│   ├── logo.png
│   ├── hero-image.png
│   └── ... (all portfolio images)
├── case-studies/           # Case study pages
│   ├── daily-dosa.html
│   ├── fox-era.html
│   └── movies-now.html
└── README.md               # This file
```

## 🌐 Custom Domain (Optional)

To use your own domain (like asterixglitz.com):

### For GitHub Pages:
1. Go to your repository Settings → Pages
2. Under "Custom domain", enter your domain
3. At your domain registrar (Bluehost), update DNS:
   - Add a CNAME record pointing to `yourusername.github.io`

### For Netlify:
1. Go to Domain settings → Add custom domain
2. Follow the DNS configuration instructions

## ✨ Features

- Modern, dark theme design
- Fully responsive (mobile-friendly)
- Fast loading (static HTML/CSS/JS)
- No WordPress dependencies
- SEO optimized
- Smooth animations

## 🎨 Customization

### Changing Colors
Edit the CSS variables in each HTML file:
```css
:root {
    --color-primary: #c9a227;      /* Gold accent */
    --color-bg: #0a0a0f;           /* Dark background */
    --color-text: #f5f5f7;         /* Light text */
}
```

### Updating Content
- Edit text directly in the HTML files
- Replace images in the `images/` folder
- Add new case studies by copying and modifying existing ones

## 📧 Contact Form

The current contact section links to email. For a working contact form, you can:
1. Use [Formspree](https://formspree.io) (free)
2. Use [Netlify Forms](https://www.netlify.com/products/forms/) (if hosted on Netlify)

---

Made with ❤️ for Anuradha's UX Portfolio
