---
description: Repository Information Overview
alwaysApply: true
---

# Continental Metal Corporation Website

## Summary
Continental Metal Corporation is a static WordPress-based website built with the CryptLight theme and Elementor page builder. The site serves as a corporate presence showcasing metal products and services, featuring product galleries, contact forms, and marketing content. The repository contains HTML, CSS, JavaScript assets, images, and WordPress theme/plugin files.

## Structure
- **index.html**: Main website entry point (1,781 lines)
- **assests/**: WordPress theme, plugins, and CSS/JS assets directory
  - **wp-content/**: WordPress plugins and theme files
    - **themes/cryptlight/**: CryptLight theme with custom styles, scripts, and icon libraries
    - **plugins/**: Elementor, Elementor Pro, Contact Form 7, and other WordPress plugins
    - **uploads/**: Elementor-generated CSS files and media uploads
  - **wp-includes/**: Core WordPress files, jQuery library, and utilities
- **css/**: Global CSS stylesheets
- **css-1**: Google Fonts CSS loader
- **s/**: Google Font files (Poppins, Roboto, Roboto Slab)
- **Image Directories**: Product images and assets organized in content-based folders (gold nuggets, iridium, osmium, NFT game, illustrations, etc.)

## Technology Stack
**Type**: Static WordPress Website  
**Theme**: CryptLight  
**Page Builder**: Elementor (v6.x)  
**Plugins**: Contact Form 7, Elementor Pro  
**Client Library**: jQuery (bundled)

## Key Resources

**Main Files**:
- `index.html` - Primary website page with full WordPress/Elementor markup
- `assests/wp-content/themes/cryptlight/style3781.css` - Main theme stylesheet
- `assests/wp-content/themes/cryptlight/assets/js/script.js` - Theme JavaScript

**Styling System**:
- CSS Custom Properties (--primary, --text, --primary-font, etc.)
- Primary Color: #3772FF
- Primary Font: Poppins
- Responsive layout with sidebar width: 320px
- Container width: 1290px

**JavaScript Libraries**:
- jQuery (wp-includes/js/jquery/jquery.min5aed.js)
- Owl Carousel (carousel library)
- Elementor frontend JavaScript (frontend.min9086.js)
- Contact Form 7 validation (index77e1.js)
- Waypoints, custom animations

## Features & Components
- **Elementor Sections**: Multiple elementor post pages (ID: 7, 3325, etc.)
- **Header Navigation**: Sticky header with logo and navigation
- **Contact Forms**: Contact Form 7 integration
- **Image Gallery**: Product image carousel and gallery displays
- **Team Section**: Team member display with custom image styling (250px height)
- **Responsive Design**: Mobile-optimized layout with hidden elements for phone displays

## Asset Management
- **Image Formats**: PNG, JPG
- **Icon Fonts**: OvaIcon custom font library, Font Awesome icons
- **Google Fonts**: Poppins, Roboto, Roboto Slab via Google Fonts API
- **Font Loading**: Bunny Fonts CDN prefetch configured

## Configuration
**CSRF Protection**: Implemented via meta tag (token: UjGy6yUyKhLU8nDghs8BIfJUkfImgchUpt0av9qC)  
**Viewport**: Width=device-width, initial-scale=1  
**Favicon**: cropped-rm1-32x32.png, 192x192.png; Apple touch icon available

## Deployment & Access
- **Hosted At**: c:\laragon\www\continentalmetalcorporation (local Laragon development environment)
- **Entry Point**: index.html (direct access in browser)
- **Development Server**: Served via Laragon's built-in web server

## Notes
This is a static site repository - no build process, package managers, or testing framework. Updates to content would typically be made through Elementor's visual editor or direct HTML/CSS modification. The WordPress structure suggests this was generated from a WordPress site export, preserving all assets as static files.
