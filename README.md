# Malick Arsalan - Portfolio Website

A modern, interactive, and responsive single-page portfolio website built with HTML, CSS, and jQuery.

## Features

✨ **Interactive Theme Toggle** - Light/Dark mode with persistent storage
📱 **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
🎨 **Modern UI/UX** - Beautiful gradient backgrounds and smooth animations
🎭 **Smooth Animations** - Fade-in effects, parallax scrolling, and hover animations
📊 **Interactive Elements** - Animated counters, ripple effects, and smooth scroll navigation
🔧 **Lightweight** - Pure HTML, CSS, and jQuery (no heavy frameworks)
♿ **Accessible** - Proper semantic HTML and keyboard navigation support

## File Structure

```
Arsalan Portfolio/
├── index.html          # Main HTML file
├── styles.css          # Complete styling and responsive design
├── script.js           # jQuery interactive functionality
├── Arsalan Pic.jpeg    # Profile picture
└── README.md           # This file
```

## Sections Included

1. **Home/Hero** - Eye-catching introduction with profile image
2. **About** - Personal introduction with statistics
3. **Services** - 6 key services offered (Native App Development, UI/UX Design, Backend Integration, App Optimization, Testing & QA, App Analytics)
4. **Skills** - Technical skills organized by categories (Languages, Frameworks, Tools, Other)
5. **Experience** - Timeline view of work experience
6. **Education** - Educational background and certifications
7. **Contact** - Contact information and social media links

## How to Use

1. **Open the Portfolio**
   - Simply open `index.html` in any web browser
   - Or use a local server for better performance

2. **Customization Guide**

### Update Personal Information

Open `index.html` and modify:

```html
<!-- Update name in navigation -->
<div class="logo">
    <h1>Your Name</h1>
</div>

<!-- Update hero section -->
<h1 class="fade-in">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="fade-in">Your Job Title | Your Subtitle</p>

<!-- Update contact information -->
<a href="mailto:your-email@example.com" class="contact-link">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</a>
```

### Update Profile Image

Replace `Arsalan Pic.jpeg` with your own image or update the reference:
```html
<img src="your-image-name.jpg" alt="Your Name" class="profile-img">
```

### Customize Services

Edit the services grid in `index.html`:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3>Your Service Title</h3>
    <p>Your service description</p>
</div>
```

### Update Skills

Modify the skills section with your actual skills:
```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <div class="skill-items">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
    </div>
</div>
```

### Update Experience & Education

Edit the timeline and education cards with your actual information.

### Update Social Links

Replace the social media links with your profiles:
```html
<a href="https://linkedin.com/in/yourprofile" class="social-icon" title="LinkedIn">
    <i class="fab fa-linkedin"></i>
</a>
```

## Color Scheme

The portfolio uses CSS variables for easy customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Indigo */
    --primary-dark: #4f46e5;       /* Darker Indigo */
    --primary-light: #818cf8;      /* Light Indigo */
    --secondary-color: #ec4899;    /* Pink */
    --accent-color: #f59e0b;       /* Amber */
    --text-dark: #1f2937;          /* Dark Gray */
    --text-light: #6b7280;         /* Light Gray */
    --bg-light: #f9fafb;           /* Very Light Gray */
    --bg-white: #ffffff;           /* White */
    --border-color: #e5e7eb;       /* Border Gray */
}
```

Change these values to match your brand colors.

## Dark Mode Colors

Dark mode colors are defined in the `[data-theme="dark"]` selector. Customize them as needed.

## Interactive Features

### 1. Theme Toggle
Click the moon/sun icon in the footer to switch between light and dark modes. Your preference is saved automatically.

### 2. Navigation
- Desktop: Click navigation links in the navbar
- Mobile: Click the hamburger menu to toggle navigation

### 3. Smooth Scrolling
Click any navigation link to smoothly scroll to that section.

### 4. Animations
- Elements fade in as you scroll
- Hover effects on service cards, skills, and buttons
- Counter animation on statistics
- Ripple effect on button clicks

### 5. Responsive Design
The site automatically adjusts for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (480px - 767px)
- Small Mobile (<480px)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Required Libraries

- Font Awesome 6.0.0 (for icons)
- jQuery 3.6.0 (for interactive functionality)

Both are loaded from CDN, so no installation needed!

## Performance Tips

1. **Optimize Images** - Use compressed images for better load time
2. **Lazy Loading** - Images are lazy-loaded automatically
3. **Minify CSS/JS** - Consider minifying for production
4. **Use CDN** - Serve from a CDN for better performance

## Customization Examples

### Change Primary Color
```css
:root {
    --primary-color: #10b981;  /* Change to green */
}
```

### Add More Services
Simply copy a service card and modify:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>New Service</h3>
    <p>Description of your service</p>
</div>
```

### Modify Animation Speed
Look for `transition: var(--transition)` and adjust:
```css
--transition: all 0.5s ease;  /* Change 0.3s to 0.5s or any value */
```

## Troubleshooting

### Images not showing?
- Ensure image file is in the same directory as `index.html`
- Check the image filename matches exactly (case-sensitive)
- Use the correct file extension (.jpg, .jpeg, .png, etc.)

### Icons not displaying?
- The Font Awesome CDN might be blocked
- Check browser console for errors
- Ensure you have internet connection

### Styles not loading?
- Make sure `styles.css` is in the same directory as `index.html`
- Check the CSS file hasn't been moved
- Clear browser cache (Ctrl+Shift+Delete)

### Dark mode not working?
- Check browser console for JavaScript errors
- Ensure `script.js` is loaded properly
- Try clearing localStorage: `localStorage.clear()` in console

## License

This portfolio template is free to use and modify. Customize it with your own information and share with the world!

## Support

For any issues or questions, refer to the code comments in the HTML, CSS, and JavaScript files for detailed explanations.

---

**Built with ❤️ using HTML, CSS, and jQuery**

Happy showcasing! 🚀
