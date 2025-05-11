# Alfa Romeo Website Project 🚗

## Overview 📝
This project is a responsive, multi-page website for Alfa Romeo, an Italian luxury car manufacturer. The website showcases various Alfa Romeo models, including Tonale Hybrid, Tonale Plug-in Hybrid, Stelvio, Giulia, Stelvio Quadrifoglio, and Giulia Quadrifoglio. It provides detailed information about each model, including specifications, owner reviews, and FAQs, along with a test drive booking form and interactive features like a photo gallery and a chatbot. 🌟

## Features ✨
- **Responsive Design** 📱: Optimized for desktop and mobile devices using media queries and flexible layouts.
- **Model Pages** 🚘: Individual pages for each Alfa Romeo model with detailed specifications, image galleries, and customer reviews.
- **Interactive Elements** 🖱️:
  - Swiper.js-powered image carousels for model galleries. 🖼️
  - Lightbox for enlarged photo viewing. 🔍
  - Chatbot interface for user support with links to services, FAQs, and dealer locator. 💬
  - Smooth scrolling for navigation and a "Back to Top" button. ⬆️
- **Test Drive Form** 📋: A form for users to book test drives, styled with a modern, transparent design.
- **Formula 1 Section** 🏎️: Highlights Alfa Romeo’s participation in Formula 1 with a video showcase.
- **Photo Gallery** 📸: A grid-based gallery with clickable images that open in a lightbox.
- **FAQ Section** ❓: Collapsible FAQs for each model and the main page, providing quick answers to common questions.
- **Navigation** 🧭: A hamburger menu for mobile devices and a fixed navbar with smooth scrolling to sections like "Test Drive."

## File Structure 📂
- **Alfa Romeo.html**: The main landing page with an overview of the brand, model carousel, photo gallery, pricing table, Formula 1 video, FAQs, and test drive form. 🏠
- **Model-specific pages** 🚗:
  - `tonale_hybrid.html`
  - `tonale_plugin_hybrid.html`
  - `stelvio.html`
  - `giulia.html`
  - `stelvio_quadr.html`
  - `giulia_quadr.html`
  Each model page includes a gallery, specifications, reviews, FAQs, and a back link to the main page. 🔗
- **Assets** 🗂️:
  - Images (e.g., `Tonale Hybrid front view.avif`, `giulia background.avif`) for backgrounds and galleries. 🖼️
  - Video (`alfa-romeo-f1-team-orlen-c42-reveal-downloade.co.mp4`) for the Formula 1 section. 🎥
  - Logo (`current-badge_457d965994803bd415fc9735d023d1eb.png`). 🏷️

## Technologies Used 🛠️
- **HTML5**: For semantic structure and content. 📜
- **CSS3**: For styling, including custom backgrounds, transparent overlays, and responsive design with media queries. 🎨
- **JavaScript**:
  - Swiper.js for image carousels. 🔄
  - Custom scripts for lightbox, chatbot toggle, smooth scrolling, and video autoplay on scroll. ⚙️
- **External Libraries**:
  - Google Fonts (`Roboto`) for typography. 🔠
  - Swiper.js (`v10`) for carousel functionality. 🖼️
  - Cloudflare scripts for email decoding and security. 🔒
- **Design Features**:
  - Consistent red (`#b30000`) and white color scheme reflecting Alfa Romeo’s brand identity. 🔴⚪
  - Transparent black overlays (`rgba(0,0,0,0.6)`) for text readability over background images. 🖤
  - Box shadows and border-radius for modern, polished UI elements. ✨

## Setup Instructions ⚙️
1. **Clone the Repository** 📥:
   ```bash
   git clone <repository-url>
   ```
2. **Host Locally** 🌐:
   - Use a local server like Live Server (VS Code extension) or run:
     ```bash
     python -m http.server
     ```
   - Open `http://localhost:8000/Alfa Romeo.html` in a browser.
3. **Ensure Assets** 🗃️:
   - Place all images and the video file in the same directory as the HTML files or update paths in the code.
4. **Dependencies** 📚:
   - No installation required for external libraries, as they are loaded via CDN (Swiper.js, Google Fonts).
   - Ensure an internet connection for CDN resources and Cloudflare scripts. 🌍

## Usage 🚀
- Navigate to `Alfa Romeo.html` for the main page. 🏠
- Use the navbar or hamburger menu (on mobile) to access model pages or the test drive form. 🍔
- Click on gallery images to view them in the lightbox. 🖼️
- Interact with the chatbot icon (bottom-right) for support options. 💬
- Scroll to view the Formula 1 video, which autoplays when in view. 🎥
- Use the test drive form to input details (note: form submission requires backend integration). 📋

## Notes 📌
- **Form Submission**: The test drive form is front-end only. Backend integration (e.g., Node.js, PHP) is needed for processing submissions. ⚠️
- **Image Optimization**: Use compressed images to improve load times, as some `.avif` and `.jpeg` files may be large. 🖼️
- **Cross-browser Compatibility**: Tested on modern browsers (Chrome, Firefox, Safari). Ensure compatibility for older browsers if needed. 🌐
- **Accessibility**: Consider adding ARIA labels and keyboard navigation for improved accessibility. ♿

## Future Improvements 🔮
- Add backend for form submission to handle test drive bookings. 📬
- Implement a search bar for easier navigation. 🔍
- Enhance accessibility with ARIA attributes and better contrast ratios. ♿
- Add animations for smoother transitions between sections. 🎬
- Integrate a CMS for dynamic content updates (e.g., new models, prices). 📈