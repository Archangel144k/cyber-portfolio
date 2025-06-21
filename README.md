# Cybersecurity Portfolio

A modern, dark-themed portfolio website showcasing my transition from computer technician and truck driver to cybersecurity professional. Features authentic project highlights, real-world lab setup, and active learning journey.

## Live Demo

🌐 **[View Portfolio](https://archangel144k.github.io/cyber-portfolio/)**

## About This Portfolio

This portfolio represents my authentic career transition into cybersecurity, highlighting:

- **10+ years** of computer repair and building experience
- **CompTIA A+** certification and ongoing training
- **Active home lab** with Proxmox, Wazuh SIEM, OPNSense, and Suricata
- **Current studies**: Google Cybersecurity Certificate, Ethical Hacking, Full Stack Development

## Features

- **Dark Cybersecurity Theme**: Professional teal accent colors
- **Animated Progress Bars**: Real skill percentages based on experience
- **Particle Background Effects**: Interactive visual elements
- **Responsive Design**: Optimized for all devices
- **Contact Form**: Integrated with Formspree
- **Fast Loading**: Optimized static site

## Technologies Used

- HTML5 & CSS3 (Custom Properties)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Orbitron, Rajdhani, Source Code Pro)
- GitHub Pages deployment

## Quick Start

### 1. Fork & Clone
```bash
git clone https://github.com/Archangel144k/cyber-portfolio.git
cd cyber-portfolio
```

### 2. Set Up Contact Form
1. Create free account at [Formspree.io](https://formspree.io)
2. Create new form and get your form ID
3. In `index.html`, replace:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
4. Update redirect URL:
   ```html
   <input type="hidden" name="_next" value="https://Archangel144k.github.io/cyber-portfolio/">
   ```

### 3. Enable GitHub Pages
1. Go to repository Settings
2. Navigate to Pages section
3. Source: Deploy from branch
4. Branch: main, folder: / (root)
5. Save

### 4. Customize Your Content
- Update personal information in `index.html`
- Modify skill percentages to match your experience
- Replace project examples with your actual work
- Update contact information

## File Structure

```
cyber-portfolio/
├── index.html              # Main portfolio page
├── styles.css              # All styling and animations
├── script.js               # Interactive functionality
├── generated-icon.png      # Favicon
├── README.md              # This documentation
├── LICENSE                # MIT License
└── .gitignore            # Git ignore rules
```

## Customization Guide

### Personal Information
Edit these sections in `index.html`:
- Hero title and description
- About section background
- Skills and percentages
- Project descriptions
- Contact information

### Color Scheme
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #64ffda;      /* Main accent */
    --secondary-color: #26a69a;    /* Secondary accent */
    --background-dark: #0a0f0d;    /* Main background */
    --text-primary: #ffffff;       /* Main text */
}
```

### Skills Section
Update skill items with your expertise:
```html
<div class="skill-item">
    <div class="skill-info">
        <span class="skill-name">Your Skill</span>
        <span class="skill-percentage">85%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress" data-width="85"></div>
    </div>
</div>
```

## Home Lab Technologies

This portfolio showcases a real home lab setup including:
- **Proxmox VE**: Virtualization platform
- **Wazuh SIEM**: Security information and event management
- **OPNSense**: Firewall and router
- **Suricata**: Intrusion detection system
- **Multiple VMs**: Kali Linux, Arch Linux, Fedora, Windows 11
- **Home Assistant**: Automation platform

## Deployment

### GitHub Pages (Recommended)
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://YOUR-USERNAME.github.io/REPO-NAME/`

### Alternative Hosting
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Codespaces**: Development environment

## Browser Support

✅ Chrome (latest)  
✅ Firefox (latest)  
✅ Safari (latest)  
✅ Edge (latest)  

## Performance

- **Lighthouse Score**: 95+ Performance
- **Load Time**: < 2 seconds
- **Mobile Optimized**: Fully responsive
- **SEO Friendly**: Semantic HTML structure

## Contributing

This is a personal portfolio, but feel free to:
- Report bugs or issues
- Suggest improvements
- Fork for your own use

## License

MIT License - see [LICENSE](LICENSE) file for details

## Contact

- **Email**: [Your email through contact form]
- **LinkedIn**: [Your LinkedIn profile]
- **GitHub**: [Your GitHub profile]

---

**Note**: This portfolio represents an authentic career transition journey. All projects, skills, and experiences are real and reflect ongoing learning in cybersecurity.