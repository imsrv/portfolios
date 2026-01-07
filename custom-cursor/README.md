# CA Portfolio Website

A modern, responsive, mobile-first portfolio website for Chartered Accountants.

## Features

- ✅ Fully responsive design (mobile-first approach)
- ✅ Modern and professional UI/UX
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly hamburger menu
- ✅ Contact options: WhatsApp, Phone, Email
- ✅ Contact form with email integration
- ✅ Service showcase section
- ✅ About section with credentials
- ✅ Animated elements on scroll

## Files Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styling (mobile-first responsive)
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Customization Guide

### Update Contact Information

1. **Phone Number**: 
   - Update in `index.html`:
     - Line with `href="tel:+1234567890"` - replace with your phone number
     - Line with `href="https://wa.me/1234567890"` - replace with your WhatsApp number (format: country code + number, no + or spaces)

2. **Email Address**:
   - Update in `index.html`:
     - Replace `info@caservices.com` with your email address
   - Update in `script.js`:
     - Line with `mailto:info@caservices.com` - replace with your email

3. **Location/Address**:
   - Update in `index.html`:
     - Replace the address text in the contact section

### Update Personal Information

1. **Name/Title**: Update the hero section title and subtitle
2. **About Section**: Customize the about text with your experience and credentials
3. **Services**: Modify or add services in the services section
4. **Logo/Branding**: Update the logo text in the navigation bar

### Color Scheme

The website uses CSS variables for easy color customization. In `styles.css`, update the `:root` variables:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1e40af;       /* Darker shade */
    --secondary-color: #10b981;    /* Accent color */
    /* ... other colors */
}
```

## How to Use

1. Open `index.html` in a web browser
2. Customize the content as needed
3. Update contact information
4. Deploy to your web hosting service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- The contact form uses `mailto:` links, which will open the user's default email client
- WhatsApp links use the `wa.me` format for universal compatibility
- Phone links use `tel:` protocol for mobile click-to-call functionality
- Font Awesome icons are loaded from CDN - ensure internet connection for icons to display

## License

Free to use and modify for personal or commercial purposes.
