# Web-Builder
A modern, responsive real estate website built with HTML 5, Tailwind CSS and Javascript. It Features smooth animation, mobile friendly design, property search filters, client Testimonial and dynamic statistic showcasing of real estate website with a professional online presence inspired by Marci Metzger and The Ridge Realty Group.


#  Marci Metzger - The Ridge Realty Group | Pahrump Realtor

A professional and responsive real estate portfolio website built using **HTML**, **JavaScript**, and **Tailwind CSS**.  
The website showcases listings, client testimonials, contact options, and realtor information with smooth animations and mobile-friendly design.

---

##  Features

- **Responsive Design:** Built entirely with Tailwind CSS for seamless viewing across all devices.  
- **Animated Navigation:** Sticky navbar with smooth scrolling and section highlighting.  
- **Hero Section:** Gradient overlays, animated headings, and dynamic statistics.  
- **Interactive Components:**  
  - Mobile-friendly hamburger navigation  
  - Property search filters  
  - Animated stats counter  
  - Scroll-triggered fade-in animations  
  - Auto-playing image carousel  
- **Accessibility:** Includes ARIA labels, focus styles, and a “Skip to main content” link.  
- **Lazy Loading:** Images are loaded efficiently for improved performance.  
- **Minimal Dependencies:** No CSS files — Tailwind CSS is loaded directly from CDN.

---

##  Project Structure

```
📁 project-root
│
├── index.html          # Main HTML structure
├── script.js           # JavaScript interactions and animations
├── images/             # Folder containing all property and background images
└── README.md           # This file
```

---

##  Technologies Used

| Technology      | Purpose |
|-----------------|----------|
| **HTML5**       | Page structure and semantic content |
| **Tailwind CSS**| Utility-first styling and responsive layout |
| **Font Awesome**| Iconography |
| **JavaScript (ES6)** | Interactivity, animations, and dynamic effects |

---

##  Setup Instructions

### 1️ Clone or Download the Repository
```bash
git clone https://github.com/yourusername/marci-metzger-website.git
cd marci-metzger-website
```

### 2️ Open the Project
Simply open the `index.html` file in your browser.  
No build tools or dependencies are required since Tailwind is loaded via CDN.

### 3️ Modify Tailwind Configuration (Optional)
Tailwind custom theme extensions are declared directly in the HTML file:
```html
<script>
tailwind.config = {
  theme: {
    extend: {
      fontFamily: {
        montserrat: ['Montserrat', 'sans-serif'],
        playfair: ['Playfair Display', 'serif'],
      },
      colors: {
        primary: '#000000',
        gold: '#808080',
      },
    },
  },
};
</script>
```
You can adjust color schemes, animations, or typography to match your branding.

---

##  JavaScript Features Overview

| Feature | Description |
|----------|--------------|
| **Mobile Menu Toggle** | Expands or collapses the mobile menu with accessibility support. |
| **Smooth Scrolling** | Smoothly scrolls to sections when navigation links are clicked. |
| **Active Link Highlighting** | Highlights the current section link while scrolling. |
| **Navbar Scroll Effects** | Changes navbar style when the user scrolls. |
| **Animated Counters** | Animates sales and experience numbers in the hero section. |
| **Carousel** | Auto-playing image slider with indicators and navigation controls. |
| **Form Validation** | Basic client-side validation for the contact form. |
| **Lazy Loading** | Loads images only when they are visible in the viewport. |

---

##  Development Notes

- Tailwind CSS is imported from the official CDN:
  ```html
  <script src="https://cdn.tailwindcss.com"></script>
  ```
- No additional CSS files are required — all custom styling and animations are done via Tailwind utilities and inline `<style>` blocks.
- All JavaScript is modularized in `script.js` for clarity and maintenance.

---

##  Responsiveness

The layout has been optimized for:
- **Mobile (≤768px)** – Stack layout, larger touch targets  
- **Tablet (769–1024px)** – Two-column grids  
- **Desktop (≥1024px)** – Multi-section grid and hover effects

---

##  License

This project is released under the **MIT License**.  
You are free to modify and reuse it for personal or commercial use.

---

##  Author

**Marci Metzger**  
Realtor The Ridge Realty Group  
 Pahrump, Nevada  
 (206) 919-6886  
🌐 [https://marci-metzger.com](https://marci-metzger.com)
