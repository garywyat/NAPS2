================================================================================
                    NAPS2 WEBSITE - README & DOCUMENTATION
================================================================================

Welcome to the NAPS2 Website!

This is a professional, modern, responsive multi-page website built with HTML, 
CSS, and JavaScript. The design is clean, elegant, and optimized for all devices.

================================================================================
                              FILE STRUCTURE
================================================================================

📁 Project Root
├── 📄 index.html           - Home page with hero section and features
├── 📄 about.html           - About page with mission and vision
├── 📄 contact.html         - Contact page with Google Form button
├── 📄 download.html        - Download page with download button
├── 📄 style.css            - All styling and responsive design
├── 📄 script.js            - Interactive features and animations
└── 📄 README.txt           - This file with instructions

================================================================================
                         HOW TO RUN THE WEBSITE
================================================================================

METHOD 1: Direct File Opening
------------------------------
1. Navigate to the project folder (D:\2Naps2)
2. Double-click on "index.html" to open it in your default browser
3. Navigate between pages using the menu

METHOD 2: Local Development Server (Recommended)
-------------------------------------------------
If you have Python installed:

1. Open Command Prompt or Terminal
2. Navigate to the project folder:
   cd D:\2Naps2

3. Run a local server:
   - For Python 3:
     python -m http.server 8000
   
   - For Python 2:
     python -m SimpleHTTPServer 8000

4. Open your browser and go to:
   http://localhost:8000

METHOD 3: Live Server (VS Code)
--------------------------------
If you use Visual Studio Code:

1. Install the "Live Server" extension
2. Right-click on index.html
3. Select "Open with Live Server"

================================================================================
                         CUSTOMIZATION GUIDE
================================================================================

1. CHANGING COLORS
------------------
Open "style.css" and find the ":root" section at the top:

:root {
    --primary-color: #E2A4CB;      /* Main pink color */
    --secondary-color: #AA9BE9;    /* Purple accent color */
    --white: #FFFFFF;              /* White */
    --black: #000000;              /* Black/Dark text */
}

Replace these hex color codes with your preferred colors.

2. UPDATING LINKS
-----------------

A) Google Form Link (Contact Page):
   - Open "contact.html"
   - Find this line (around line 65):
     href="https://docs.google.com/forms/d/e/1FAIpQLScxEwSL-PwT21F_ey5yT1CKvfhqPxw_R5Pc1g7pVeeSc0JJjQ/viewform?usp=header"
   - Replace with your Google Form URL

B) Download Link:
   - Open "download.html"
   - Find this line (around line 67):
     href="https://naps2.net/download/"
   - Replace with your download URL

C) GitHub Repository Link:
   - Open any HTML file
   - Find all instances of:
     href="https://github.com/naps22/Naps-2"
   - Replace with your GitHub repository URL

D) Official Website Link:
   - Open any HTML file
   - Find all instances of:
     href="https://naps2.net/"
   - Replace with your official website URL

3. CHANGING TEXT & KEYWORDS
----------------------------

Home Page Keywords (index.html):
--------------------------------
The following keywords are naturally integrated with links:

1. "naps2 scanner" - Links to: https://naps2.net/
   Location: Feature card section, line ~60

2. "naps2 auto crop" - Links to: https://naps2.net/naps2-auto-crop/
   Location: Feature card section, line ~67

3. "naps2 scanner download for windows 7 64 bit" 
   Links to: https://naps2.net/download-and-install-naps2-v-4-7-2/
   Location: Feature card section, line ~82

To update these:
- Open index.html
- Search for the keyword text
- Update the text and/or the href link as needed

4. EDITING CONTENT
------------------

Hero Section:
- Open "index.html"
- Find the <header class="hero"> section
- Edit the title, subtitle, and button text

Navigation Menu:
- Open any HTML file
- Find the <nav class="navbar"> section
- Edit menu items in the <ul class="nav-menu"> list

Footer:
- Open any HTML file
- Find the <footer class="footer"> section
- Edit company name, year, links, and text

About Page Content:
- Open "about.html"
- Edit mission, vision, and values sections

5. CHANGING FONTS
-----------------
Current font: Poppins (from Google Fonts)

To change:
1. Visit https://fonts.google.com/
2. Select your preferred font
3. Copy the <link> code
4. Replace the font link in ALL HTML files (in <head> section)
5. Open "style.css" and update font-family in body selector

6. ADDING IMAGES
----------------
To add images:

1. Create an "images" folder in the project root
2. Place your images in this folder
3. In HTML, add:
   <img src="images/your-image.jpg" alt="Description">

For the image placeholder in index.html:
- Replace the SVG in <div class="image-placeholder">
- With: <img src="images/your-image.jpg" alt="Description">

7. MODIFYING RESPONSIVE BREAKPOINTS
------------------------------------
Open "style.css" and scroll to the bottom:

@media (max-width: 968px) { ... }  /* Tablets */
@media (max-width: 768px) { ... }  /* Mobile landscape */
@media (max-width: 480px) { ... }  /* Mobile portrait */

