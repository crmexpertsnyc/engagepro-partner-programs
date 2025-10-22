# EngagePro Partner & Affiliate Programs

A professional landing page showcasing EngagePro's Partner and Affiliate Programs.

## 🌐 Live Website

This website is automatically deployed to GitHub Pages.

**URL:** https://crmexpertsnyc.github.io/engagepro-partner-programs/

## 📋 Overview

This is a static HTML website that presents information about two programs:
- **Partner Program**: For sales professionals, consultants, and agencies
- **Affiliate Program**: For content creators, influencers, and bloggers

## 🚀 Deployment

### Automatic Deployment

This site uses GitHub Actions to automatically deploy to GitHub Pages whenever changes are pushed to the `main` branch.

The deployment workflow:
1. Triggers on push to `main` branch or manually via workflow dispatch
2. Builds and uploads the site content
3. Deploys to GitHub Pages

### Manual Deployment

To manually trigger a deployment:
1. Go to the Actions tab in GitHub
2. Select "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

### Initial Setup (One-time)

To enable GitHub Pages for this repository:
1. Go to repository Settings → Pages
2. Under "Build and deployment":
   - Source: Select "GitHub Actions"
3. Save the settings

The site will be available at: `https://crmexpertsnyc.github.io/engagepro-partner-programs/`

## 📁 Project Structure

```
.
├── index.html              # Main landing page
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions deployment workflow
└── README.md              # This file
```

## 🛠️ Development

### Local Development

To view the site locally, simply open `index.html` in your web browser:

```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Use Python's built-in server
python3 -m http.server 8000
# Then visit http://localhost:8000

# Option 3: Use Node.js http-server
npx http-server
```

### Making Changes

1. Edit `index.html` with your desired changes
2. Test locally by opening the file in a browser
3. Commit and push to the `main` branch
4. The site will automatically redeploy via GitHub Actions

## 📝 Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean, professional design with gradient accents
- **Comparison Table**: Easy-to-understand comparison of both programs
- **Call-to-Action**: Clear buttons for joining either program
- **No Build Process**: Pure HTML/CSS - no dependencies or build tools required

## 🎨 Customization

The website uses embedded CSS in the HTML file. To customize:
- Colors and gradients: Modify the CSS variables in the `<style>` section
- Content: Update the HTML in the `<body>` section
- Layout: Adjust grid and flexbox properties in CSS

## 📄 License

Copyright © EngagePro - All rights reserved.
