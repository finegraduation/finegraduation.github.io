# Fine Graduation - Photography Website

A responsive one-page static website for Fine Graduation photography services, featuring a full-screen video background and minimalist design.

## 🎯 Overview

Fine Graduation is a photography service specializing in graduation ceremonies across multiple Indonesian cities. This website showcases their services with an elegant, minimalist design that emphasizes visual storytelling.

### 🌟 Features

- **Full-screen video background** with elegant overlay
- **Responsive design** optimized for mobile, tablet, and desktop
- **Minimalist photography theme** with elegant typography
- **WhatsApp integration** for direct customer contact
- **Smooth animations** and transitions
- **Accessibility-friendly** design
- **GitHub Pages deployment** ready

### 🏙️ Service Areas

- Kediri
- Malang  
- Surabaya
- Jogja
- Bandung
- Semarang

## 🚀 Live Demo

Visit the live website: [Fine Graduation Website](https://yourusername.github.io/finegraduation.github.io_v2)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling and animations
- **Tailwind CSS** - Utility-first CSS framework
- **Google Fonts** - Playfair Display & Montserrat typography
- **GitHub Pages** - Static site hosting
- **GitHub Actions** - Automated deployment

## 📱 Responsive Design

The website is fully responsive across all device sizes:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px
- **Large Desktop**: > 1440px

## 🎨 Design Philosophy

### Typography
- **Headings**: Playfair Display (elegant serif)
- **Body Text**: Montserrat (clean sans-serif)
- **Hierarchy**: Clear visual hierarchy with appropriate font weights

### Color Scheme
- **Primary**: White text on dark overlay
- **Accent**: Green (#25D366) for WhatsApp integration
- **Background**: Video with gradient overlay

### Layout
- **Centered content** with proper spacing
- **Fade-in animations** for progressive content reveal
- **Minimalist approach** focusing on content and imagery

## 📁 Project Structure

```
finegraduation.github.io_v2/
├── index.html              # Main HTML file
├── style.css               # Custom CSS styles
├── README.md               # Project documentation
├── TODO.md                 # Development progress tracker
├── assets/                 # Media assets
│   ├── README.md           # Asset instructions
│   ├── graduation-bg.mp4   # Video background (to be added)
│   └── graduation-fallback.jpg # Fallback image (to be added)
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Pages deployment
```

## 🔧 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/finegraduation.github.io_v2.git
cd finegraduation.github.io_v2
```

### 2. Add Media Assets
1. Download a suitable graduation ceremony video
2. Rename it to `graduation-bg.mp4`
3. Place it in the `assets/` directory
4. Optionally add `graduation-fallback.jpg` for fallback support

**Recommended video specifications:**
- Resolution: 1920x1080 (Full HD) or higher
- Format: MP4 (H.264 codec)
- Duration: 10-30 seconds (will loop)
- File size: Under 10MB

### 3. Local Development
Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

### 4. GitHub Pages Deployment

#### Automatic Deployment (Recommended)
1. Push your code to the `main` or `master` branch
2. GitHub Actions will automatically deploy to GitHub Pages
3. Enable GitHub Pages in repository settings if not already enabled

#### Manual Deployment
1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `main` branch and `/ (root)` folder
4. Click Save

## 📞 Contact Integration

The website includes WhatsApp integration for direct customer contact. Update the phone number in `index.html`:

```html
<a href="https://wa.me/6281234567890?text=..." 
```

Replace `6281234567890` with the actual WhatsApp business number.

## 🎯 Customization

### Content Updates
Edit the text content in `index.html`:
- Company name and tagline
- Service areas
- Contact information
- Call-to-action text

### Styling Changes
Modify `style.css` for:
- Color scheme adjustments
- Typography changes
- Animation timing
- Layout modifications

### Responsive Breakpoints
Current breakpoints in `style.css`:
- Mobile: `max-width: 767px`
- Tablet: `768px - 1023px`
- Desktop: `min-width: 1024px`
- Large Desktop: `min-width: 1440px`

## 🔍 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta descriptions
- Open Graph tags (can be added)
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## ♿ Accessibility Features

- **Keyboard navigation** support
- **Screen reader** friendly markup
- **High contrast** text and backgrounds
- **Reduced motion** support for users with vestibular disorders
- **Focus indicators** for interactive elements

## 🚀 Performance Optimization

- **Optimized video** loading with fallbacks
- **Efficient CSS** with minimal external dependencies
- **Progressive enhancement** approach
- **Mobile-first** responsive design
- **Compressed assets** for faster loading

## 📈 Analytics Integration

To add Google Analytics or other tracking:

1. Add tracking code to `<head>` section in `index.html`
2. Ensure compliance with privacy regulations
3. Consider cookie consent if required

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Tailwind CSS** for the utility-first CSS framework
- **Google Fonts** for beautiful typography
- **GitHub Pages** for free static site hosting
- **Pexels/Unsplash** for stock video recommendations

## 📞 Support

For support or questions about this website:
- Create an issue in this repository
- Contact Fine Graduation via WhatsApp through the website

---

**#YourStoryMustBeRemembered #MemorableStoryWithFine**
