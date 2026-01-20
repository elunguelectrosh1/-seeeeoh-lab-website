# SEEEEOH LAB Website

Modern AI and cybersecurity research lab website for Southern Africa.

## 🚀 Quick Start

### Local Development
1. Open `index.html` in your browser
2. No build process required - pure HTML, CSS, and JavaScript

### Project Structure
```
seeeeoh-lab-website/
├── index.html          # Main HTML file
├── style.css           # Styling
├── script.js           # JavaScript functionality
├── seeeeoh-lab-logo2.png  # Logo image
└── README.md           # This file
```

## 🌐 Deploy to Netlify

### Option 1: Deploy via Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

### Option 2: Deploy via Netlify Dashboard
1. Go to [app.netlify.com](https://app.netlify.com)
2. Click "Add new site" → "Deploy manually"
3. Drag and drop all files (index.html, style.css, script.js, seeeeoh-lab-logo2.png)
4. Your site is live!

### Option 3: Deploy from GitHub (Recommended)
1. Push code to GitHub (see below)
2. Go to [app.netlify.com](https://app.netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Choose GitHub and select your repository
5. Click "Deploy site"

## 📦 Deploy to GitHub

### First Time Setup
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - SEEEEOH LAB website"

# Add remote (replace with your repository URL)
git remote add origin https://github.com/YOUR_USERNAME/seeeeoh-lab-website.git

# Push to GitHub
git push -u origin main
```

### Update Website
```bash
git add .
git commit -m "Update website"
git push
```

## 🔧 Configuration

### Update Contact Form
Replace `YOUR_FORM_ID` in `index.html` (line 342) with your Formspree form ID:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Custom Domain (Netlify)
1. Go to Site settings → Domain management
2. Add custom domain: `seeeeoh-lab.com` or `see-ee-oh.com`
3. Update DNS records as instructed

## 📝 Features

- ✅ Responsive design
- ✅ Modern AI lab aesthetic
- ✅ Black and white color scheme
- ✅ Smooth animations
- ✅ Mobile-friendly navigation
- ✅ SEO optimized
- ✅ Fast loading

## 🎨 Customization

### Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary-black: #000000;
    --pure-white: #ffffff;
    /* Add your custom colors */
}
```

### Content
- Update services in the Services section
- Modify pricing in service cards
- Change contact information
- Update footer links

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

© 2025 SEEEEOH LAB (Pty) Ltd. All rights reserved.
Founded by Benjamen Elungu.

## 🤝 Support

Email: benjamen@see-ee-oh.com
Phone: +264 85 749 9175
Location: Windhoek, Namibia
