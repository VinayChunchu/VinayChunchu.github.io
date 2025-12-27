# Vinay Chunchu - Personal Portfolio

A modern, clean personal portfolio website showcasing professional experience as a Senior Software Engineer at AWS.

## 🌟 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Performance Focused**: Fast loading with optimized code
- **Accessibility**: WCAG compliant with proper semantic HTML
- **Single Page Application**: Smooth scrolling navigation
- **Professional Sections**: Hero, About, Experience, Skills, Contact

## 🚀 Live Demo

Visit the live website: [https://vinaychunchu.github.io/portfolio](https://vinaychunchu.github.io/portfolio)

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Fonts**: Google Fonts (Inter)
- **Icons**: Custom SVG icons
- **Build Tools**: Native HTML/CSS/JS (no build process required)

## 📁 Project Structure

```
portfolio/
├── assets/
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   ├── images/                # Image assets
│   └── js/
│       └── script.js          # Main JavaScript file
├── index.html                 # Main HTML file
├── README.md                  # Project documentation
├── package.json               # Project metadata
└── .gitignore                # Git ignore rules
```

## 🚀 Quick Start

### For GitHub Pages Deployment

1. **Fork this repository**
   - Click the "Fork" button on GitHub
   - Clone your forked repository locally

2. **Enable GitHub Pages**
   ```bash
   # Go to your repository settings
   # Navigate to Pages section
   # Select "GitHub Actions" as source
   ```

3. **Customize your content**
   - Update personal information in `index.html`
   - Replace `assets/images/vinay.jpeg` with your photo
   - Modify experience, education, and skills sections
   - Update social media links

4. **Push changes**
   ```bash
   git add .
   git commit -m "Customize portfolio content"
   git push origin main
   ```

5. **Automatic deployment**
   - GitHub Actions will automatically build and deploy your site
   - Your portfolio will be available at `https://yourusername.github.io/repository-name`

### For Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/VinayChunchu/portfolio.git
   cd portfolio
   ```

2. **Start development server**
   ```bash
   # Option 1: Simple Python server
   python -m http.server 8000
   
   # Option 2: With live reload (requires npm install)
   npm run dev
   
   # Option 3: Just open index.html in browser
   open index.html
   ```

## 🎨 Customization

### Personal Information
Edit the following sections in `index.html`:
- Hero section: Name, title, description
- About section: Professional summary and stats
- Experience section: Work history and achievements
- Skills section: Technologies and tools
- Contact section: Email and social links

### Styling
- Main colors and themes: `assets/css/style.css` (CSS custom properties)
- Typography: Google Fonts (Inter) link in HTML head
- Layout: CSS Grid and Flexbox for responsive design

### Content Updates
- **Profile Image**: Replace `assets/images/vinay.jpeg` with your photo
- **Experience**: Update timeline with your work history
- **Skills**: Modify skill categories and technologies
- **Social Links**: Update URLs to your profiles

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Development

### Adding New Sections
1. Add HTML structure following existing patterns
2. Update navigation in `assets/js/script.js`
3. Add corresponding CSS styles
4. Test responsiveness across devices

### Performance Tips
- Images are optimized and properly sized
- CSS and JS are minified for production
- Uses modern web standards for best performance
- Implements smooth scrolling and animations

## 📈 SEO & Analytics

### Meta Tags
The portfolio includes comprehensive meta tags:
- Title and description optimized for search
- Open Graph tags for social sharing
- Proper semantic HTML structure

### Analytics
Add your analytics code before closing `</body>` tag:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
```

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select "GitHub Actions" as source
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository
2. Build command: (leave empty)
3. Publish directory: `/` (root)
4. Deploy automatically on push

### Vercel
```bash
npm install -g vercel
vercel --prod
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

**Vinay Chunchu**
- Email: vinaychunchu@hotmail.com
- LinkedIn: [linkedin.com/in/vinay-chunchu-324737167](https://www.linkedin.com/in/vinay-chunchu-324737167)
- GitHub: [github.com/VinayChunchu](https://github.com/VinayChunchu)
- Twitter: [twitter.com/VinayCChunchu](https://twitter.com/VinayCChunchu)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Inter font family from Google Fonts
- Custom SVG icons for clean aesthetics
- Modern CSS Grid and Flexbox for responsive layout

---

⭐ Star this repository if you found it helpful!