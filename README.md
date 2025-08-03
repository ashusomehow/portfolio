# Z - Software Engineer Portfolio

A modern, responsive portfolio website with a dark theme and purple glow effects, inspired by the design shown in the reference image.

## Features

- **Dark Theme Design**: Modern dark background with purple accent colors
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Interactive Elements**: Hover effects, smooth scrolling, and animated components
- **Professional Sections**: Hero, Work Experience, Skills, Projects, and Contact sections

## File Structure

```
portfolio/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript interactions
├── README.md           # This file
└── portfolio-assets/   # Design assets and images
    ├── Logo.png
    ├── Me.png
    ├── Portfolio-1.png
    ├── Skills.png
    └── ... (other assets)
```

## Customization Guide

### 1. Personal Information
Edit the following sections in `index.html`:

- **Name and Title**: Update the main title and role
- **Current Position**: Change the company name and position
- **About Text**: Modify the description about yourself
- **Contact Information**: Update email and social media links

### 2. Work Experience
In the Work Experience section, you can:
- Add more project cards by duplicating the `.work-card` div
- Update project titles and descriptions
- Add actual project links to the "View Project" buttons
- Replace project icons with your own images

### 3. Skills Section
- Replace the `Skills.png` image with your own skills visualization
- Or create individual skill icons and arrange them in a grid

### 4. Example Projects
- Update project descriptions with your actual projects
- Add real project screenshots or mockups
- Link to live demos or GitHub repositories

### 5. Contact Information
- Update the email address
- Add your actual social media links (LinkedIn, GitHub, etc.)
- Modify the contact message

### 6. Colors and Styling
The main color scheme uses:
- **Primary Purple**: `#a855f7`
- **Background**: Dark gradient from `#0a0a0a` to `#16213e`
- **Text**: White and light gray variations

You can customize these colors in `styles.css` by changing the CSS custom properties.

## How to Use

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local Development**: Use a local server for better performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```
3. **Deploy**: Upload all files to your web hosting service

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Features

- Optimized images and assets
- Smooth scrolling navigation
- Intersection Observer for performance animations
- Responsive design for all screen sizes
- Minimal JavaScript for fast loading

## Customization Tips

1. **Images**: Replace the placeholder images in `portfolio-assets/` with your own
2. **Content**: Update all text content to reflect your personal information
3. **Projects**: Add your actual projects with screenshots and links
4. **Skills**: Create a custom skills section that matches your expertise
5. **Contact**: Add your real contact information and social media links

## Adding New Sections

To add new sections, follow this pattern:

```html
<section class="new-section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

And add corresponding CSS:

```css
.new-section {
    padding: 6rem 0;
    /* Your styles here */
}
```

## Troubleshooting

- **Images not loading**: Check that all image paths are correct
- **Animations not working**: Ensure JavaScript is enabled
- **Mobile issues**: Test on different devices and screen sizes
- **Performance**: Optimize images and reduce file sizes if needed

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Note**: This portfolio is based on the design reference provided. Feel free to customize it to match your personal brand and style! 