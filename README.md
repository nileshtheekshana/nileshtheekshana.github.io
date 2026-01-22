# Nilesh's Portfolio Website

A modern, responsive portfolio website for a web developer, built with HTML, CSS, and JavaScript.

## ✨ Features

- **Modern UI Design** - Clean, dark theme with gradient accents and smooth animations
- **Fully Responsive** - Works beautifully on desktop, tablet, and mobile devices
- **Interactive Elements**:
  - Custom cursor (desktop only)
  - Typing animation for role titles
  - Smooth scroll animations
  - Skill progress bars
  - Counter animations
  - Parallax background effects
- **Sections**:
  - Hero section with animated code window
  - About section with stats
  - Skills section with technology cards
  - Projects section featuring your websites
  - Contact section with form
- **Optimized for GitHub Pages** - No build process required!

## 🚀 Quick Deploy to GitHub Pages

1. **Create a new repository on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Name it `username.github.io` (replace `username` with your GitHub username) for a user site
   - Or use any name for a project site

2. **Push your code**
   ```bash
   cd /home/nilesh/Desktop/portfolio
   git init
   git add .
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to **Settings** > **Pages**
   - Under "Source", select **main** branch
   - Click **Save**
   - Your site will be live at `https://YOUR_USERNAME.github.io/` or `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## 📁 Project Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styles and animations
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🎨 Customization

### Update Personal Information

1. **Name & Role**: Edit the hero section in `index.html`
2. **About Text**: Update the about section with your story
3. **Skills**: Modify skill cards and progress percentages
4. **Projects**: Update project details with your actual projects
5. **Contact**: Change email and social links

### Colors & Styling

Edit CSS variables in `styles.css`:

```css
:root {
    --primary: #6366f1;        /* Main accent color */
    --secondary: #10b981;      /* Secondary accent */
    --dark: #0f172a;           /* Background color */
    --text: #e2e8f0;           /* Text color */
}
```

### Add Your Profile Picture

Replace the icon placeholder in the about section with your image:

```html
<div class="image-placeholder">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```

### Add Project Screenshots

Replace project placeholders with actual screenshots:

```html
<div class="project-image">
    <img src="project-screenshot.jpg" alt="Project Name">
    <!-- ... overlay code -->
</div>
```

## 📧 Contact Form Setup

For the contact form to work on GitHub Pages, use one of these services:

### Option 1: Formspree (Recommended)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form
3. Update the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Option 2: EmailJS
1. Sign up at [emailjs.com](https://emailjs.com)
2. Follow their setup guide
3. Add their SDK and update `script.js`

## 🌐 Live Preview

Open `index.html` in your browser to preview locally.

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📄 License

Free to use and modify for personal projects.

---

Made with ❤️ by Nilesh
