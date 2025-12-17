# Hearts and Plates Restaurant Website

A modern, responsive website for **Hearts and Plates**, a vibrant multi-cuisine restaurant located on Mission Street, Puducherry. Built with Bootstrap, Swiper, and custom CSS.

## 🍽️ About Hearts and Plates

**Hearts and Plates** is a vibrant multi-cuisine restaurant located on Mission Street, Puducherry. We bring together flavors from around the world, serving everything from Indian classics to global favorites, all prepared fresh and served with heartfelt hospitality.

Whether you're stopping by for a quick bite, a family meal, or a special celebration, our cozy ambiance and lovingly crafted dishes promise a memorable dining experience. At Hearts and Plates, every plate tells a story and every guest is served with love.

### Restaurant Information

- **Name**: Hearts and Plates
- **Location**: 51 B, First Floor Mission Street, Pondicherry
- **Phone**: +91 73052 07180
- **Email**: support@hearts-and-plates.com
- **Opening Hours**:
  - Monday - Thursday: 12:00 PM – 11:00 PM
  - Friday - Sunday: 11:30 AM – 11:30 PM
  - *Breaktime: 3:30 PM - 5:00 PM*
  - Closed on Tuesdays

### Cuisines & Services

- **Multi-Cuisine Specialities**: Chettinad, South Indian, Tandoori, Biryani, Indo-Chinese, Seafood, Desserts
- **Dine-In Experience**: Warm ambiance with quick service
- **Party Halls**: Elegant venues for 25-50 guests with music, decor, and curated menus
- **Catering Services**: Outdoor and onsite catering across Pondicherry for weddings and corporate events

### Social Media

