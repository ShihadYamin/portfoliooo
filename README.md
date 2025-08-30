
#visit website----
    "https://portfolio-shihadyamin-two.vercel.app/"

# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases your skills, projects, and professional information in an elegant and user-friendly design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **SEO Friendly**: Semantic HTML structure
- **Fast Loading**: Optimized for performance

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Open the website**: Double-click on `index.html` to open it in your web browser
2. **Customize content**: Edit the HTML file to replace placeholder content with your information
3. **Modify styling**: Update the CSS file to change colors, fonts, and layout
4. **Add functionality**: Enhance the JavaScript file for additional features

## Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Full Stack Developer & Creative Problem Solver</p>
```

#### About Section
```html
<p>I'm a passionate developer with a love for creating meaningful digital experiences...</p>
```

#### Contact Information
```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### Skills and Technologies

Update the skills section to match your expertise:

```html
<div class="skill-item">
    <i class="fab fa-html5"></i>
    <span>HTML5</span>
</div>
```

### Projects

Replace the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### Social Media Links

Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="your-github" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

## Styling Customization

### Colors

The main color scheme is defined in `styles.css`. You can change the primary colors:

```css
/* Primary Blue */
--primary-color: #2563eb;
--primary-dark: #1d4ed8;

/* Accent Yellow */
--accent-color: #fbbf24;
--accent-dark: #f59e0b;

/* Gradient Background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Fonts

The website uses the Inter font family. You can change it by updating the Google Fonts link in the HTML head:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

And update the CSS:

```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## Adding Your Profile Picture

1. Add your profile picture to the project folder
2. Replace the placeholder in the hero section:

```html
<div class="hero-image">
    <img src="your-profile-picture.jpg" alt="Your Name" class="profile-image">
</div>
```

3. Add CSS for the profile image:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

## Adding Project Images

1. Add project screenshots to your project folder
2. Replace the placeholder icons with actual images:

```html
<div class="project-image">
    <img src="project-screenshot.jpg" alt="Project Name" class="project-img">
</div>
```

3. Add CSS for project images:

```css
.project-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## Contact Form Setup

The contact form currently shows an alert message. To make it functional:

1. **For Netlify**: Add `netlify` attribute to the form
2. **For Formspree**: Replace the form action with your Formspree endpoint
3. **For custom backend**: Update the JavaScript form submission handler

Example with Formspree:
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize images**: Compress images before adding them
2. **Minimize HTTP requests**: Combine CSS and JS files for production
3. **Use CDN**: The website already uses CDN for Font Awesome and Google Fonts
4. **Lazy loading**: Consider adding lazy loading for images if you have many

## Deployment

### GitHub Pages
1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually main)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. You'll get a custom URL

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. You'll get a custom URL

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio or have questions, feel free to:
- Check the code comments for guidance
- Modify the CSS variables for easy customization
- Add your own features and enhancements

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspiration: Modern web design principles

---


**Happy coding! 🚀** 