Adjust these breakpoints and styles as needed.

================================================================================
                         FEATURES & FUNCTIONALITY
================================================================================

✓ Fully responsive design (mobile, tablet, desktop)
✓ Modern gradient color scheme
✓ Smooth animations and transitions
✓ Mobile navigation menu with hamburger icon
✓ Scroll-to-top button
✓ Parallax effect on hero section
✓ Fade-in animations on scroll
✓ Interactive button ripple effects
✓ Active navigation link highlighting
✓ Smooth scrolling for anchor links
✓ SEO-friendly semantic HTML
✓ Cross-browser compatible
✓ Fast loading and optimized performance

================================================================================
                         BROWSER COMPATIBILITY
================================================================================

✓ Chrome (latest)
✓ Firefox (latest)
✓ Safari (latest)
✓ Edge (latest)
✓ Opera (latest)

Minimum supported versions:
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

================================================================================
                         DEPLOYMENT OPTIONS
================================================================================

OPTION 1: GitHub Pages
-----------------------
1. Create a GitHub repository
2. Upload all files
3. Go to Settings > Pages
4. Select branch and folder
5. Your site will be live at: username.github.io/repository-name

OPTION 2: Netlify
-----------------
1. Sign up at netlify.com
2. Drag and drop your project folder
3. Your site will be deployed instantly
4. Free SSL certificate included

OPTION 3: Vercel
----------------
1. Sign up at vercel.com
2. Import your GitHub repository or upload files
3. Deploy with one click

OPTION 4: Traditional Web Hosting
----------------------------------
1. Use FTP client (FileZilla, etc.)
2. Upload all files to your hosting server
3. Ensure index.html is in the root directory

================================================================================
                         MAINTENANCE & UPDATES
================================================================================

Regular Updates:
- Check for broken links monthly
- Update year in footer annually (automatic via script.js)
- Keep keywords and content fresh for SEO
- Test on new browser versions periodically

Performance Optimization:
- Compress images before adding (use TinyPNG or similar)
- Minify CSS and JS for production (use online tools)
- Enable gzip compression on your server
- Use CDN for faster global delivery

================================================================================
                         SEO OPTIMIZATION
================================================================================

✓ Meta descriptions on all pages
✓ Semantic HTML5 structure
✓ Proper heading hierarchy (H1, H2, H3)
✓ Alt text for images (when added)
✓ Fast loading speed
✓ Mobile-friendly design
✓ Clean URL structure
✓ Internal linking strategy
✓ Focus keywords naturally integrated

To improve SEO further:
1. Add XML sitemap
2. Create robots.txt file
3. Submit to Google Search Console
4. Add Google Analytics tracking code
5. Add Open Graph tags for social sharing
6. Create a blog section for regular content updates

================================================================================
                         TROUBLESHOOTING
================================================================================

Problem: Navigation menu not working on mobile
Solution: Check if script.js is properly linked in HTML files

Problem: Styles not loading
Solution: Verify style.css path is correct in all HTML files

Problem: Colors look different
Solution: Check browser compatibility for CSS gradients and 
          background-clip properties

Problem: Links not working
Solution: Verify all href attributes have correct URLs
          Check for typos in file paths

Problem: Animations not smooth
Solution: Test on different devices/browsers
          Check if hardware acceleration is enabled

================================================================================
                         SUPPORT & RESOURCES
================================================================================

HTML Reference: https://developer.mozilla.org/en-US/docs/Web/HTML
CSS Reference: https://developer.mozilla.org/en-US/docs/Web/CSS
JavaScript Reference: https://developer.mozilla.org/en-US/docs/Web/JavaScript

Color Palette Tools:
- Coolors.co - Generate color schemes
- Adobe Color - Color wheel and themes
- ColorSpace - Gradient generators

Free Stock Images:
- Unsplash.com
- Pexels.com
- Pixabay.com

Icon Resources:
- Font Awesome - Icon fonts
- Feather Icons - Simple, clean icons
- Heroicons - Hand-crafted SVG icons

================================================================================
                         CREDITS & LICENSE
================================================================================

Design & Development: Custom built for NAPS2
Font: Poppins by Google Fonts (Open Font License)
Color Palette: #E2A4CB, #FFFFFF, #AA9BE9, #000000

This website template is provided as-is for the NAPS2 project.
Feel free to modify, customize, and deploy as needed.

================================================================================
                         VERSION HISTORY
================================================================================

Version 1.0 (2024)
- Initial release
- 4 responsive pages (Home, About, Contact, Download)
- Modern gradient design
- Mobile-first approach
- Interactive JavaScript features
- SEO optimized
- Keyword integration with natural internal linking

================================================================================
                         CONTACT & FEEDBACK
================================================================================

For questions or suggestions about this website template:
- Visit: https://naps2.net/
- GitHub: https://github.com/naps22/Naps-2
- Use the contact form on the website

================================================================================

Thank you for using the NAPS2 Website!
Built with ❤️ for professional document scanning.

================================================================================
