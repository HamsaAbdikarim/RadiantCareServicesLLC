# RadiantCare Services LLC - Assisted Living Website

A professional, responsive website for RadiantCare Services LLC, an assisted living facility.

## Features

- 🎨 Modern, warm, and trustworthy design
- 📱 Fully responsive (mobile, tablet, desktop)
- ♿ Accessible and user-friendly
- ⚡ Fast loading with optimized performance
- 🎭 Smooth animations and transitions
- 📧 Contact form with validation

## Sections

1. **Home/Hero** - Welcome message with key features
2. **Services** - Comprehensive care services offered
3. **Call-to-Action** - Appointment scheduling and location info
4. **Mission** - Company mission and values
5. **Contact** - Contact form and information
6. **Footer** - Quick links and additional info

## Files Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive features
└── README.md       # This file
```

## Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `radiantcare-website`)
4. Make it public
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. Click "uploading an existing file"
2. Drag and drop all files (index.html, styles.css, script.js, README.md)
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be live at: `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Customization Guide

### Update Contact Information

In `index.html`, search for and replace:
- Phone numbers: `(555) 123-4567`
- Email addresses: `info@radiantcareservices.com`
- Address: `1234 Caring Way, Your City, ST 12345`

### Change Colors

In `styles.css`, modify the CSS variables at the top:
```css
:root {
    --primary-color: #5f8aa6;      /* Main brand color */
    --secondary-color: #d4a574;    /* Secondary accent */
    --accent-color: #e8997a;       /* Additional accent */
}
```

### Add Your Logo

Replace the SVG logo in the navigation section with your own logo image:
```html
<div class="logo-icon">
    <img src="your-logo.png" alt="RadiantCare Logo" width="50" height="50">
</div>
```

### Add Real Images

Replace the placeholder SVG in the hero and mission sections with actual photos:
```html
<!-- In hero section -->
<div class="hero-image">
    <img src="images/hero-image.jpg" alt="Happy residents">
</div>

<!-- In mission section -->
<div class="mission-image">
    <img src="images/mission-image.jpg" alt="Caring staff">
</div>
```

### Update Service Details

In `index.html`, find the "Services Section" and modify the service cards with your specific offerings.

### Customize the Mission Statement

Update the text in the "Mission Section" to reflect your facility's actual mission and values.

## Adding More Pages

To add additional pages (e.g., About, Careers):

1. Create a new HTML file (e.g., `about.html`)
2. Copy the header and footer from `index.html`
3. Add your content in between
4. Link to it in the navigation menu

## Form Integration

The contact form is currently set up with Formspree to send emails to **RadiantCarellc@outlook.com**. 

**IMPORTANT**: You need to activate the form:
1. Go to your live website
2. Fill out and submit the contact form once
3. Check RadiantCarellc@outlook.com for a confirmation email from Formspree
4. Click the activation link in that email
5. Your form will now work and send all submissions to your Outlook email!

Alternatively, you can:

1. **Using Formspree (Easy):**
   - Sign up at [Formspree.io](https://formspree.io)
   - Get your form endpoint
   - Add to the form tag: `<form action="https://formspree.io/f/YOUR-FORM-ID" method="POST">`

2. **Using Google Forms:**
   - Create a Google Form
   - Embed it in place of the current form

3. **Using a Backend Service:**
   - Set up a backend service (Node.js, PHP, etc.)
   - Modify `script.js` to send data to your server

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Accessibility Features

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Color contrast compliance
- Reduced motion support for users with vestibular disorders

## Performance Tips

- Compress images before uploading (use TinyPNG or similar)
- Keep file sizes small
- Use lazy loading for images below the fold
- Minimize custom fonts if possible

## License

Free to use and modify for RadiantCare Services LLC.

## Support

For questions or issues with the website code:
- Check GitHub Issues
- Refer to [MDN Web Docs](https://developer.mozilla.org)
- Contact your web developer

---

**Created with care for RadiantCare Services LLC** 💙
