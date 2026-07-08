# Professional Fullstack Web Developer Portfolio

A modern, responsive portfolio website built with Jekyll and SCSS. Designed to showcase your fullstack web development skills and projects.

## 🎯 Features

✨ **Modern Design**
- Clean, professional aesthetic with smooth animations
- Responsive grid layouts for mobile, tablet, and desktop
- Dark mode support built-in

🚀 **Portfolio Sections**
- **Home**: Compelling hero section with call-to-action
- **Projects**: Detailed project showcase with tech stacks
- **About**: Professional bio, skills, and experience overview
- **Contact**: Easy email contact integration

💻 **Technical Highlights**
- Fullstack skills presentation (Frontend, Backend, Database, DevOps)
- Project cards with technology tags
- Experience/services overview
- Professional footer with contact links

## 📋 Quick Start

### Prerequisites
- Ruby and Bundler installed
- Jekyll knowledge (basic)

### Installation & Running

```bash
# Install dependencies
bundle install

# Build the site
bundle exec jekyll build

# Serve locally with live reload
bundle exec jekyll serve --livereload
```

Visit `http://localhost:4000` in your browser.

## 🎨 Customization Guide

### 1. **Update Site Configuration** (`_config.yml`)

```yaml
title: Your Name - Your Title
email: your.email@example.com
description: Your professional tagline here
github_username: your-github-username
twitter_username: your-twitter-handle  # optional
```

### 2. **Update Homepage** (`index.md`)

- Modify the hero section title and description
- Update the featured projects section with your actual projects
- Update skills to match your expertise

### 3. **Update About Page** (`about.md`)

- Add your professional bio
- Update skills sections with technologies you use
- Add your GitHub and social media links

### 4. **Update Projects Page** (`projects.md`)

Add your own projects by duplicating the project-item structure:

```html
<div class="project-item">
  <div class="project-item-header">
    <h3>Your Project Name</h3>
    <span class="project-status">Completed/Active</span>
  </div>
  <p class="project-description">Project description...</p>
  <!-- Add project details, tech tags, and links -->
</div>
```

### 5. **Customize Colors** (`_sass/_variables.scss`)

Update the color scheme in the `:root` CSS variables:

```scss
:root {
  --primary-color: #d17171;      /* Main accent color */
  --bg-color: #ffffff;            /* Background */
  --text-color: #313131;          /* Text color */
  --secondary-color: #dbb44a;    /* Highlight color */
}
```

### 6. **Update Footer** (`_includes/footer.html`)

- Add your correct email
- Update social media links
- Customize footer text

## 📁 File Structure

```
├── _config.yml              # Site configuration
├── _includes/
│   ├── navigation.html      # Top navigation bar
│   └── footer.html          # Footer content
├── _layouts/
│   ├── default.html         # Main layout
│   ├── page.html            # Page layout
│   └── post.html            # Blog post layout
├── _sass/                   # SCSS stylesheets
│   ├── _base.scss           # Base styles
│   ├── _layout.scss         # Layout styles
│   ├── _navbar.scss         # Navigation styles
│   ├── _variables.scss      # Color variables
│   └── _liquid_glass.scss   # Additional effects
├── assets/css/main.scss     # Main CSS entry point
├── index.md                 # Homepage
├── about.md                 # About page
└── projects.md              # Projects page
```

## 🎯 Content Tips

### Projects
For each project, include:
- Clear, descriptive title
- Detailed description (what problem it solves)
- Frontend technologies used
- Backend technologies used
- Database/data storage solution
- Deployment method
- Link to GitHub or live demo

### Skills
Organize skills by category:
- Frontend Development (languages, frameworks, tools)
- Backend Development (runtimes, frameworks, languages)
- Database & Tools (SQL, NoSQL, version control)
- Cloud & DevOps (hosting, CI/CD, containerization)

### About Section
Include:
- Professional bio (2-3 paragraphs)
- Quick facts (location, experience level, specialization)
- Technical skills breakdown
- Services/what you offer
- Call-to-action for contact

## 🚀 Deployment

### Option 1: GitHub Pages
```bash
# Push to GitHub with gh-pages branch
git push origin main
```

### Option 2: Netlify
1. Connect your GitHub repository to Netlify
2. Build command: `bundle exec jekyll build`
3. Publish directory: `_site`

### Option 3: Vercel
1. Import project from GitHub
2. Build command: `bundle exec jekyll build`
3. Output directory: `_site`

## 🌙 Dark Mode

Dark mode is automatically enabled based on system preferences. No additional setup needed!

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- Mobile (< 480px)
- Tablet (480px - 768px)
- Desktop (> 768px)

## 🎨 Styling System

The site uses:
- **SCSS** for styling with variables and mixins
- **CSS Grid** for layouts
- **Flexbox** for component layouts
- **CSS Variables** for theming
- **Animations** for smooth transitions

## 📚 Resources

- [Jekyll Documentation](https://jekyllrb.com/)
- [SCSS Guide](https://sass-lang.com/guide)
- [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

## 🤝 Contributing

Feel free to customize this template for your needs. Some ideas:
- Add a blog section with Jekyll posts
- Include testimonials section
- Add contact form
- Integrate with services like Formspree for email
- Add analytics tracking

## 📄 License

This portfolio template is free to use and modify for your personal use.

## ❓ Troubleshooting

**Site not building?**
```bash
# Ensure gems are installed
bundle install

# Clear Jekyll cache
rm -rf _site .jekyll-cache
```

**Styles not loading?**
- Clear browser cache (Cmd+Shift+R on Mac)
- Check that main.scss imports all partials
- Verify CSS file is in assets/css/

**Navigation not working?**
- Ensure page permalinks match navigation links
- Check `_includes/navigation.html` for correct URLs

---

**Ready to showcase your skills?** Start by updating `_config.yml` and adding your own content! 🚀
