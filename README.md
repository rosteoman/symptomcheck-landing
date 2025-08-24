# Symptom Track - Landing Page

Professional landing page for the iOS app **Symptom Track**, designed to capture leads from users interested in Premium and Gold versions.

## 🚀 Features

### **Design and UX**
- ✅ **Perfect Responsive Design** (mobile, tablet, desktop)
- ✅ **Custom color palette** (#011436, #a00202, #e3e3e3, #61707f, #ecaf05)
- ✅ **Smooth animations** and professional transitions
- ✅ **Fluid navigation** with smooth scrolling
- ✅ **Interactive modals** for legal terms

### **Functionalities**
- ✅ **Functional contact form** with validation
- ✅ **Real-time notifications**
- ✅ **SEO optimized** with complete meta tags
- ✅ **Enhanced accessibility** (ARIA labels, keyboard navigation)
- ✅ **Performance optimized** (debounce, throttle)

### **Sections**
- 🏠 **Hero Section** with app mockup
- ⭐ **Key Features** (6 cards)
- 💎 **Versions** (Free, Premium, Gold)
- 📞 **Contact form** for leads
- 📱 **Download section** with App Store
- 📄 **Footer** with legal links

## 🎨 Color Palette

```css
--primary-blue: #011436    /* Primary blue */
--primary-red: #a00202     /* Primary red */
--light-gray: #e3e3e3      /* Light gray */
--medium-gray: #61707f     /* Medium gray */
--gold: #ecaf05           /* Gold */
--white: #FFFFFF          /* White */
--black: #000000          /* Black */
```

## 📁 Project Structure

```
symptomtrack-landing/
├── index.html              # Main page
├── css/
│   └── style.css          # Main styles
├── js/
│   └── main.js            # Functional JavaScript
├── images/                # Images (to add)
│   ├── favicon.png
│   └── og-image.jpg
└── README.md              # This file
```

## 🚀 Installation and Deployment

### **1. GitHub Pages (Recommended)**

```bash
# 1. Create repository on GitHub
git init
git add .
git commit -m "Initial commit: Symptom Track Landing Page"
git branch -M main
git remote add origin https://github.com/rosteoman/symptomtrack-landing.git
git push -u origin main

# 2. Activate GitHub Pages
# Go to Settings > Pages > Source: Deploy from a branch > main
# URL: https://rosteoman.github.io/symptomtrack-landing
```

### **2. Local Server**

```bash
# With Python 3
python -m http.server 8000

# With Node.js
npx serve .

# With PHP
php -S localhost:8000
```

### **3. Other Hosting**

- **Netlify**: Drag & drop the folder
- **Vercel**: Connect GitHub repository
- **Firebase Hosting**: `firebase deploy`
- **AWS S3**: Upload static files

## ⚙️ Configuration

### **1. Customize Content**

Edit `index.html` to change:
- Titles and descriptions
- Version prices
- Contact information
- Legal terms

### **2. Configure Contact Form**

1. **EmailJS Setup**:
   - Create account at [emailjs.com](https://emailjs.com)
   - Get Public Key, Service ID, and Template ID
   - Update `js/main.js` with your credentials

2. **Google Analytics**:
   - Create property in Google Analytics
   - Get Measurement ID (G-XXXXXXXXXX)
   - Update `index.html` with your ID

### **3. SEO Optimization**

- Update meta tags in `index.html`
- Add your domain to `CNAME` file
- Configure social media images
- Add structured data if needed

## 📊 Analytics and Tracking

### **Google Analytics**
- Page views and user behavior
- Conversion tracking
- Traffic sources analysis
- Mobile vs desktop usage

### **EmailJS Analytics**
- Form submission rates
- Lead quality metrics
- Response time tracking
- Conversion funnel analysis

## 🎯 Marketing Features

### **Lead Capture**
- Contact form with validation
- Version preference selection
- Custom message field
- Privacy policy acceptance

### **Conversion Optimization**
- Clear value propositions
- Social proof elements
- Multiple CTAs
- Mobile-first design

### **SEO Elements**
- Semantic HTML structure
- Meta descriptions
- Open Graph tags
- Twitter Cards
- Schema markup ready

## 🔧 Technical Details

### **Performance**
- Optimized CSS and JavaScript
- Minified assets (recommended)
- Image optimization
- CDN ready

### **Security**
- Form validation
- CSRF protection (EmailJS)
- HTTPS required
- Privacy compliance

### **Accessibility**
- WCAG 2.1 AA compliant
- Keyboard navigation
- Screen reader friendly
- High contrast support

## 📈 Expected Metrics

### **Target KPIs**
- **Page Load Time**: < 3 seconds
- **Form Conversion**: > 5%
- **Mobile Traffic**: > 60%
- **Bounce Rate**: < 40%

### **Lead Quality**
- **Valid Emails**: > 90%
- **Complete Forms**: > 80%
- **Premium Interest**: > 30%
- **Gold Interest**: > 15%

## 🚀 Next Steps

### **Immediate Actions**
1. ✅ Deploy to GitHub Pages
2. ✅ Configure EmailJS
3. ✅ Set up Google Analytics
4. 🔄 Add app screenshots
5. 🔄 Create favicon and OG image

### **Future Enhancements**
- A/B testing setup
- Advanced analytics
- CRM integration
- Multi-language support
- Blog section

## 📞 Support

For technical support or questions:
- **Email**: contact@babenberg-studies.com
- **Website**: SymptomTrack.com
- **Documentation**: This README

## 📄 License

© 2025 Roman Dura Sanz Von Babenberg - Babenberg Studies. All rights reserved.

---

**Built with ❤️ for Symptom Track users worldwide**
