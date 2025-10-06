 Taste Haven - Restaurant Menu Website

Overview
Taste Haven is a fully responsive, single-page static website for a restaurant menu. It features a sleek dark theme with sections for "Today's Special," Starters, Main Course, and Desserts. The design emphasizes simplicity, accessibility, and mobile-friendliness, using only HTML5 and CSS3—no JavaScript or external dependencies required. Images are embedded as base64 data URIs for instant loading and offline compatibility.

This project serves as a showcase of modern web design principles, including CSS Grid for layouts, sticky navigation, and hover animations.

Features
- Sticky Navigation Bar: Fixed top menu with anchor links for smooth scrolling to sections (#special, #starters, #main-course, #desserts).
- Responsive Layout: 
  - Uses CSS Grid for menu item cards that adapt to screen size (auto-fit columns).
  - Mobile-optimized: Navigation stacks vertically on screens under 600px.
- Menu Sections:
  - Today's Special: A highlighted, bordered section for daily features.
  - Starters, Main Course, Desserts**: Grid of cards with images, titles, descriptions, and prices.
- Visual Effects:
  - Hover animations on menu items (lift effect with enhanced shadow).
  - Gradient backgrounds and custom colors (e.g., #ffb703 for accents).
- Self-Contained Design: No external files needed—everything (styles, images) is inline.
- Accessibility: Semantic HTML, alt attributes on images, high contrast for readability.
- Performance: Lightweight (~10KB) and loads instantly in any browser.

Demo
- Save the code as `index.html` and open in a web browser.
- Live preview: [Paste the code into an online HTML editor like CodePen or JSFiddle](https://codepen.io/pen/) for instant viewing.

Installation & Usage
1. Setup:
   - Copy the entire HTML code into a new file named `index.html`.
   - No additional tools or servers required—it's a static file.

2. Running the Site:
   - Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).
   - Navigate using the top menu or scroll manually.

3. Customization:
   - Edit Menu Items: Modify the `<div class="menu-item">` blocks in each `.menu-section` (e.g., change dish names, prices, descriptions, or swap base64 images).
   - Styling: Tweak colors, fonts, or layouts in the `<style>` section (e.g., change `background: #1c1c1c;` for a different theme).
   - Add Sections: Duplicate the `<h3>` and `.menu-section` structure for new categories (e.g., Beverages).
   - Fonts: The site uses 'Poppins' (Google Fonts fallback to sans-serif). Add `<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap">` in `<head>` for custom loading if needed.
   - Deployment: Upload to any static host (GitHub Pages, Netlify, Vercel) for free hosting.

4. Browser Compatibility: Works on all modern browsers (IE11+ with minor tweaks for Grid support).


Technologies & Tools
- HTML5: Semantic structure (e.g., `<nav>`, `<header>`, `<section>`, `<footer>`).
- CSS3:
  - Layout: CSS Grid (`grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`), Flexbox for navigation.
  - Animations: `transition` for hovers, `transform: translateY(-8px)` for lift effect.
  - Responsiveness: Media queries (`@media (max-width: 600px)`).
  - Styling: Gradients, shadows, custom properties (e.g., colors like `#ffb703` for branding).
- Images: Base64-encoded JPEGs (e.g., `data:image/jpeg;base64,...`) for dishes—ensures no external HTTP requests.
- Fonts: 'Poppins' sans-serif (system fallback).
