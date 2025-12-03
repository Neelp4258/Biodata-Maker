# 🎨 Professional Biodata Maker

A modern, professional biodata/resume maker with 10 stunning templates and PDF download functionality.

![Biodata Maker](https://img.shields.io/badge/Templates-10-blue) ![A4 Format](https://img.shields.io/badge/Format-A4-green) ![Mobile](https://img.shields.io/badge/Mobile-Optimized-brightgreen) ![License](https://img.shields.io/badge/License-MIT-yellow)

## ✨ Features

### 🎯 Core Features
- **10 Premium Templates** - Choose from minimalist to luxurious designs
- **Professional Background Section** - Showcase your work experience and skills
- **Login/Signup System** - Secure authentication with email and contact
- **Live Preview** - See your biodata in real-time as you type
- **PDF Download** - Export perfect A4 PDFs ready for printing
- **Auto-Save** - Never lose your progress with localStorage
- **Mobile Responsive** - Perfect experience on all devices

### 📋 Template Categories

1. **Minimalist Elegance** - Clean and professional
2. **Geometric Luxury** - Dark theme with golden accents
3. **Organic Nature** - Nature-inspired with earthy colors
4. **Art Deco Luxe** - Vintage luxury design
5. **Magazine Editorial** - Sophisticated editorial layout
6. **Brutalist Concrete** - Industrial design aesthetic
7. **Watercolor Dreams** - Artistic watercolor-inspired
8. **Modern Corporate Glass** - Glassmorphism design ✨ NEW
9. **Classic Renaissance** - Vintage ornamental style ✨ NEW
10. **Tech Futuristic** - Cyberpunk-inspired design ✨ NEW

## 🚀 Quick Start

### Online Demo
Visit the live demo: [Your Netlify URL here]

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/Neelp4258/Biodata-Maker.git
cd Biodata-Maker
```

2. **Open in browser**
```bash
# Using Python 3
python3 -m http.server 8000

# Or using PHP
php -S localhost:8000

# Or using Node.js http-server
npx http-server -p 8000
```

3. **Visit** `http://localhost:8000` in your browser

## 📖 How to Use

### Step 1: Sign Up / Login
- Open `index.html`
- Create an account with your email, name, contact number, and password
- Or login if you already have an account

### Step 2: Choose Template
- Browse through 10 beautiful templates
- Click on any template card to preview it
- Click "Select This Template" to proceed

### Step 3: Fill Details
- Enter your personal information
- Add educational background
- **Include professional background** (occupation, experience, skills)
- Add family details
- Save your progress anytime

### Step 4: Download PDF
- Review your biodata in the live preview
- Click "Download PDF" to get your A4-formatted biodata
- Print or share digitally!

## 🛠️ Technical Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Framework**: Bootstrap 5
- **Icons**: Font Awesome 6
- **Fonts**: Google Fonts
- **PDF Generation**: html2canvas + jsPDF
- **Storage**: LocalStorage API
- **Responsive**: Mobile-first design

## 📐 Technical Specifications

### Strict A4 Dimensions
All templates follow exact A4 specifications:
```css
@page {
    size: A4;
    margin: 0;
}

.page {
    width: 210mm;
    min-height: 297mm;
    page-break-after: always;
}
```

### Print-Safe CSS
- `-webkit-print-color-adjust: exact;`
- `print-color-adjust: exact;`
- Proper page breaks
- No content overflow
- Color-safe for printing

## 🎨 Customization

### Adding Your Own Template

1. Create a new HTML file: `template-XX.html`
2. Follow the A4 dimension structure:
```html
<div class="page">
    <div class="header"><!-- Fixed height --></div>
    <div class="content" style="flex: 1;"><!-- Flexible content --></div>
    <div class="footer" style="margin-top: auto;"><!-- Footer --></div>
</div>
```
3. Add to `templates.html` array:
```javascript
{
    id: XX,
    name: 'Your Template Name',
    file: 'template-XX.html',
    description: 'Description here',
    features: ['Feature 1', 'Feature 2', 'Feature 3'],
    previewClass: 'preview-custom',
    badge: 'New'
}
```

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 🌐 Deployment

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy)

1. **Via Netlify CLI**
```bash
npm install -g netlify-cli
netlify login
netlify deploy --prod
```

2. **Via Git Integration**
- Push your code to GitHub
- Connect repository in Netlify dashboard
- Deploy automatically on every push

### Deploy to Vercel
```bash
npm i -g vercel
vercel --prod
```

### Deploy to GitHub Pages
```bash
git checkout -b gh-pages
git push origin gh-pages
```

## 🔒 Security Features

- Client-side authentication (no backend required)
- LocalStorage encryption (can be enhanced)
- XSS protection headers
- CSRF protection
- Content Security Policy ready

## 🐛 Known Issues & Limitations

- PDF generation depends on browser capabilities
- LocalStorage has 5-10MB limit
- Emoji rendering may vary by OS/browser
- Some advanced CSS features may not print perfectly

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Neelp4258**
- GitHub: [@Neelp4258](https://github.com/Neelp4258)

## 🙏 Acknowledgments

- Bootstrap team for the amazing framework
- Font Awesome for beautiful icons
- Google Fonts for typography
- html2canvas & jsPDF for PDF generation

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Star ⭐ the repository if you find it useful!

---

Made with ❤️ by Neelp4258

**Happy Creating! 🎉**
