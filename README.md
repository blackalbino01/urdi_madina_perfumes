# Luxury Perfumes Website

A modern, responsive business website for a luxury perfume company with WhatsApp booking integration.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **WhatsApp Integration**: Direct booking and consultation via WhatsApp
- **Modern UI/UX**: Clean, elegant design with smooth animations
- **Product Showcase**: Beautiful product grid with hover effects
- **Services Section**: Highlight of key services offered
- **Contact Form**: WhatsApp-integrated contact form
- **Mobile Navigation**: Hamburger menu for mobile devices

## Sections

1. **Hero Section**: Eye-catching banner with call-to-action buttons
2. **About Us**: Company story and key features
3. **Products**: Perfume collection with booking buttons
4. **Services**: Personal consultation, custom blending, gift wrapping
5. **Contact**: Contact information and form with WhatsApp integration

## Setup Instructions

1. **Replace placeholder images**:
   - Add your perfume product images to the `images/` folder
   - Name them: `perfume1.jpg`, `perfume2.jpg`, `perfume3.jpg`, `perfume4.jpg`
   - Add a hero background image: `hero-bg.jpg`

2. **Update WhatsApp number**:
   - Open `js/script.js`
   - Find the line: `const phoneNumber = '1234567890';`
   - Replace with your actual WhatsApp business number (format: country code + number, no + or spaces)
   - Example: For +1 (555) 123-4567, use: `15551234567`

3. **Customize content**:
   - Update company name, address, and contact details in `index.html`
   - Modify product names, descriptions, and prices
   - Adjust business hours and location information

4. **Color scheme** (optional):
   - Edit CSS custom properties in `css/styles.css`
   - Main colors are defined in the `:root` section

## File Structure

```text
perfume/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Product and background images
├── .github/
│   └── copilot-instructions.md
└── README.md           # This file
```

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript
- Google Fonts (Playfair Display, Poppins)
- WhatsApp Business API

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## WhatsApp Integration

The website includes multiple WhatsApp integration points:

- **Book Consultation**: General consultation booking
- **Product Booking**: Specific product interest
- **Contact Form**: Form submissions sent via WhatsApp
- **Service Inquiries**: Service-specific bookings

## Customization Notes

- **Images**: All images have error handling and placeholder fallbacks
- **Animations**: Smooth scroll, fade-in effects, hover animations
- **Mobile-First**: Responsive design optimized for mobile devices
- **SEO Ready**: Semantic HTML structure for better search engine optimization

## Launch Instructions

1. Open `index.html` in a web browser to view locally
2. For production, upload all files to your web hosting service
3. Ensure all image files are properly uploaded
4. Test WhatsApp functionality with your phone number

## Support

The website is built with modern web standards and includes:

- Cross-browser compatibility
- Mobile responsiveness
- Accessibility features
- Fast loading times
- SEO optimization

Remember to replace placeholder content and images with your actual business information before going live!
