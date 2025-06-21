# GitHub Pages Deployment Guide for Archangel144k/cyber-portfolio

## Prerequisites
- GitHub account (Archangel144k)
- Git installed on your computer
- Formspree account for contact form

## Step-by-Step Deployment

### 1. Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in as Archangel144k
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository exactly: **cyber-portfolio**
5. Make it public (required for free GitHub Pages)
6. Check "Add a README file"
7. Click "Create repository"

### 2. Upload Your Portfolio Files

**Option A: Using GitHub Web Interface**
1. Click "uploading an existing file" on your new repository page
2. Drag and drop all your portfolio files:
   - index.html
   - styles.css
   - script.js
   - generated-icon.png
   - README.md
   - LICENSE
   - .gitignore
3. Write a commit message: "Initial portfolio upload"
4. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
# Clone your repository
git clone https://github.com/Archangel144k/cyber-portfolio.git
cd cyber-portfolio

# Copy your portfolio files to this directory
# Then add and commit
git add .
git commit -m "Initial portfolio upload"
git push origin main
```

### 3. Set Up Contact Form

1. Go to [Formspree.io](https://formspree.io)
2. Sign up for a free account
3. Click "New Form"
4. Give it a name (e.g., "Portfolio Contact Form")
5. Copy your form endpoint (looks like: `https://formspree.io/f/xyzabc123`)
6. Edit `index.html` in your GitHub repository
7. Find this line:
   ```html
   <form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
8. Replace `YOUR_FORM_ID` with your actual form ID
9. Update the redirect URL:
   ```html
   <input type="hidden" name="_next" value="https://Archangel144k.github.io/cyber-portfolio/">
   ```
10. Commit the changes

### 4. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Select "/ (root)" folder
7. Click "Save"

### 5. Access Your Live Site

- Your portfolio will be available at: `https://Archangel144k.github.io/cyber-portfolio/`
- It may take 5-10 minutes for the site to become available
- GitHub will show a green checkmark when deployment is complete

## Updating Your Portfolio

To make changes:

1. Edit files directly on GitHub (click pencil icon)
2. Or use Git to clone, edit locally, and push changes
3. Changes automatically deploy to your live site

## Troubleshooting

### Site Not Loading
- Check repository is public
- Verify GitHub Pages is enabled in settings
- Wait 10-15 minutes for initial deployment

### Contact Form Not Working
- Verify Formspree form ID is correct
- Check that form action URL is properly formatted
- Test the form by submitting a message

### Custom Domain (Optional)
1. Buy a domain name
2. In repository settings > Pages
3. Add your custom domain
4. Configure DNS with your domain provider

## Security Considerations

- Never commit sensitive information (API keys, passwords)
- Use environment variables for sensitive data
- Keep dependencies updated
- Monitor form submissions for spam

## Performance Optimization

- Images are optimized
- CSS and JS are minified
- Uses CDN for external resources
- Lighthouse score should be 90+

Your portfolio is now live and professional!