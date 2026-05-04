# Miteri Solutions Website

A modern, responsive business landing page for [Miteri Solutions](https://miterisolutions.dpdns.org) - your trusted partner for innovative digital and printing services.

## Services

- **Printing Services**: High-quality printing solutions for business and personal needs
- **Software Development**: Custom software to streamline operations and boost productivity
- **IT Consulting**: Expert guidance for technology challenges and opportunities
- **Computer Repair**: Professional laptop and computer repair services
- **Digital Subscriptions**: Convenient access to streaming platforms and digital services
- **Game Top-Ups**: Fast and reliable game credits for popular titles

## Features

- Fully responsive design (desktop, tablet, mobile)
- Mobile-friendly hamburger navigation
- Smooth scrolling between sections
- Google Forms contact integration
- Modern UI with CSS custom properties
- SVG icons (no external icon libraries)
- Custom favicon and branding

## Project Structure

```
website/
├── index.html
├── CNAME
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── script.js
    └── images/
        ├── favicon.jpg
        └── banner.png
```

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `your-username.github.io` (recommended) or any name you prefer
3. Make it public

### Step 2: Push Your Code

```bash
cd website
git init
git add .
git commit -m "Initial commit: Miteri Solutions website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings** > **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select **main** branch and **/ (root)** folder
4. Click **Save**

### Step 4: Configure Custom Domain

1. In the same Pages settings, enter `miterisolutions.dpdns.org` in the **Custom domain** field
2. Click **Save**
3. Check **Enforce HTTPS** (wait for SSL certificate to provision)

### Step 5: Configure DNS

Add a **CNAME** record in your DNS provider settings:

| Type   | Name             | Value                   |
|--------|------------------|-------------------------|
| CNAME  | miterisolutions  | miteri-miteri.github.io |

## Customization

- **Colors**: Edit CSS variables in `assets/css/styles.css` (`:root` section)
- **Contact button link**: Update the Google Forms URL in the contact section of `index.html`
- **Contact info**: Update phone, email, and address in `index.html`
- **Images**: Replace `favicon.jpg` and `banner.png` in `assets/images/`
- **Social links**: Update footer social media URLs in `index.html`
