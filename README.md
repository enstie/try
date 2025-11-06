# Crest Immigration Law Firm Website

A professional, responsive website for Crest Immigration Law Firm, founded by Attorney Samuel Bookman.

## Website Features

- **Modern Blue Design System**: Professional blue color palette (#1e3a8a, #2563eb, #dbeafe) with gray accents
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices
- **Enhanced SEO**: Comprehensive meta tags including geographic data for Amsterdam location
- **Professional Styling**: Pacifico font for logo, system fonts for body text
- **Remix Icons**: Modern icon library throughout the website
- **Four Main Pages**:
  - **Home**: Hero section with statistics cards, 6-service grid, attorney profile, and client testimonials
  - **About**: Firm history, mission statement, core values, and detailed attorney information
  - **Services**: Comprehensive immigration law services with process overview
  - **Contact**: Contact form with service selector, office hours, and Google Maps integration

## Technology Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Pacifico)
- Remix Icons (via CDN)

## Project Structure

```
lawfirm/
├── index.html          # Home page with hero, services, testimonials
├── about.html          # About page with firm history and values
├── services.html       # Services page with detailed offerings
├── contact.html        # Contact page with form and map
├── assets/
│   ├── css/
│   │   └── style.css   # Complete stylesheet with blue design system
│   ├── js/
│   │   └── script.js   # JavaScript for navigation and form handling
│   └── images/         # Image assets directory
└── README.md           # This file
```

## Design System

### Colors
- **Blue-900** (#1e3a8a): Primary brand color for buttons, headers
- **Blue-600** (#2563eb): Secondary blue for icons and highlights
- **Blue-100** (#dbeafe): Light blue for backgrounds and accents
- **White** (#ffffff): Primary background
- **Gray-50** (#f9fafb): Section backgrounds
- **Gray-900** (#111827): Dark text and footer

### Typography
- **Logo**: Pacifico (cursive)
- **Body**: System default sans-serif stack
- **Font Sizes**: Responsive scaling from mobile to desktop

### Components
- Button variants: Primary, Secondary, Outline
- Service cards with hover animations
- Statistics cards with glassmorphism effect
- Testimonial cards with star ratings
- Contact cards with icons
- Process steps with numbered badges

## Contact Information

- **Attorney**: Samuel Bookman
- **Phone**: +31 97005033157
- **Email**: lawsamchambers@email.com
- **Firm**: Crest Immigration Law Firm
- **Location**: Amsterdam, Netherlands

## Deployment on GitHub Pages

This website is designed to be deployed on GitHub Pages. Follow these steps:

1. Push the repository to GitHub
2. Go to the repository Settings
3. Navigate to Pages section
4. Under "Source", select the branch you want to deploy (e.g., `main` or `master`)
5. Click Save
6. Your website will be available at: `https://[username].github.io/[repository-name]/`

## Local Development

To run the website locally:

1. Clone the repository
2. Open a terminal in the project directory
3. Start a local web server:
   ```bash
   # Using Python 3
   python3 -m http.server 8080
   
   # Using Python 2
   python -m SimpleHTTPServer 8080
   
   # Using Node.js (requires http-server package)
   npx http-server -p 8080
   ```
4. Open your browser and navigate to `http://localhost:8080`

## Features

### Enhanced SEO
- Comprehensive meta tags for search engines
- Geographic SEO tags for Amsterdam location
- Descriptive titles and descriptions for each page
- Keywords optimized for immigration law services

### Responsive Navigation
- Desktop: Horizontal navigation bar with logo and icons
- Mobile: Hamburger menu with smooth transitions
- Sticky header for easy navigation

### Contact Form
- Client-side validation
- Service selector dropdown
- Required fields: Name, Email, Message
- Optional: Phone number and service type
- Success/error messages via JavaScript alerts

### Using FormSubmit (no backend)

If you'd like to receive form submissions by email without running a server, FormSubmit is a simple option:

  - `_subject` — set the email subject line
  - `_next` — URL to redirect users to after successful submission (use a full URL)
  - `_captcha` — enable/disable FormSubmit captcha handling

Example (already added to `contact.html`):

<form action="https://formsubmit.co/farfrombroke4561@gmail.com" method="POST">
<form action="https://formsubmit.co/you@yourdomain.com" method="POST">
  <input type="hidden" name="_subject" value="New contact form message - Crest Law">
  <input type="hidden" name="_next" value="https://your-site.com/thank-you.html">
  <input type="hidden" name="_captcha" value="false">
  <!-- form fields... -->
</form>
```

Notes:
- Replace `you@yourdomain.com` with your real email address before publishing.
- Test locally using a simple server (see Local Development above) instead of opening the file via `file://` to ensure POST requests behave correctly.
- Check your spam/junk folder for the verification email if you don't see it.

### Google Maps Integration
- Embedded map showing Amsterdam location
- Can be customized to show actual office location

### Interactive Elements
- Hover effects on cards and buttons
- Smooth color transitions
- Statistics cards with glassmorphism
- Testimonial ratings with stars
- Social media links in footer

## Browser Compatibility

The website is compatible with modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2023 Crest Immigration Law Firm. All rights reserved.
