# Web-Builder - Marci Metzger Real Estate Website

A modern, responsive real estate website built with HTML5, Tailwind CSS and JavaScript. It features smooth animations, mobile-friendly design, property search filters, client testimonials and dynamic statistics showcasing for a professional online presence inspired by Marci Metzger and The Ridge Realty Group.

## Overview
This is a modern, professional revamp of Marci Metzger's real estate website homepage built with **Tailwind CSS**. The redesign maintains all original content while significantly improving the design, user experience, and functionality.

## Features

### Design Improvements
- **Modern Layout**: Built with Tailwind CSS for consistent, modern design
- **Responsive Design**: Fully responsive across all devices (desktop, tablet, mobile)
- **Professional Color Scheme**: Real estate-appropriate colors with custom Tailwind configuration
- **Improved Typography**: Uses Google Fonts (Montserrat & Playfair Display) for better readability
- **Animated Navigation**: Sticky navbar with smooth scrolling and section highlighting
- **Hero Section**: Gradient overlays, animated headings, and dynamic statistics

### Interactive Components
- **Mobile-friendly hamburger navigation**
- **Property search filters**
- **Animated stats counter**
- **Scroll-triggered fade-in animations**
- **Auto-playing image carousel**
- **Accessibility**: Includes ARIA labels, focus styles, and a "Skip to main content" link
- **Lazy Loading**: Images are loaded efficiently for improved performance

### Functionality
- **Search Form**: Interactive property search with form validation
- **Contact Form**: Working contact form with validation and modern styling
- **Google Maps Integration**: Interactive map showing office location
- **Social Integration**: WhatsApp contact option
- **Performance**: Optimized with Tailwind CSS and smooth animations

## Project Structure
```
📁 Web-Builder
│
├── index.html          # Main HTML structure with Tailwind CSS classes
├── script.js           # JavaScript interactions and animations
├── images/             # Folder containing all property and background images
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Technologies Used

| Technology      | Purpose |
|-----------------|----------|
| **HTML5**       | Semantic markup and modern HTML structure |
| **Tailwind CSS**| Utility-first CSS framework for rapid development |
| **Font Awesome**| Iconography |
| **JavaScript (ES6+)** | Interactive functionality, form handling, and animations |
| **Google Maps API** | Interactive map showing office location |

## Setup Instructions

### 1️⃣ Clone or Download the Repository
```bash
git clone https://github.com/Hjmontalban/Web-Builder.git
cd Web-Builder
```

### 2️⃣ Open the Project
Simply open the `index.html` file in your browser.  
No build tools or dependencies are required since Tailwind is loaded via CDN.

### 3️⃣ Google Maps Setup (Optional)
1. Get a free Google Maps API key from [Google Cloud Console](https://developers.google.com/maps/documentation/javascript/get-api-key)
2. Replace `YOUR_GOOGLE_MAPS_API_KEY` in the HTML file with your actual API key
3. Enable the following APIs in Google Cloud Console:
   - Maps JavaScript API
   - Places API (optional, for enhanced features)

## JavaScript Features Overview

| Feature | Description |
|----------|--------------|
| **Mobile Menu Toggle** | Expands or collapses the mobile menu with accessibility support |
| **Smooth Scrolling** | Smoothly scrolls to sections when navigation links are clicked |
| **Active Link Highlighting** | Highlights the current section link while scrolling |
| **Navbar Scroll Effects** | Changes navbar style when the user scrolls |
| **Animated Counters** | Animates sales and experience numbers in the hero section |
| **Carousel** | Auto-playing image slider with indicators and navigation controls |
| **Form Validation** | Basic client-side validation for the contact form |
| **Lazy Loading** | Loads images only when they are visible in the viewport |

## Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Responsiveness

The layout has been optimized for:
- **Mobile (≤768px)** – Stack layout, larger touch targets  
- **Tablet (769–1024px)** – Two-column grids  
- **Desktop (≥1024px)** – Multi-section grid and hover effects

## Performance Features
- Lazy loading for images
- Smooth scroll behavior
- Optimized CSS and JavaScript
- Fast loading times
- Minimal Dependencies: No CSS files — Tailwind CSS is loaded directly from CDN

## Contact Integration
- Phone numbers are clickable for mobile users
- WhatsApp integration for instant messaging
- Contact form with validation
- Social media ready (easily extensible)

## License

This project is released under the **MIT License**.  
You are free to modify and reuse it for personal or commercial use.

## Author

**Marci Metzger**  
Realtor - The Ridge Realty Group  
📍 Pahrump, Nevada  
📞 (206) 919-6886  
🌐 [https://marci-metzger.com](https://marci-metzger.com)

---

**Note**: This is a single-page website focusing on the homepage. For a full website, you would need to create additional pages for listings, about, etc.