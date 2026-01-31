# Deepashree V - Portfolio Website

A modern, responsive personal portfolio website showcasing skills, experience, and projects. Built with HTML5, CSS3, and vanilla JavaScript.

## 🌟 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern Animations** - Smooth scroll animations, fade-in effects, and interactive elements
- **Dark Theme** - Professional dark color scheme with cyan/blue accents
- **Interactive Components** - Mobile navigation menu, smooth scrolling, and form validation
- **Optimized Performance** - Clean code with CSS animations and minimal dependencies

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet with all styles
├── script.js           # JavaScript for interactivity
└── README.md          # Documentation
```

## 🚀 Getting Started

### Option 1: Open Locally
1. Download all files to a folder
2. Open `index.html` in your web browser
3. That's it! The website will run locally

### Option 2: Deploy Online
You can deploy this website to various hosting platforms:

#### GitHub Pages
1. Create a new GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

#### Netlify (Recommended)
1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your folder
3. Your site will be live instantly!

#### Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload files
3. Deploy with one click

## 🎨 Customization Guide

### Update Personal Information

**In `index.html`:**

1. **Hero Section** (Lines 40-60):
   - Change name and title
   - Update subtitle description

2. **About Section** (Lines 63-135):
   - Modify overview text
   - Update contact information (email, phone)
   - Change statistics (CGPA, internships, certifications, graduation year)

3. **Skills Section** (Lines 138-280):
   - Add/remove tech stack items
   - Update competencies

4. **Experience Section** (Lines 283-370):
   - Add your work experience
   - Update company names, dates, and descriptions

5. **Contact Section** (Lines 373-445):
   - Update email and phone
   - Modify location

### Customize Colors

**In `style.css`** (Lines 1-12), modify CSS variables:

```css
:root {
    --primary-color: #38bdf8;      /* Main accent color */
    --secondary-color: #0ea5e9;    /* Secondary accent */
    --dark-bg: #0a0e1a;           /* Background color */
    --accent: #38bdf8;            /* Highlight color */
}
```

### Add Your Own Projects

Create a new "Projects" section in `index.html` before the Contact section:

```html
<section class="projects" id="projects">
    <div class="container">
        <h2 class="section-title">Projects.</h2>
        <div class="stats-grid">
            <div class="stat-card">
                <h3>Project Name</h3>
                <p>Project description</p>
                <a href="#" class="btn btn-primary">View Project</a>
            </div>
            <!-- Add more project cards -->
        </div>
    </div>
</section>
```

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 968px
- **Desktop**: > 968px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Customization Tips

1. **Images**: Add your profile photo by creating an `images/` folder and updating the image sources
2. **Resume**: Add your resume PDF file and update the download link
3. **Social Links**: Update GitHub and LinkedIn URLs in the navigation and footer
4. **Favicon**: Add a favicon by placing `favicon.ico` in the root folder and adding this to `<head>`:
   ```html
   <link rel="icon" type="image/x-icon" href="favicon.ico">
   ```

## 🔧 Advanced Features to Add

### Add a Blog Section
Create a new section with blog cards linking to your articles

### Add a Projects Gallery
Include screenshots and live demos of your projects

### Integrate Contact Form
Connect the form to:
- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- [Web3Forms](https://web3forms.com/)

### Add Analytics
Track visitors with:
- Google Analytics
- Plausible Analytics
- Simple Analytics

## 📧 Contact Form Setup

The contact form currently shows an alert. To make it functional:

1. **Using Formspree** (Easy):
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

2. **Using EmailJS** (Free):
   - Sign up at emailjs.com
   - Add their script
   - Update the form submission handler in `script.js`

## 🎨 Font Information

This website uses:
- **Display Font**: Playfair Display (headings)
- **Body Font**: DM Sans (text)

Both are loaded from Google Fonts.

## 📄 License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## 🤝 Support

If you need help customizing this template:
1. Check the code comments in each file
2. Refer to this README
3. Search for HTML/CSS tutorials online

## 🎉 Credits

Created by Claude (Anthropic AI) based on requirements from Deepashree V.

---

**Built with ❤️ using HTML, CSS, and JavaScript**
