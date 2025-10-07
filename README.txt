╔═══════════════════════════════════════════════════════════════════════════╗
║                        MODENGINE2 WEBSITE                                 ║
║                   Professional Multi-Page Website                         ║
║                       README & SETUP GUIDE                                ║
╚═══════════════════════════════════════════════════════════════════════════╝

┌───────────────────────────────────────────────────────────────────────────┐
│ TABLE OF CONTENTS                                                         │
├───────────────────────────────────────────────────────────────────────────┤
│ 1. Introduction                                                           │
│ 2. File Structure                                                         │
│ 3. Quick Start Guide                                                      │
│ 4. Customization Instructions                                            │
│ 5. Color Palette Customization                                           │
│ 6. Updating Links & URLs                                                 │
│ 7. Content Modification                                                   │
│ 8. SEO & Keywords                                                         │
│ 9. Responsive Design Notes                                               │
│ 10. Browser Compatibility                                                │
│ 11. Troubleshooting                                                       │
│ 12. Support & Credits                                                     │
└───────────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════════
1. INTRODUCTION
═══════════════════════════════════════════════════════════════════════════

Welcome to the ModEngine2 Website!

This is a professional, modern, responsive multi-page website built with:
• HTML5 (semantic markup)
• CSS3 (modern styling with Flexbox & Grid)
• Vanilla JavaScript (no dependencies)
• Mobile-first responsive design
• Smooth animations and transitions
• SEO-optimized structure

Design inspired by modengine2.com with a cleaner, more professional look.

═══════════════════════════════════════════════════════════════════════════
2. FILE STRUCTURE
═══════════════════════════════════════════════════════════════════════════

ModEngine2-Website/
│
├── index.html          → Home page with hero section, features, keywords
├── about.html          → About page with mission, vision, values
├── contact.html        → Contact page with Google Form button
├── download.html       → Download page with download button
├── style.css           → All styling (colors, layouts, animations)
├── script.js           → JavaScript functionality (menu, animations)
└── README.txt          → This file (setup & customization guide)

═══════════════════════════════════════════════════════════════════════════
3. QUICK START GUIDE
═══════════════════════════════════════════════════════════════════════════

METHOD 1: Open Locally
──────────────────────────────────────────────────────────────────────────
1. Extract all files to a folder
2. Double-click "index.html" to open in your default browser
3. Navigate using the menu to explore all pages

METHOD 2: Use a Local Server (Recommended for Development)
──────────────────────────────────────────────────────────────────────────
If you have Python installed:

   # Python 3
   python -m http.server 8000

If you have Node.js installed:

   # Install http-server globally (one time)
   npm install -g http-server
   
   # Run server
   http-server

Then open: http://localhost:8000 in your browser

METHOD 3: Deploy to Web Hosting
──────────────────────────────────────────────────────────────────────────
Upload all files to your web hosting via FTP/SFTP or hosting control panel.

Popular free hosting options:
• GitHub Pages (free, easy)
• Netlify (free tier)
• Vercel (free tier)
• Firebase Hosting (free tier)

═══════════════════════════════════════════════════════════════════════════
4. CUSTOMIZATION INSTRUCTIONS
═══════════════════════════════════════════════════════════════════════════

This website is designed to be easily customizable. Below are detailed
instructions for common customization tasks.

═══════════════════════════════════════════════════════════════════════════
5. COLOR PALETTE CUSTOMIZATION
═══════════════════════════════════════════════════════════════════════════

Current Color Palette:
──────────────────────────────────────────────────────────────────────────
Primary Color:    #C46C11 (Orange/Brown)
Secondary Color:  #FFFFFF (White)
Accent Color:     #C46C11 (Same as primary)
Text Color:       #000000 (Black)
Background Light: #F8F8F8
Background Dark:  #1A1A1A

How to Change Colors:
──────────────────────────────────────────────────────────────────────────
Open "style.css" and locate the ":root" section at the top:

:root {
    --primary-color: #C46C11;      ← Change this
    --secondary-color: #FFFFFF;    ← Change this
    --accent-color: #C46C11;       ← Change this
    --text-color: #000000;         ← Change this
    --bg-light: #F8F8F8;
    --bg-dark: #1A1A1A;
}

Replace the hex color codes with your desired colors.
Save the file and refresh your browser to see changes.

Color Tools:
• Coolors.co - Generate color palettes
• Adobe Color - Professional color schemes
• ColorHunt.co - Curated color palettes

═══════════════════════════════════════════════════════════════════════════
6. UPDATING LINKS & URLs
═══════════════════════════════════════════════════════════════════════════

A. Replace Google Form Link
──────────────────────────────────────────────────────────────────────────
Open "contact.html" and find:

<a href="https://docs.google.com/forms/d/e/1FAIpQLSf...">

Replace the entire URL with your new Google Form link.

B. Replace Download Link
──────────────────────────────────────────────────────────────────────────
Open "download.html" and find:

<a href="https://modengine2.com/download/" target="_blank" class="download-button">

Replace with your download page URL.

C. Replace GitHub Link
──────────────────────────────────────────────────────────────────────────
Open ANY HTML file and find:

<a href="https://github.com/open-ssh/ModEngine2" target="_blank">

Replace with your GitHub repository URL.

Note: This link appears in:
• Navigation menu (all pages)
• Footer (all pages)
• Contact page
• Download page

D. Replace Official Website Link
──────────────────────────────────────────────────────────────────────────
Open "index.html" and find:

