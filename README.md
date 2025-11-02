# Personal Homepage - README

# 🌐 Personal Homepage

A modern, responsive personal homepage with Google-inspired design, featuring quick access to your favorite apps and websites.

![Homepage Screenshot](https://via.placeholder.com/800x400/1a1a2e/ffffff?text=Personal+Homepage)

## ✨ Features

- **🎨 Modern UI Design** - Clean, dark-themed interface with Google-inspired elements
- **📱 Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **🌙 Dark/Light Mode** - Toggle between dark and light themes with persistent settings
- **⚡ Quick Access** - Organized sections for Google apps and frequently visited websites
- **🔍 Smart Search** - Direct Google search with URL detection
- **⏰ Live Clock** - Real-time date and time display
- **🎯 Interactive Elements** - Smooth animations and hover effects

## 🚀 Live Demo

[View Live Demo](https://your-username.github.io/personal-homepage)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pawan9460r/homepage
   cd personal-homepage
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or serve using a local server for better performance

## 📁 Project Structure

```
personal-homepage/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── assets/             # Additional assets (if any)
    ├── images/         # Screenshots and icons
    └── css/           # Additional CSS files
```

## 🎯 Customization

### Personal Information
Update the following sections in `index.html`:

1. **Header Title**
   ```html
   <div class="title-name">
       <h1>Your Name</h1>
   </div>
   ```

2. **Social Media Links**
   ```html
   <a href="https://your-social-media-url" class="social-media-url" target="_blank">
       <i class="fab fa-platform-name"></i>
   </a>
   ```

### Google Apps
Modify the Google apps grid in the `google-apps-grid` section:

```html
<a href="https://your-app-url" class="app-card" target="_blank">
    <div class="app-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="app-name">App Name</div>
</a>
```

### Recent Websites
Update the websites grid in the `websites-grid` section:

```html
<a href="https://your-website-url" class="website-card" target="_blank">
    <div class="website-icon">
        <i class="fab fa-icon-name"></i>
    </div>
    <div class="website-name">Website Name</div>
</a>
```

## 🎨 Color Scheme

The homepage uses CSS custom properties for easy theming:

### Dark Theme (Default)
```css
--bg-color: #1a1a2e;
--card-bg: #16213e;
--text-color: #e4e4e4;
--accent-color: #4a9eff;
```

### Light Theme
```css
--bg-color: #f5f7fa;
--card-bg: #ffffff;
--text-color: #333333;
--accent-color: #4a9eff;
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid and Flexbox
- **JavaScript** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Roboto & Montserrat)

## 🌟 JavaScript Features

### Theme Toggle
- Persists user preference in localStorage
- Smooth transitions between themes

### Live Clock
- Real-time updates every second
- Formatted date and time display

### Smart Search
- Direct URL navigation
- Google search integration

### Scroll Animations
- Fade-in effects for cards
- Smooth appearance on scroll

## 🚀 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" and choose `main` branch
4. Your site will be available at `https://your-username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Or connect your GitHub repository for automatic deployments

### Vercel
1. Import your GitHub repository
2. Vercel will automatically detect and deploy

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons by [Font Awesome](https://fontawesome.com)
- Fonts by [Google Fonts](https://fonts.google.com)
- Inspiration from Google's homepage design

## 📞 Contact

Your Name - [@your-twitter](https://twitter.com/your-twitter) - email@example.com

Project Link: [https://github.com/your-username/personal-homepage](https://github.com/your-username/personal-homepage)

## 🗂️ Related Projects

- [Another Project](https://github.com/your-username/another-project)
- [Portfolio Website](https://github.com/your-username/portfolio)

---

<div align="center">

### ⭐ Don't forget to star this repository if you find it helpful!

</div>

## 📋 Changelog

### v1.0.0 (Current)
- Initial release
- Responsive design
- Dark/light theme toggle
- Google apps grid layout
- Recent websites section

### Planned Features
- [ ] Weather API integration
- [ ] Bookmark management
- [ ] Custom background images
- [ ] Keyboard shortcuts
- [ ] PWA support

---

**Note**: Remember to update all placeholder URLs and personal information with your actual details before deploying.
