# Rohan Desai - CV Website

A modern, responsive CV website built with HTML, CSS, and JavaScript. Deployed on GitHub Pages.

## Features

- **Professional Design**: Clean, modern UI with smooth animations
- **Responsive Layout**: Fully responsive on mobile, tablet, and desktop
- **Projects Showcase**: Featured projects section with links to live demos and GitHub repositories
- **Skills Display**: Organized skills categories
- **Smooth Navigation**: Smooth scrolling and active navigation highlighting
- **Social Links**: Easy integration with GitHub, LinkedIn, Twitter, and Email

## Structure

```
CV_website/
├── index.html       # Main HTML file
├── style.css        # Styling and responsive design
├── script.js        # JavaScript for interactivity
├── README.md        # This file
└── .gitignore       # Git ignore file
```

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CV_website.git
   cd CV_website
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Or using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

### Customization

Edit `index.html` to update:
- Your name and title
- About section content
- Skills section
- Project details (title, description, links)
- Social media links
- Contact information

Edit `style.css` to customize:
- Colors (change CSS variables in `:root`)
- Fonts
- Spacing and layout
- Animations

## Deploying to GitHub Pages

1. Create a new repository named `yourusername.github.io` (replace `yourusername` with your GitHub username)

2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: CV website"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. Your site will be live at `https://yourusername.github.io`

### Alternative: Deploy to a project repository

If you want to deploy to a regular repository:

1. In GitHub repository settings, go to "Pages"
2. Under "Source", select "Deploy from a branch"
3. Choose `main` branch and `/root` directory
4. Your site will be available at `https://yourusername.github.io/CV_website/`

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables and Grid/Flexbox
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icon library for social links
- **GitHub Pages**: Free hosting

## Portfolio Projects

Each project card displays:
- **Title**: Name of the project
- **Tags**: Technologies used
- **Description**: Brief project description
- **Live Demo Link**: Button to visit the live demo
- **GitHub Link**: Button to view the source code

## Customization Guide

### Update Project Cards

In `index.html`, find the projects section and update:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <div class="project-tags">
            <span class="tag">Technology1</span>
            <span class="tag">Technology2</span>
        </div>
    </div>
    <p class="project-description">
        Your project description here
    </p>
    <div class="project-links">
        <a href="https://your-live-demo-url.com" target="_blank" class="project-link live-demo">
            <i class="fas fa-arrow-up-right-from-square"></i> Live Demo
        </a>
        <a href="https://github.com/yourusername/project-name" target="_blank" class="project-link github-link">
            <i class="fab fa-github"></i> View Code
        </a>
    </div>
</div>
```

### Update Colors

In `style.css`, modify the CSS variables:

```css
:root {
    --primary-color: #3b82f6;      /* Main brand color */
    --secondary-color: #10b981;    /* Accent color */
    --dark-bg: #0f172a;
    --light-bg: #f8fafc;
    --text-dark: #1e293b;
    --text-light: #64748b;
}
```

### Update Social Links

In `index.html`, update the contact section with your actual links:

```html
<a href="https://github.com/yourusername" target="_blank" class="social-link">
    <i class="fab fa-github"></i> GitHub
</a>
```

## Browser Support

- Chrome/Edge: Latest versions
- Firefox: Latest versions
- Safari: Latest versions
- Mobile browsers: iOS Safari, Chrome Mobile

## Performance

- Fully optimized for fast loading
- No external dependencies (except Font Awesome icons)
- Minimal CSS and JavaScript
- Responsive images support

## License

This project is open source and available under the MIT License.

## Author

**Rohan Desai**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [linkedin.com/in/yourusername](https://linkedin.com/in/yourusername)
- Email: your.email@example.com

## Contributing

If you'd like to improve this template, feel free to fork and submit pull requests!

---

Made with ❤️ by Rohan Desai
