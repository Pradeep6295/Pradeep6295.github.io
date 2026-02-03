# Pradeep Kumar - Portfolio Website

A modern, professional portfolio website showcasing my skills and experience as a Software Engineer.

## 🚀 Live Demo

Your portfolio will be live at: `https://your-username.github.io/portfolio`

## ✨ Features

- **Modern Design**: Clean, professional dark theme with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Performance**: Optimized for fast loading and smooth scrolling
- **Sections**:
  - Hero section with code preview
  - Work experience timeline
  - Technical skills showcase
  - Featured projects
  - Contact information and form

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom animations & responsive design)
- Vanilla JavaScript
- Google Fonts (Syne & IBM Plex Mono)
- Formspree for contact form (optional)

## 📦 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `portfolio` or `your-username.github.io`)
4. Make it **Public**
5. Click "Create repository"

### Step 2: Upload Your Portfolio

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Initialize git in your project folder
git init

# Add your files
git add index.html

# Commit your files
git commit -m "Initial commit: Add portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment

Your site will be live at:
- If repo name is `portfolio`: `https://YOUR-USERNAME.github.io/portfolio`
- If repo name is `YOUR-USERNAME.github.io`: `https://YOUR-USERNAME.github.io`

## 📝 Customization

### Update Contact Form

To make the contact form work:

1. Go to [Formspree](https://formspree.io/)
2. Sign up for a free account
3. Create a new form
4. Copy your form endpoint
5. In `index.html`, find this line:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
6. Replace `YOUR_FORM_ID` with your actual Formspree form ID

### Update Personal Information

Search for these in `index.html` and update as needed:
- Email address
- Phone number
- LinkedIn URL
- Location
- Projects and descriptions

### Change Colors

Find the `:root` section in the CSS and modify these variables:
```css
:root {
    --bg-primary: #0a0e14;        /* Main background */
    --accent-primary: #00ff88;    /* Primary accent color */
    --accent-secondary: #0080ff;  /* Secondary accent color */
    /* ... other colors ... */
}
```

## 🎨 Design Features

- **Dark Theme**: Modern dark color scheme with bright accents
- **Animated Background**: Subtle grid animation
- **Smooth Transitions**: All interactions have smooth animations
- **Code Block**: Interactive code preview in hero section
- **Timeline**: Visual timeline for work experience
- **Hover Effects**: Interactive elements throughout
- **Scroll Animations**: Elements fade in as you scroll

## 📱 Responsive Design

The portfolio is fully responsive and tested on:
- Desktop (1920px and above)
- Laptop (1024px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This portfolio template is free to use and modify for your personal portfolio.

## 🤝 Contributing

Feel free to fork this repository and customize it for your own use!

## 📞 Contact

- **Email**: pradeepkumar7642@gmail.com
- **Phone**: +91 8563937642
- **LinkedIn**: [Pradeep Kumar](https://linkedin.com/in/pradeep-kumar-0b87aa209)
- **Location**: Delhi, India

---

Built with ❤️ by Pradeep Kumar
