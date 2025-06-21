# Quick Start Guide - Archangel144k/cyber-portfolio

## Download Files from Replit

Since Git operations are restricted in this environment, here's how to get your portfolio files:

### Method 1: Download Individual Files
Right-click and save each file:
- `index.html`
- `styles.css` 
- `script.js`
- `generated-icon.png`
- `README.md`
- `LICENSE`
- `DEPLOYMENT.md`
- `.gitignore`

### Method 2: Use the Shell Script
1. Download `setup-repo.sh`
2. Run it on your local machine to create the repository structure

## Local Setup Commands

```bash
# Create and navigate to project directory
mkdir cyber-portfolio
cd cyber-portfolio

# Initialize Git repository
git init
git branch -M main

# Set up Git (replace with your email)
git config user.name "Archangel144k"
git config user.email "your-email@example.com"

# Add remote repository
git remote add origin https://github.com/Archangel144k/cyber-portfolio.git

# Copy all portfolio files to this directory, then:
git add .
git commit -m "Initial cybersecurity portfolio - dark theme with animations"
git push -u origin main
```

## Before Pushing - Update Contact Form

In `index.html`, replace:
```html
action="https://formspree.io/f/YOUR_FORM_ID"
```

With your actual Formspree form ID from https://formspree.io

## GitHub Repository Setup

1. Go to GitHub.com
2. Create new repository: `cyber-portfolio`
3. Make it public
4. Don't initialize with README (you already have one)
5. Copy the repository URL: `https://github.com/Archangel144k/cyber-portfolio.git`

## Enable GitHub Pages

After pushing files:
1. Go to repository Settings
2. Navigate to Pages
3. Source: Deploy from branch
4. Branch: main
5. Folder: / (root)
6. Save

Your site will be live at: `https://Archangel144k.github.io/cyber-portfolio/`

## File Summary

Your portfolio includes:
- Professional dark cybersecurity theme
- Animated progress bars and particle effects
- Responsive design for all devices
- Contact form integration
- SEO optimized content
- Your authentic background and skills
- Home lab technology showcase