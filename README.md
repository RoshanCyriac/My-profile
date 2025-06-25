# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-friendly layout.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading and optimized
- 🎭 Smooth animations and transitions
- 📧 Contact form with validation
- 🔍 SEO-friendly structure
- 🌙 Professional color scheme
- 📊 Interactive elements

## Sections

1. **Hero Section** - Introduction with name, title, and call-to-action buttons
2. **About** - Personal description and statistics
3. **Skills** - Technical skills organized by categories
4. **Projects** - Showcase of featured projects with images and descriptions
5. **Contact** - Contact form and social media links

## Getting Started

1. **Clone or download** the files to your local machine
2. **Open `index.html`** in your web browser to view the website
3. **Customize the content** by editing the HTML, CSS, and JavaScript files

## Customization Guide

### Personal Information

Edit the following in `index.html`:

#### Name and Title
```html
<!-- Change "John Doe" to your name -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Professional Title</p>
```

#### About Section
```html
<!-- Update the about text with your information -->
<div class="about-text">
    <p>Your personal description here...</p>
</div>
```

#### Contact Information
```html
<!-- Update contact details -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
```

### Profile Image

Replace the hero image URL in `index.html`:
```html
<img src="YOUR_IMAGE_URL_HERE" alt="Your Name">
```

**Recommended image specifications:**
- Size: 400x400 pixels
- Format: JPG or PNG
- Square aspect ratio
- High quality headshot

### Skills

Update the skills section with your technologies:
```html
<div class="skill-category">
    <h3>Your Category</h3>
    <div class="skill-items">
        <span class="skill-item">Your Skill 1</span>
        <span class="skill-item">Your Skill 2</span>
        <!-- Add more skills -->
    </div>
</div>
```

### Projects

Replace the example projects with your own:

1. **Project Images**: Use high-quality images (600x400 pixels recommended)
2. **Project Details**: Update title, description, and technologies
3. **Project Links**: Add your GitHub and live demo URLs

```html
<div class="project-card">
    <div class="project-image">
        <img src="YOUR_PROJECT_IMAGE" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="YOUR_GITHUB_URL" class="project-link">
                <i class="fab fa-github"></i>
            </a>
            <a href="YOUR_LIVE_DEMO_URL" class="project-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
</div>
```

### Social Media Links

Update social media URLs in the contact section:
```html
<div class="social-links">
    <a href="YOUR_GITHUB_URL" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="YOUR_LINKEDIN_URL" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links -->
</div>
```

### Colors and Styling

To change the color scheme, edit the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;    /* Main blue color */
--secondary-color: #7c3aed;  /* Purple accent */
--accent-color: #ffd700;     /* Gold highlight */

/* Text colors */
--text-dark: #1a202c;
--text-medium: #4a5568;
--text-light: #6b7280;

/* Background colors */
--bg-light: #f8fafc;
--bg-white: #ffffff;
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Use WebP Format**: For better compression (optional)
3. **Minimize HTTP Requests**: Keep external resources minimal
4. **Enable Gzip**: On your web server for faster loading

## Deployment

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `username.github.io/repository-name`

### Netlify (Free)
1. Sign up at netlify.com
2. Drag and drop your project folder
3. Your site will be live instantly

### Other Options
- Vercel
- Firebase Hosting
- Traditional web hosting

## Contact Form Setup

The contact form currently shows a success message but doesn't actually send emails. To make it functional:

### Option 1: Formspree (Recommended for beginners)
1. Sign up at formspree.io
2. Create a new form
3. Update the form action in HTML:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Netlify Forms (If hosting on Netlify)
Add `netlify` attribute to your form:
```html
<form class="contact-form" netlify>
```

### Option 3: Custom Backend
Implement your own backend with Node.js, PHP, or Python to handle form submissions.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:

1. Check this README first
2. Search for solutions online
3. Ask for help in developer communities
4. Consider hiring a developer for complex customizations

## Credits

- Icons: Font Awesome
- Fonts: Google Fonts (Inter)
- Images: Unsplash (for examples)

---

**Happy coding! 🚀**

Remember to update this README file with your own information and remove the example content. 