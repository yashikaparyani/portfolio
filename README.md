# Yashika Paryani - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases your professional experience, projects, and skills in an attractive and interactive format.

## Features

- 🎨 **Modern Design**: Clean, professional design with gradient backgrounds and smooth animations
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Interactive Elements**: Smooth scrolling, hover effects, and dynamic content
- 🖼️ **Profile Image Upload**: Click on the placeholder to upload your profile picture
- 📧 **Contact Form**: Functional contact form with validation
- 🎯 **Smooth Navigation**: Fixed navigation bar with active section highlighting
- 🌟 **Animations**: Scroll-triggered animations and typing effects

## Sections Included

1. **Hero Section**: Introduction with profile image and call-to-action buttons
2. **About Section**: Personal description and statistics
3. **Experience Section**: Timeline-based work experience display
4. **Projects Section**: Showcase of your projects with technology tags
5. **Skills Section**: Organized display of your technical skills
6. **Contact Section**: Contact information and contact form

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Download or clone this repository
2. Open `index.html` in your web browser
3. The website should load immediately with all features working

### Customization Guide

#### 1. Personal Information

Edit the following sections in `index.html`:

- **Name**: Update the hero title and page title
- **Profile Image**: Click on the placeholder image in the hero section to upload your photo
- **Contact Information**: Update email, phone, and location in the contact section
- **Social Links**: Add your social media profiles

#### 2. Experience Section

Replace the placeholder experience entries with your actual work history:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="duration">2023 - Present</span>
        </div>
        <p class="timeline-description">
            • Your responsibilities and achievements<br>
            • Key projects you worked on<br>
            • Technologies you used
        </p>
    </div>
</div>
```

#### 3. Projects Section

Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project screenshot here -->
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description and key features</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-live-demo-url" class="project-link">Live Demo</a>
            <a href="your-github-url" class="project-link">Code</a>
        </div>
    </div>
</div>
```

#### 4. Skills Section

Customize the skills based on your expertise:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

#### 5. Styling Customization

Modify `styles.css` to change colors, fonts, and layout:

- **Primary Colors**: Update the gradient colors in the hero section
- **Font**: Change the font family in the body selector
- **Spacing**: Adjust padding and margins as needed

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── profile-image.jpg   # Your profile image (add this)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Features in Detail

### Profile Image Upload
- Click on the placeholder image in the hero section
- Select an image file from your computer
- The image will be displayed immediately (stored locally)

### Contact Form
- Validates all required fields
- Email format validation
- Success message on submission
- Form resets after successful submission

### Responsive Design
- Mobile-first approach
- Hamburger menu for mobile devices
- Optimized layouts for all screen sizes

### Animations
- Scroll-triggered fade-in animations
- Hover effects on cards and buttons
- Typing animation for the hero title
- Smooth transitions throughout

## Customization Tips

1. **Colors**: The website uses a purple-blue gradient theme. You can change this in the CSS variables or gradient definitions.

2. **Content**: Replace all placeholder text with your actual information from your resume.

3. **Images**: Add project screenshots to make the projects section more visually appealing.

4. **Links**: Update all project links and social media links to point to your actual profiles.

5. **SEO**: Add meta tags and descriptions for better search engine optimization.

## Deployment

To deploy your portfolio:

1. **GitHub Pages**: Upload to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop your folder to Netlify for instant deployment
3. **Vercel**: Connect your repository to Vercel for automatic deployments
4. **Traditional Hosting**: Upload files to any web hosting service

## Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS classes for styling options
3. Modify the JavaScript for additional functionality

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Note**: Remember to replace all placeholder content with your actual information from your resume. The website is designed to be easily customizable while maintaining a professional appearance. 