# Avani Purohit - Portfolio Website html/css/js

A modern, responsive, and professional portfolio website for Avani Purohit, Full Stack Software Developer.

## 🌟 Features

### Design & User Experience
- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern Aesthetics**: Clean, professional design with gradient colors and smooth animations
- **Smooth Navigation**: Smooth scrolling and interactive navigation menu with hamburger toggle for mobile
- **Performance Optimized**: Fast loading with optimized assets and lazy loading

### Sections

1. **Navigation Bar**
   - Fixed header with smooth scroll links
   - Responsive hamburger menu for mobile devices
   - Gradient logo design

2. **Hero Section**
   - Eye-catching welcome message
   - Call-to-action buttons (View Work, Get in Touch)
   - Gradient background with smooth animations

3. **About Section**
   - Professional introduction
   - Key highlights about experience
   - Avatar placeholder with customizable content

4. **Skills Section**
   - Frontend Development skills (HTML, CSS, JavaScript, React, Vue.js)
   - Backend Development expertise (Node.js, Python, Django, APIs)
   - Tools & Technologies (Git, Docker, AWS, Databases)
   - Specializations (System Architecture, Optimization, Leadership)
   - Hover animations on skill cards

5. **Projects Section**
   - 6 featured projects with descriptions
   - Technology tags for each project
   - Links to demo and GitHub repositories
   - Hover effects with interactive cards

6. **Contact Section**
   - Contact form with validation
   - Contact information (Email, Location, LinkedIn)
   - Form submission handling

7. **Footer**
   - Social media links (GitHub, LinkedIn, Twitter, Email)
   - Copyright information

## 🛠️ Technologies Used

**Frontend:**
- HTML5 (Semantic markup)
- CSS3 (Grid, Flexbox, Animations, Gradients)
- JavaScript (ES6+)

**No External Dependencies:** Everything is built with vanilla HTML, CSS, and JavaScript - No frameworks required!

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with multi-column grids
- **Tablet**: Optimized for medium screens
- **Mobile**: Single column layout with hamburger navigation

## 🎨 Color Scheme

- **Primary Color**: `#6366f1` (Indigo)
- **Secondary Color**: `#8b5cf6` (Purple)
- **Accent Color**: `#ec4899` (Pink)
- **Dark Background**: `#0f172a`
- **Light Background**: `#f8fafc`

## 🚀 How to Use

### 1. Open in Browser
Simply open the `index.html` file in any modern web browser.

### 2. Customize Content
Edit the following sections in `index.html`:

**Personal Information:**
Replace placeholder details with your own:
- Name and title
- Professional descriptions
- Contact information

**About Section:**
- Update the description in the About section
- Replace the emoji avatar with a real image

**Skills:**
- Modify skill cards with your actual technical skills
- Add or remove skill categories as needed

**Projects:**
- Replace project details with your actual projects
- Update project links and descriptions
- Change emoji placeholders with actual project images

**Contact Information:**
- Update email address
- Update location
- Add your social media links

### 3. Add Real Images
Replace emoji placeholders with actual images:
```html
<!-- Instead of: -->
<div class="project-image">🚀</div>

<!-- Use: -->
<div class="project-image">
    <img src="path/to/image.jpg" alt="Project Name">
</div>
```

### 4. Connect Form Backend
The contact form currently shows an alert. To make it functional:
```javascript
// Replace the alert in contactForm submission with API call
fetch('/api/send-email', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ name, email, subject, message })
});
```

## 📋 File Structure

```
hehe/
├── index.html      # Main portfolio file (HTML + CSS + JavaScript)
└── README.md       # Documentation and customization guide
```

## ✨ Key Features Explained

### Smooth Scrolling
- All internal links scroll smoothly to their target sections
- Active section highlighting in navigation

### Animations
- Fade-in animations on scroll for cards
- Hover effects on buttons, cards, and links
- Smooth transitions on all interactive elements

### Mobile Responsiveness
- Hamburger menu toggles on mobile devices
- Responsive grid layouts that adapt to screen size
- Touch-friendly button and link sizes

### Accessibility
- Semantic HTML structure
- Proper form labels and validation
- Color contrast compliance

## 🔧 Customization Tips

### Change Color Scheme
Modify CSS variables in the `:root` selector to match your brand:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
}
```

### Add More Projects
Copy the project card section and modify with your details to showcase additional work.

### Modify Typography
Add custom fonts from Google Fonts or other font services to personalize the design.

## 🌐 Deployment Options

1. **GitHub Pages**: Push to a GitHub repository and enable Pages
2. **Netlify**: Drag and drop the folder for instant deployment
3. **Vercel**: Connect your git repository for automatic deployments
4. **Traditional Hosting**: Upload to any web server via FTP/SFTP

## 🚀 Quick Start

1. Clone or download this repository
2. Open `index.html` in a web browser
3. Edit the content with your personal information
4. Deploy to your preferred hosting platform

## 📞 Contact Information

Update these with your actual details:
- **Email**: your-email@example.com
- **LinkedIn**: [Your LinkedIn Profile]
- **GitHub**: [Your GitHub Profile]
- **Location**: Your City, Country

## 📄 License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Created with ❤️ as a professional portfolio template for software developers**

Start showcasing your amazing work today! 🚀
