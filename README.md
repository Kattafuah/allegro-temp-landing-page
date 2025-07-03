# Allegro Travel & Tours - Landing Page

A professional, responsive landing page for Allegro Travel & Tours, specializing in international visa advisory services and career opportunities in the travel industry.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Friendly**: Semantic HTML structure with proper meta tags
- **GitHub Pages Ready**: Configured for easy deployment
- **Dual Purpose**: Serves both potential clients and job applicants
- **Career Focused**: Includes messaging for prospective team members

## File Structure

```
landing_page/
├── index.html          # Main HTML file
├── style.css           # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This documentation file
```

## Quick Start

1. **Clone or download** this repository
2. **Customize** the content to match your business details
3. **Deploy** to GitHub Pages following the instructions below

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. **Create a new repository** on GitHub:
   - Go to [GitHub](https://github.com)
   - Click "+" → "New repository"
   - Name it something like `allegro-landing-page` or `company-website`
   - Make sure it's **Public** (required for free GitHub Pages)
   - Don't initialize with README (you already have one)

2. **Upload your files**:
   - Click "uploading an existing file"
   - Drag and drop all files (`index.html`, `style.css`, `script.js`, `README.md`)
   - Add a commit message like "Initial landing page"
   - Click "Commit changes"

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your site**:
   - GitHub will provide a URL like: `https://yourusername.github.io/repository-name`
   - It may take a few minutes to become available

### Method 2: Using Git Command Line

```bash
# Create a new repository on GitHub first, then:
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Copy all landing page files to this directory
# Then:
git add .
git commit -m "Initial landing page"
git push origin main

# Enable GitHub Pages in repository settings
```

## Customization Guide

### 1. Company Information
Edit `index.html` to update:
- Company name and tagline
- Contact information (email, phone)
- Service descriptions
- About section content

### 2. Contact Details
Update these sections in `index.html`:
```html
<!-- Email -->
<p>info@allegrotravelandtours.com</p>

<!-- Phone -->
<p>+1 (555) 123-4567</p>

<!-- Business Hours -->
<p>Monday - Friday: 9AM - 6PM</p>
```

### 3. Colors and Branding
To change the color scheme, modify these CSS variables in `style.css`:
```css
/* Primary colors */
#3498db  /* Blue - used for buttons and accents */
#2c3e50  /* Dark blue - used for headings */
#667eea  /* Purple gradient start */
#764ba2  /* Purple gradient end */
```

### 4. Services
Update the services section in `index.html`:
```html
<div class="service-card">
    <div class="service-icon">🇨🇳</div>
    <h3>Your Service Name</h3>
    <p>Your service description</p>
</div>
```

### 5. Statistics
Update the about section statistics:
```html
<div class="stat">
    <h3>500+</h3>
    <p>Successful Applications</p>
</div>
```

## Advanced Customization

### Adding Your Logo
1. Add your logo image to the repository
2. Replace the text logo in the navigation:
```html
<div class="nav-logo">
    <img src="your-logo.png" alt="Allegro Travel & Tours" height="40">
</div>
```

### Adding Real Images
1. Add image files to your repository
2. Replace the placeholder elements:
```html
<!-- Replace hero placeholder -->
<div class="hero-image">
    <img src="hero-image.jpg" alt="Travel Advisory Services">
</div>

<!-- Replace about placeholder -->
<div class="about-image">
    <img src="about-image.jpg" alt="About Us">
</div>
```

### Form Integration
To make the contact form functional:
1. Use services like [Formspree](https://formspree.io/) or [Netlify Forms](https://www.netlify.com/products/forms/)
2. Update the form action in `index.html`:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## SEO Optimization

The landing page includes:
- Semantic HTML structure
- Meta description for search engines
- Proper heading hierarchy (H1, H2, H3)
- Alt text for images (when you add them)
- Mobile-friendly responsive design

To improve SEO further:
1. Add more specific meta tags
2. Include structured data markup
3. Add a favicon
4. Optimize images for web

## Browser Support

This landing page works on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- **No external dependencies** except Google Fonts
- **Lightweight**: Total page size < 50KB
- **Fast loading**: Optimized CSS and minimal JavaScript
- **Mobile optimized**: Responsive design with touch-friendly interface

## Maintenance

To keep your landing page updated:
1. Regularly update contact information
2. Add new services as your business grows
3. Update statistics and testimonials
4. Keep content fresh and relevant

## Troubleshooting

### Common Issues:

1. **Site not loading**: Wait 5-10 minutes after enabling GitHub Pages
2. **Changes not visible**: Clear browser cache or try incognito mode
3. **Mobile menu not working**: Check if JavaScript is enabled
4. **Form not submitting**: Integrate with a form service like Formspree

### Getting Help:

If you encounter issues:
1. Check GitHub Pages documentation
2. Verify all files are properly uploaded
3. Ensure repository is public
4. Check browser console for errors

## License

This landing page template is provided as-is for business use. Feel free to modify and customize it for your needs.

## Support

For questions about customization or deployment, refer to:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML/CSS/JS tutorials](https://www.w3schools.com/)
- [Web development resources](https://developer.mozilla.org/)

---

**Ready to launch your professional landing page? Follow the deployment steps above and start attracting more clients today!** 