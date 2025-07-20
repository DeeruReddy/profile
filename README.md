# Deeraj Reddy - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases your skills, projects, and professional journey with a beautiful and interactive design.

## Features

- 🎨 **Modern Design**: Clean and professional design with smooth animations
- 📱 **Responsive**: Fully responsive design that works on all devices
- ⚡ **Fast Loading**: Optimized for performance and fast loading times
- 🎯 **Interactive**: Smooth scrolling, hover effects, and animations
- 📧 **Contact Form**: Functional contact form with validation
- 🔧 **Easy Customization**: Simple to customize with your own content

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Projects Section**: Showcase of your work with technology tags
4. **Skills Section**: Visual representation of your technical skills
5. **Contact Section**: Contact information and contact form
6. **Footer**: Copyright and additional links

## Customization Guide

### Personal Information

1. **Update the title** in `index.html`:
   ```html
   <title>Your Name - Portfolio</title>
   ```

2. **Update your name** throughout the HTML file:
   - Hero section
   - Navigation logo
   - Footer

3. **Update contact information** in the contact section:
   - Email address
   - Phone number
   - Location
   - Social media links

### Projects

1. **Add your projects** in the projects section:
   - Update project titles
   - Add project descriptions
   - Update technology tags
   - Add links to live demos and code repositories

2. **Update project icons** by changing the Font Awesome classes:
   ```html
   <i class="fas fa-car"></i> <!-- Change to appropriate icon -->
   ```

### Skills

1. **Update skill categories** and individual skills
2. **Adjust skill percentages** by modifying the width in the CSS:
   ```css
   .skill-progress { width: 90%; } /* Change percentage */
   ```

### Styling

1. **Change colors** in `styles.css`:
   - Primary color: `#2563eb`
   - Secondary color: `#fbbf24`
   - Background gradients

2. **Update fonts** by changing the Google Fonts import in `index.html`

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
├── ParkingSystem.java  # Your Java project
└── LibraryManagementSystem.java  # Your Java project
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

### Option 1: GitHub Pages

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify

1. Create a Netlify account
2. Drag and drop your project folder to Netlify
3. Your site will be deployed automatically
4. You can set up a custom domain

### Option 3: Vercel

1. Create a Vercel account
2. Connect your GitHub repository
3. Deploy automatically on every push

## Customization Tips

### Adding a Profile Picture

1. Replace the Font Awesome icon in the hero section:
   ```html
   <div class="profile-image">
       <img src="path/to/your/image.jpg" alt="Your Name">
   </div>
   ```

2. Add CSS for the image:
   ```css
   .profile-image img {
       width: 200px;
       height: 200px;
       border-radius: 50%;
       object-fit: cover;
   }
   ```

### Adding More Sections

1. Create a new section in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu

### Changing Animations

1. Modify animation properties in `styles.css`
2. Update JavaScript animations in `script.js`

## Performance Optimization

1. **Optimize images** before uploading
2. **Minify CSS and JavaScript** for production
3. **Use a CDN** for external resources
4. **Enable compression** on your hosting provider

## SEO Optimization

1. **Add meta tags** in the HTML head:
   ```html
   <meta name="description" content="Your portfolio description">
   <meta name="keywords" content="your, keywords, here">
   ```

2. **Add Open Graph tags** for social media:
   ```html
   <meta property="og:title" content="Your Name - Portfolio">
   <meta property="og:description" content="Your description">
   <meta property="og:image" content="path/to/image.jpg">
   ```

## Contact Form Setup

The contact form currently simulates submission. To make it functional:

1. **Use a form service** like Formspree or Netlify Forms
2. **Set up a backend** to handle form submissions
3. **Use email services** like SendGrid or AWS SES

### Example with Formspree:

```html
<form action="https://formspree.io/f/your-form-id" method="POST" class="contact-form">
    <!-- form fields -->
</form>
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Note**: Remember to replace all placeholder content with your actual information before deploying your portfolio. 