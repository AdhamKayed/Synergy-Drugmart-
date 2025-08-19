# Synergy Drugmart - Professional Pharmacy Website

A modern, responsive website for Synergy Drugmart featuring comprehensive pharmacy services, prescription management, and patient care information.

## 🏥 Features

### Core Functionality
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Prescription Refill System** - Easy-to-use forms for prescription refills
- **Service Information** - Comprehensive details about pharmacy services
- **Contact & Location** - Store hours, contact information, and location details
- **Professional Branding** - Clean, trustworthy design suitable for healthcare

### Services Highlighted
- Prescription Services (new, refills, transfers)
- Immunizations (flu shots, COVID-19, travel vaccines)
- Health Screenings (blood pressure, diabetes, cholesterol)
- Medication Counseling & Reviews
- Free Delivery Services
- Over-the-Counter Medications & Wellness Products

### Technical Features
- **Modern CSS** - Uses CSS Grid, Flexbox, and modern styling techniques
- **Interactive JavaScript** - Form validation, smooth scrolling, mobile navigation
- **Accessibility** - Semantic HTML, keyboard navigation, screen reader friendly
- **Performance Optimized** - Fast loading with optimized assets
- **SEO Ready** - Proper meta tags and semantic structure

## 🚀 Quick Start

### Method 1: Python Server (Recommended)
```bash
# Navigate to the project directory
cd synergy-drugmart-website

# Start the development server
python3 -m http.server 8000

# Open your browser and visit:
# http://localhost:8000
```

### Method 2: PHP Server
```bash
# Navigate to the project directory
cd synergy-drugmart-website

# Start PHP development server
php -S localhost:8000

# Open your browser and visit:
# http://localhost:8000
```

### Method 3: Direct File Opening
Simply open `index.html` in your web browser by double-clicking the file.

## 📁 Project Structure

```
synergy-drugmart-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── package.json        # Project configuration
└── README.md          # This file
```

## 🎨 Design Features

### Color Scheme
- **Primary Blue**: #2563eb (Professional, trustworthy)
- **Secondary Blue**: #3b82f6 (Accent color)
- **Gray Tones**: #1e293b, #64748b, #f8fafc (Text and backgrounds)
- **Success Green**: #10b981 (Positive actions)

### Typography
- **Font Family**: Inter (Modern, readable sans-serif)
- **Font Weights**: 300, 400, 500, 600, 700
- **Responsive Sizing**: Scales appropriately across devices

### Layout
- **Mobile-First**: Responsive design starting from mobile
- **Grid System**: CSS Grid for complex layouts
- **Flexbox**: For component-level layouts
- **Smooth Animations**: CSS transitions and JavaScript animations

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Customization

### Updating Contact Information
Edit the contact section in `index.html`:
```html
<!-- Update address, phone, email, and hours -->
<div class="contact-details">
    <h3>Location</h3>
    <p>YOUR ADDRESS HERE</p>
</div>
```

### Modifying Services
Update the services grid in `index.html` to reflect your pharmacy's specific offerings.

### Changing Colors
Modify the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #3b82f6;
    /* Add your custom colors */
}
```

## 📋 Form Integration

The website includes two main forms:

### Prescription Refill Form
- Patient information collection
- Prescription details
- Pickup/delivery options
- Form validation included

### Contact Form
- General inquiry form
- Subject categorization
- Message submission

**Note**: Forms currently use JavaScript simulation. To make them functional, integrate with your backend API or form processing service.

## 🛡️ Security Considerations

- All forms include client-side validation
- No sensitive data is stored client-side
- HTTPS recommended for production deployment
- Consider implementing CAPTCHA for form submissions

## 📈 SEO Optimization

- Semantic HTML structure
- Meta tags for search engines
- Alt text for images
- Proper heading hierarchy (H1-H6)
- Schema markup ready for implementation

## 🚀 Deployment Options

### Static Hosting (Recommended)
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Pages**: Free hosting for public repositories
- **AWS S3**: Scalable static hosting

### Traditional Web Hosting
- Upload files to your web server's public directory
- Ensure server supports HTML, CSS, and JavaScript
- Configure domain and SSL certificate

## 🔄 Future Enhancements

Consider adding these features:
- Online prescription ordering system
- Patient portal integration
- Appointment scheduling
- Insurance verification
- Medication interaction checker
- Multi-language support
- Live chat functionality
- Blog/health tips section

## 📞 Support

For questions about this website template:
1. Check the code comments for implementation details
2. Review the responsive design in browser developer tools
3. Test forms and interactive elements thoroughly
4. Validate HTML/CSS for compliance

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for Synergy Drugmart**

*Professional pharmacy website template designed for modern healthcare practices.*