- **Instagram**: [@hearts_and_plates](https://www.instagram.com/hearts_and_plates)
- **Google**: [Google Business Profile](https://g.page/r/CZ8rOB4VQ65-EAE/review)
- **WhatsApp**: [Contact via WhatsApp](https://wa.me/917305207180)
- **Swiggy**: [Order Online](https://www.swiggy.com/city/pondicherry/hearts-and-plates-restaurant-white-town-rest1271805)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Pages](#pages)
- [Customizations](#customizations)
- [Getting Started](#getting-started)
- [GitHub Pages Deployment](#github-pages-deployment)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)

## 🎯 Overview

This website is built on the Basilico restaurant template, customized specifically for Hearts and Plates. It features a modern, responsive design with smooth animations, video integration, and interactive booking forms.

## ✨ Features

### Implemented Features

- ✅ **Responsive Design**: Fully responsive across all devices (desktop, tablet, mobile)
- ✅ **Modern UI Components**:
  - Image sliders (Swiper.js)
  - Animated sections (AOS - Animate On Scroll)
  - Video integration with autoplay
  - Interactive booking forms
  - WhatsApp integration for bookings and contact
- ✅ **Custom Sections**:
  - Hero slider with restaurant tagline
  - About Restaurant section
  - Opening Hours with zoom-in image effect
  - Special Menu (Starters, Tandoori, Biryani)
  - Restaurant video section with autoplay on scroll
  - Why Choose Us section with tab-driven videos
  - Customer testimonials slider
  - Order Online section with Swiggy integration
- ✅ **Booking System**:
  - Date picker with Tuesday restrictions
  - Indian phone number validation
  - Meal type selection (Lunch/Dinner)
  - People counter (1-25 guests)
  - WhatsApp message integration
- ✅ **Contact Form**:
  - Email validation
  - Indian phone number validation (10 digits, starts with 6-9)
  - WhatsApp message integration
- ✅ **Navigation**: Simplified to Home, Menu, and Contact Us
- ✅ **Footer**: Updated with restaurant information and social links

### Technical Features

- Bootstrap 5 framework
- Swiper.js for sliders
- AOS (Animate On Scroll) library
- Custom CSS animations
- Video autoplay functionality
- Form validation
- WhatsApp API integration

## 📄 Pages

### Active Pages

1. **`index.html`** - Homepage
   - Hero slider
   - About Restaurant section
   - Opening Hours
   - Special Menu preview
   - Restaurant video
   - Why Choose Us (with videos)
   - Customer testimonials
   - Order Online section

2. **`menu_list.html`** - Full Menu Page
   - Complete menu with categories
   - Booking form with validation
   - Opening hours
   - Contact information

3. **`contact_01.html`** - Contact Page
   - Contact form with validation
   - Google Maps integration
   - Restaurant information
   - Opening hours

### Removed Pages

The following pages were removed to streamline the website:
- `home_02.html`, `home_03.html`, `home_04.html` (alternative homepages)
- `contact_02.html` (alternative contact page)
- `menu_zigzag.html` (alternative menu layout)
- All blog pages
- All portfolio pages
- `gallery.html`, `coming_soon.html`, `gift_vouchers.html`, etc.

## 🎨 Customizations

### Content Updates

- ✅ Restaurant name changed from "Basilico" to "Hearts and Plates"
- ✅ All contact information updated
- ✅ Opening hours customized
- ✅ Menu items updated with actual restaurant menu
- ✅ Social media links integrated
- ✅ Footer copyright updated to "© 2026 Hearts & Plates. All rights reserved."
- ✅ Navigation simplified to essential pages only

### Visual Customizations

- ✅ Logo resized and updated across all pages
- ✅ Opening hours image with zoom-in effect (155% on hover)
- ✅ Video integration in "Why Choose Us" section
- ✅ Tab-driven video playback (Luxury Space → choose-1.mp4, Private Event/Catering → choose-2.mp4)
- ✅ Restaurant video with autoplay on scroll (50% visibility)
- ✅ Order Online section with horizontal split layout
- ✅ Removed sidebar from all pages
- ✅ Removed search icon from menu and contact pages
- ✅ Removed "latest new" email subscription from footer

### Functional Customizations

- ✅ Booking form with date restrictions (no Tuesdays, only current/future dates)
- ✅ Indian phone number validation (10 digits, starts with 6-9)
- ✅ Email validation
- ✅ WhatsApp integration for bookings and contact
- ✅ Swiggy order link opens in new tab
- ✅ All "BOOK A TABLE" buttons link to booking form

## 🚀 Getting Started

### Prerequisites

- A web server (for local development) or GitHub Pages (for hosting)
- A code editor (VS Code, Sublime Text, etc.)
- Git (for version control)

### Local Development

1. **Clone or download this repository**
   ```bash
   git clone <your-repo-url>
   cd basilicohtml
   ```

2. **Open in a web server**
   - Option 1: Use VS Code Live Server extension
   - Option 2: Use Python's built-in server:
     ```bash
     python -m http.server 8000
     ```
   - Option 3: Use Node.js http-server:
     ```bash
     npx http-server
     ```

3. **Open in browser**
   - Navigate to `http://localhost:8000` (or the port your server uses)
   - Open `index.html` to see the homepage

### SCSS Compilation (Optional)

If you need to modify SCSS files:

1. Install Sass:
   ```bash
   npm install -g sass
   ```

2. Compile SCSS to CSS:
   ```bash
   sass app/scss/app.scss app/dist/app.css --watch
   ```

**Note**: CSS changes have been made directly to `app/dist/app.css` for this project.

## 🌐 GitHub Pages Deployment

### Step 1: Create GitHub Repository

1. Create a new repository on GitHub
2. Name it (e.g., `hearts-and-plates-website`)

### Step 2: Push Your Code

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Hearts and Plates restaurant website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
5. Click **Save**
6. Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Step 4: Update Base Path (if needed)

All paths in this template are relative, so it should work automatically on GitHub Pages.

## 📁 Project Structure

```
basilicohtml/
├── assets/                 # Static assets
│   ├── font/              # Custom fonts (Audrey, DM Sans)
│   ├── fontawesome-free-6.4.2-web/  # Font Awesome library
│   ├── images/            # Images (logos, icons, sections, sliders)
│   │   ├── logo/          # Restaurant logos
│   │   ├── section/       # Section images
│   │   └── slider/        # Slider images
│   └── videos/           # Video files
│       ├── choose-1.mp4   # Luxury Space video
│       ├── choose-2.mp4   # Private Event/Catering video
│       └── restaurant-video.mp4  # Main restaurant video
├── app/                   # Application files
│   ├── bootstrap/         # Bootstrap CSS framework
│   ├── dist/              # Compiled CSS (app.css)
│   ├── js/                # JavaScript files
│   │   ├── swiper.js      # Swiper slider configuration
│   │   └── app.js         # Main application JavaScript
│   ├── scss/              # Source SCSS files
│   └── swiper/            # Swiper slider library
├── contact/               # Contact form PHP files (not used on GitHub Pages)
├── index.html             # Homepage
├── menu_list.html         # Menu page with booking form
├── contact_01.html        # Contact page
└── README.md              # This file
```

## 📦 Dependencies

### Local Dependencies (Included)

- Bootstrap 5.x
- Swiper.js (for sliders)
- jQuery
- Font Awesome 6.4.2
- Custom JavaScript libraries (parallax, countdown, etc.)

### CDN Dependencies

- AOS (Animate On Scroll) - `https://unpkg.com/aos@2.3.1/dist/aos.css`
- Highcharts - `https://code.highcharts.com/highcharts.js` (used in template, may not be active)

## 🔧 Key Files Modified

- `index.html` - Main homepage with all customizations
- `menu_list.html` - Menu page with booking form and validation
- `contact_01.html` - Contact page with WhatsApp integration
- `app/dist/app.css` - Custom CSS styles (directly modified)
- `app/js/swiper.js` - Swiper configuration

## 📝 Notes

- All CSS is pre-compiled in `app/dist/app.css`
- PHP contact forms are not functional on GitHub Pages (replaced with WhatsApp integration)
- Video files should be optimized for web (compressed)
- Images should be optimized for faster loading
- Update meta tags in HTML files for better SEO
- All form submissions go through WhatsApp API

## 🌍 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Support & Contact

For website issues or updates, contact:
- **Email**: support@hearts-and-plates.com
- **Phone**: +91 73052 07180
- **WhatsApp**: [Click to chat](https://wa.me/917305207180)

## 📄 License

This template was purchased from Themesflat and customized for Hearts and Plates restaurant. Please refer to your purchase license for usage terms.

---

**Built with ❤️ for Hearts and Plates Restaurant**

**Every plate tells a story, every guest is served with love. 🍽️**