<a href="https://modengine2.com/" target="_blank">

Replace with your official website URL.

═══════════════════════════════════════════════════════════════════════════
7. CONTENT MODIFICATION
═══════════════════════════════════════════════════════════════════════════

A. Change Site Title & Logo
──────────────────────────────────────────────────────────────────────────
Open each HTML file and find:

<a href="index.html" class="logo">ModEngine2</a>

Replace "ModEngine2" with your site name.

Also update the <title> tag in each file:

<title>Your Site Name - Page Name</title>

B. Modify Hero Section
──────────────────────────────────────────────────────────────────────────
Open "index.html" and locate:

<section class="hero">
    <div class="hero-content">
        <h1>Welcome to <span>ModEngine2</span></h1>
        <p>Your description here...</p>

Edit the heading and paragraph text as needed.

C. Update Features/Cards
──────────────────────────────────────────────────────────────────────────
Find the ".feature-card" sections and edit:

<div class="feature-card">
    <div class="feature-icon">🚀</div>
    <h3>Feature Title</h3>
    <p>Feature description...</p>
</div>

You can change the emoji icon, title, and description.

D. Modify Footer
──────────────────────────────────────────────────────────────────────────
Open any HTML file and find the <footer> section:

<div class="footer-bottom">
    <p>&copy; 2024 ModEngine2. All rights reserved.</p>
    <p>Designed & Developed with ❤️ for the Modding Community</p>
</div>

Update year, site name, and tagline as needed.

═══════════════════════════════════════════════════════════════════════════
8. SEO & KEYWORDS
═══════════════════════════════════════════════════════════════════════════

Keywords with Links (index.html):
──────────────────────────────────────────────────────────────────────────
The following keywords are naturally integrated with their respective URLs:

1. "mod engine 2" 
   → https://modengine2.com/

2. "mod engine 2 cracked elden ring"
   → https://modengine2.com/how-to-launch-elden-ring-with-mod-engine-2/

3. "seamless coop mod engine 2"
   → https://modengine2.com/how-to-use-seamless-co-op-with-mod-engine-2/

To Update Keywords:
──────────────────────────────────────────────────────────────────────────
Open "index.html" and search for the keyword text. Update the anchor tag:

<a href="YOUR_NEW_URL">your keyword text</a>

Meta Tags:
──────────────────────────────────────────────────────────────────────────
Each page has meta tags in the <head> section:

<meta name="description" content="Page description here...">
<meta name="keywords" content="keyword1, keyword2, keyword3">

Update these for better SEO.

═══════════════════════════════════════════════════════════════════════════
9. RESPONSIVE DESIGN NOTES
═══════════════════════════════════════════════════════════════════════════

This website is fully responsive and tested on:
• Desktop (1920px and above)
• Laptop (1366px - 1920px)
• Tablet (768px - 1365px)
• Mobile (320px - 767px)

Breakpoints are defined in style.css:

@media (max-width: 768px) { ... }  → Tablet & Mobile
@media (max-width: 480px) { ... }  → Small Mobile

Mobile Navigation:
──────────────────────────────────────────────────────────────────────────
• Hamburger menu (☰) appears on mobile
• Click to open/close navigation
• Auto-closes when clicking a link
• Can be closed with ESC key

═══════════════════════════════════════════════════════════════════════════
10. BROWSER COMPATIBILITY
═══════════════════════════════════════════════════════════════════════════

Tested and compatible with:
• Google Chrome (latest)
• Mozilla Firefox (latest)
• Microsoft Edge (latest)
• Safari (latest)
• Opera (latest)

Note: Internet Explorer is NOT supported (deprecated browser).

═══════════════════════════════════════════════════════════════════════════
11. TROUBLESHOOTING
═══════════════════════════════════════════════════════════════════════════

Issue: Styles not loading
Solution: Ensure style.css is in the same folder as HTML files.
          Check the <link> tag path in HTML files.

Issue: JavaScript not working
Solution: Ensure script.js is in the same folder as HTML files.
          Check browser console for errors (F12 → Console).

Issue: Links not working
Solution: Verify all href attributes have correct URLs.
          Check for typos in file paths.

Issue: Mobile menu not closing
Solution: Clear browser cache and refresh.
          Ensure script.js is loaded properly.

Issue: Animations not smooth
Solution: Test in a different browser.
          Disable browser extensions that might interfere.

Issue: Colors not changing after editing CSS
Solution: Hard refresh the page (Ctrl+Shift+R or Cmd+Shift+R).
          Clear browser cache.

═══════════════════════════════════════════════════════════════════════════
12. SUPPORT & CREDITS
═══════════════════════════════════════════════════════════════════════════

Design Inspiration: modengine2.com
Fonts: Google Fonts (Poppins)
Icons: Unicode emojis & inline SVGs

Credits:
──────────────────────────────────────────────────────────────────────────
Designed & Developed for the ModEngine2 Community
Built with HTML5, CSS3, and Vanilla JavaScript
No frameworks or libraries required
100% customizable and extendable

═══════════════════════════════════════════════════════════════════════════

Thank you for using this website template!

For questions or support, please visit:
• GitHub: https://github.com/open-ssh/ModEngine2
• Website: https://modengine2.com/

═══════════════════════════════════════════════════════════════════════════

Last Updated: 2024
Version: 1.0

═══════════════════════════════════════════════════════════════════════════
