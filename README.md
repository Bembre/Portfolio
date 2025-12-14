# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, JavaScript, and Bootstrap. Features a unique design with smooth animations and interactive elements.

## Features

- 🎨 **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- 🌙 **Dark/Light Theme**: Toggle between dark and light themes with smooth transitions
- ✨ **Particle Effects**: Interactive particle system in the hero section
- 📱 **Responsive**: Fully responsive design that works on all devices
- ⚡ **Interactive**: Smooth scrolling, hover effects, and dynamic animations
- 🎯 **Sections**: Home, About, Skills, Projects, and Contact sections
- 📧 **Contact Form**: Functional contact form with validation
- 🎭 **Advanced Animations**: Staggered animations and intersection observer effects
- 🚀 **Performance**: Optimized for fast loading and smooth user experience
- 💾 **Theme Persistence**: Remembers your theme preference

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with CSS Grid, Flexbox, and animations
- **JavaScript**: Interactive features and animations
- **Bootstrap 5**: Responsive framework and components
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Poppins)

## Customization Guide

### 1. Personal Information
Update the following in `index.html`:

```html
<!-- Replace "Your Name" with your actual name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update contact information -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your City, Country</p>
```

### 2. Social Media Links
Update the social media links in the hero section:

```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links as needed -->
</div>
```

### 3. Skills Section
Modify the skills in the skills section:

```html
<!-- Update skill names and progress percentages -->
<div class="skill-progress" data-width="90"></div>
```

### 4. Projects Section
Update your projects:

```html
<div class="project-card">
    <div class="project-content">
        <h4>Your Project Name</h4>
        <p>Project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

### 5. Colors and Styling
Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;    /* Main brand color */
    --secondary-color: #8b5cf6;  /* Secondary color */
    --accent-color: #06b6d4;     /* Accent color */
    /* Update other colors as needed */
}
```

## Free Deployment Options

### 1. GitHub Pages (Recommended)
1. Create a GitHub repository
2. Upload your files to the repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### 2. Netlify
1. Go to [netlify.com](https://netlify.com)
2. Sign up for a free account
3. Drag and drop your project folder
4. Your site will be live instantly with a custom URL

### 3. Vercel
1. Go to [vercel.com](https://vercel.com)
2. Sign up for a free account
3. Import your GitHub repository or upload files
4. Deploy with one click

### 4. Firebase Hosting
1. Go to [firebase.google.com](https://firebase.google.com)
2. Create a new project
3. Install Firebase CLI: `npm install -g firebase-tools`
4. Run `firebase init hosting`
5. Deploy with `firebase deploy`

### 5. Surge.sh
1. Install Surge: `npm install -g surge`
2. Run `surge` in your project directory
3. Follow the prompts to deploy

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Use WebP format and compress images
2. **Minify Files**: Minify CSS and JavaScript for production
3. **CDN**: Use CDN for external libraries
4. **Caching**: Enable browser caching for static assets

## SEO Optimization

1. Update the `<title>` tag with your name and profession
2. Add meta descriptions
3. Include alt text for images
4. Use semantic HTML structure
5. Add structured data markup

## Contact Form Setup

The contact form is currently set up for demonstration. To make it functional:

1. **Netlify Forms**: If using Netlify, add `netlify` attribute to the form
2. **Formspree**: Use Formspree service for form handling
3. **EmailJS**: Integrate EmailJS for client-side email sending
4. **Backend**: Create a simple backend API for form processing

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Happy Coding! 🚀**
