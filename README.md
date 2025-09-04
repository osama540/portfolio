# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This portfolio includes all the essential sections you need to showcase your skills, projects, and professional information.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Skills Visualization**: Animated skill bars with progress indicators
- **Project Showcase**: Beautiful project cards with technology tags
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## Sections Included

1. **Header Section**: Navigation with your name and tagline
2. **Hero Section**: Eye-catching introduction with call-to-action
3. **About Section**: Personal information with statistics
4. **Skills Section**: Categorized skills with progress bars
5. **Projects Section**: Featured projects with descriptions and links
6. **Resume Section**: Download link for your resume
7. **Contact Section**: Contact information and contact form
8. **Footer**: Copyright and social links

## How to Customize

### 1. Personal Information
Edit the `index.html` file to replace the placeholder content:

- **Name**: Replace "John Doe" with your name
- **Tagline**: Update the tagline in the header
- **About Section**: Replace the placeholder text and image
- **Contact Information**: Update email, phone, location, and social media links

### 2. Profile Image
Replace the placeholder image URL in the About section:
```html
<img src="your-image-url.jpg" alt="Your Name">
```

### 3. Skills
Update the skills section with your actual skills and proficiency levels:
```html
<div class="skill-item">
    <span class="skill-name">Your Skill</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 4. Projects
Replace the sample projects with your actual projects:
```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="live-demo-url" class="project-link">Live Demo</a>
            <a href="github-url" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

### 5. Resume
Add your actual resume PDF file and update the link:
```html
<a href="path/to/your-resume.pdf" class="resume-download">
    Download Resume (PDF)
</a>
```

### 6. Colors and Styling
Customize the color scheme by editing the CSS variables in `styles.css`:
- Primary color: `#4F46E5`
- Secondary color: `#7C3AED`
- Background colors: `#F9FAFB`, `#FFFFFF`
- Text colors: `#1F2937`, `#6B7280`

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images and assets
- Smooth scrolling and animations
- Lazy loading for better performance
- Responsive images
- Minimal JavaScript for fast loading

## Getting Started

1. **Download or Clone**: Get the files to your local machine
2. **Customize Content**: Edit the HTML file with your information
3. **Add Images**: Replace placeholder images with your own
4. **Test Locally**: Open `index.html` in your browser
5. **Deploy**: Upload to your web hosting service

## Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository
2. Vercel will automatically deploy your site

## Customization Tips

### Adding More Sections
To add new sections, follow this pattern:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Adding Animations
The portfolio includes several CSS animations. You can add more by:
1. Creating keyframes in CSS
2. Adding animation classes to elements
3. Using JavaScript for scroll-triggered animations

### SEO Optimization
- Add meta descriptions
- Include Open Graph tags
- Optimize images with alt text
- Use semantic HTML elements

## Support

If you need help customizing your portfolio:
1. Check the HTML structure for guidance
2. Review the CSS comments for styling options
3. Test changes in different browsers
4. Validate your HTML and CSS

## License

This portfolio template is free to use for personal and commercial projects.

---

**Happy Coding!** 🚀 
