# Subodh Sonar - Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This website showcases professional experience, skills, and contact information in an elegant and user-friendly design.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile navigation, and form validation
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized for performance with minimal dependencies

## 📁 File Structure

```
subodh122.github.io/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A GitHub account
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Setup Instructions

1. **Clone or Download**: This repository should already be in your GitHub Pages repository
2. **Customize Content**: Update the content in `index.html` with your personal information
3. **Deploy**: Push your changes to GitHub - the site will be available at `https://subodh122.github.io`

## 🎨 Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Hero Section (Lines 45-55)
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Title & Description</p>
<p class="hero-description">
    Your personal description here...
</p>
```

#### About Section (Lines 75-85)
```html
<p>
    Update your about me text here...
</p>
```

#### Experience Section (Lines 105-140)
Replace the timeline items with your actual work experience:
```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p class="timeline-date">2022 - Present</p>
        <ul>
            <li>Your responsibility 1</li>
            <li>Your responsibility 2</li>
        </ul>
    </div>
</div>
```

#### Skills Section (Lines 150-200)
Update the skills with your actual technical skills:
```html
<div class="skill-category">
    <h3>Category Name</h3>
    <div class="skill-items">
        <span class="skill-item">Skill 1</span>
        <span class="skill-item">Skill 2</span>
    </div>
</div>
```

#### Contact Section (Lines 220-240)
Update your contact information:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
```

### Styling Customization

#### Colors
Update the color scheme in `styles.css`:
- Primary Blue: `#2563eb`
- Accent Yellow: `#fbbf24`
- Text Dark: `#1f2937`
- Text Light: `#6b7280`

#### Fonts
The website uses Inter font from Google Fonts. You can change it by updating the font import in `index.html` and the font-family in `styles.css`.

### Profile Picture

Replace the placeholder icon with your actual profile picture:
1. Add your image to the repository
2. Update the hero section in `index.html`:
```html
<div class="hero-image">
    <img src="your-image.jpg" alt="Your Name" class="profile-image">
</div>
```
3. Add CSS for the image in `styles.css`:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
}
```

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- Mobile navigation menu
- Responsive grid layouts
- Optimized typography for small screens
- Touch-friendly buttons and links

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Performance Features
- Optimized images and assets
- Minimal JavaScript dependencies
- Efficient CSS animations
- Fast loading times

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Email format checking
- Success message display
- Form reset after submission

**Note**: The form currently shows a success message but doesn't actually send emails. To enable email functionality, you'll need to integrate with a service like:
- Formspree
- Netlify Forms
- EmailJS
- Custom backend solution

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Push your changes to the main branch
2. Go to your repository settings
3. Enable GitHub Pages
4. Your site will be available at `https://subodh122.github.io`

### Other Hosting Options
- Netlify
- Vercel
- AWS S3
- Any web hosting service

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you need help customizing this portfolio website, feel free to:
- Open an issue on GitHub
- Check the documentation above
- Review the code comments for guidance

---

**Happy coding! 🎉** 