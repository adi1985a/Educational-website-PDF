# 🖥️ Computer Monitors - Technical Overview

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![jQuery](https://img.shields.io/badge/jQuery-2.2.4-0769AD.svg?logo=jquery)](https://jquery.com/)
[![Google Fonts](https://img.shields.io/badge/Google%20Fonts-Open%20Sans-4285F4.svg?logo=googlefonts)](https://fonts.google.com/specimen/Open+Sans)

## 📋 Table of Contents
1. [📋 Overview](#-overview)
2. [✨ Features](#-features)
3. [🖼️ Screenshots](#️-screenshots)
4. [📋 Requirements](#-requirements)
5. [🚀 Setup](#-setup)
6. [🎮 Usage](#-usage)
7. [📁 File Structure](#-file-structure)
8. [⚙️ Technical Features](#️-technical-features)
9. [📝 Notes](#-notes)
10. [🤝 Contributing](#-contributing)
11. [📄 License](#-license)
12. [📧 Contact](#-contact)

## 📋 Overview
Computer Monitors - Technical Overview is a modern, responsive HTML-based educational website detailing CRT and LCD monitor technologies, connectors (VGA, DVI, HDMI, DisplayPort), and future displays (PDP, OLED). It features a hero section, modern navigation with icons, dark mode toggle, smooth animations, and comprehensive content sections. Styled with modern CSS, Google Fonts (Montserrat, Roboto), and Font Awesome icons for enhanced user experience.

<br><br>
<p align="center">
  <img src="screenshots/1.gif" width="85%">
</p>

## ✨ Features
- 🎯 **Hero Section**: Eye-catching header with background image and call-to-action button
- 🧭 **Modern Navigation**: Sticky navigation bar with Font Awesome icons and dark mode toggle
- 🌙 **Dark Mode**: Toggle between light and dark themes with localStorage persistence
- 📚 **Table of Contents**: Organized navigation with icons and smooth scrolling to sections
- 🔧 **Detailed Sections**: Covers construction, operating principles, mask/matrix types, pros/cons, and parameters for CRT and LCD monitors
- 🎨 **Interactive Elements**: Hover effects, fade-in animations, and smooth transitions
- 🔌 **Connector Guide**: Explains DSUB, DVI, HDMI, and DisplayPort with images and diagrams
- 🚀 **Future Technologies**: Discusses PDP and OLED displays with detailed explanations
- 📱 **Responsive Design**: Mobile-first approach with breakpoints for all devices
- ⬆️ **Back to Top Button**: Fixed button in top-right corner for easy navigation
- 📊 **Scroll Progress Indicator**: Visual progress bar at the top of the page
- ⏳ **Loading Animation**: Smooth loading transition when page loads
- 👆 **Touch Support**: Swipe gestures and touch-friendly interface for mobile devices
- 🔍 **SEO Optimized**: Meta tags, semantic HTML, and proper structure

## 🖼️ Screenshots

_Screenshots of: the website's main page with the table of contents, examples of the detailed sections on CRT/LCD monitors with images, the display connector guide, and the scroll-to-top button in action._

<p align="center">
  <img src="screenshots/1.jpg" width="300" "/>
  <img src="screenshots/2.jpg" width="300" "/>
  <img src="screenshots/3.jpg" width="300" "/>
  <img src="screenshots/4.jpg" width="300" "/>
  <img src="screenshots/5.jpg" width="300" "/>
  <img src="screenshots/6.jpg" width="300" "/>
  <img src="screenshots/7.jpg" width="300" "/>
  <img src="screenshots/8.jpg" width="300" "/>
  <img src="screenshots/9.jpg" width="300" "/>
  <img src="screenshots/10.jpg" width="300" "/>
  <img src="screenshots/11.gif" width="300" "/>
  <img src="screenshots/12.jpg" width="300" "/>
  <img src="screenshots/13.jpg" width="300" "/>
  <img src="screenshots/14.jpg" width="300" "/>
  <img src="screenshots/15.jpg" width="300" "/>
  <img src="screenshots/16.jpg" width="300" "/>
  <img src="screenshots/17.jpg" width="300" "/>
  <img src="screenshots/18.jpg" width="300" "/>
  <img src="screenshots/19.jpg" width="300" "/>
  <img src="screenshots/20.jpg" width="300" "/>
</p>

## 📋 Requirements
- 🌐 Web browser (e.g., Chrome, Firefox, Safari, Edge)
- 📡 Internet connection for external resources:
  - ⚡ jQuery (`https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js`)
  - 📜 jQuery ScrollTo (`jquery.scrollTo.min.js`)
  - 🔤 Google Fonts (`Montserrat`, `Roboto`)
  - 🎨 Font Awesome (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css`)
  - 🖼️ Unsplash image for hero background
- 💾 Local assets:
  - 🎨 `style.css`: Modern stylesheet with animations and responsive design
  - 📜 `jquery.scrollTo.min.js`: jQuery plugin for smooth scrolling
  - 🖼️ `img/`: Images and diagrams (e.g., `budowa-crt.png`, `zlacze1.png`, `maska1.png`)

## 🚀 Setup
1. 📥 Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. 📁 Ensure the required assets are in place:
   - 🎨 `style.css`: Modern stylesheet with animations, dark mode, and responsive design
   - 📜 `jquery.scrollTo.min.js`: jQuery plugin for smooth scrolling
   - 🖼️ `img/`: Images for diagrams, masks, matrices, and connectors
3. 🌐 Host the site on a web server (e.g., Apache, Nginx) or open `index.html` directly:
   ```bash
   python -m http.server 8000
   ```
4. 🔗 Access the site at `http://localhost:8000`.

## 🎮 Usage
1. 🌐 Open the website in a browser to view the modern homepage with hero section.
2. 🖥️ **Interface**:
   - 🎯 **Hero Section**: Eye-catching header with background image and "Explore" button
   - 🧭 **Navigation**: Use the sticky navigation bar with icons for quick access to sections
   - 🌙 **Dark Mode**: Toggle the moon icon in navigation to switch between light and dark themes
   - 📚 **Table of Contents**: Click links with icons to smoothly scroll to sections
   - 📖 **Content Sections**: Read detailed explanations with interactive images and diagrams
   - ⬆️ **Back to Top**: Click the fixed button in top-right corner to return to the top
   - 📊 **Scroll Progress**: Watch the progress bar at the top as you scroll
   - 📚 **References**: View sources in the final section with hover effects
3. 🎨 **Interactive Features**:
   - 🖱️ Hover over images for scale and shadow effects
   - ⚡ Use smooth scrolling navigation for seamless browsing
   - ✨ Experience fade-in animations as you scroll through content
   - 📱 Enjoy responsive design on all device sizes
   - 👆 Use touch gestures on mobile devices

## 📁 File Structure
```
📦 Computer Monitors Website
├── 📄 index.html          # Main page with hero section, modern navigation, content sections, and enhanced JavaScript
├── 🎨 style.css           # Modern stylesheet with animations, dark mode, responsive design, and interactive elements
├── 📜 jquery.scrollTo.min.js  # jQuery plugin for smooth scrolling functionality
├── 📁 img/                # Comprehensive image collection for diagrams, masks, matrices, and connectors
│   ├── 🖼️ budowa-crt.png
│   ├── 🖼️ budowa-lcd.png
│   ├── 🖼️ maska1.png
│   ├── 🖼️ maska2.png
│   ├── 🖼️ maska3.png
│   ├── 🖼️ mat1.png
│   ├── 🖼️ mat2.png
│   ├── 🖼️ mat3.png
│   ├── 🔌 zlacze1.png
│   ├── 🔌 zlacze1a.png
│   ├── 🔌 zlacze2.png
│   ├── 🔌 zlacze2a.png
│   ├── 🔌 zlacze3.png
│   ├── 🔌 zlacze3a.png
│   ├── 🔌 zlacze4.png
│   ├── 🔌 zlacze4a.png
│   ├── 🖼️ tlo.png
│   └── ⬆️ up.png
├── 📄 README.md           # This file, providing updated project documentation
└── 📄 slajdy.html         # Additional slides content (if applicable)
```

## ⚙️ Technical Features
- 🎨 **Modern CSS**: Flexbox layouts, CSS Grid, custom properties, and advanced animations
- ⚡ **JavaScript Enhancements**: Intersection Observer API, localStorage, touch events, and performance optimizations
- 📱 **Responsive Design**: Mobile-first approach with breakpoints at 900px, 700px, and 480px
- ♿ **Accessibility**: Semantic HTML, keyboard navigation, and screen reader support
- ⚡ **Performance**: Lazy loading images, optimized animations, and efficient event handling
- 🌐 **Cross-browser Compatibility**: Works on all modern browsers with graceful degradation

## 📝 Notes
- 🌍 The site is in English (`lang="en"`) for broad accessibility
- 💾 Dark mode preference is saved in localStorage for returning users
- 🌐 All external resources (fonts, icons, images) are loaded from CDNs for reliability
- 🖼️ Images in `img/` must match referenced filenames to avoid broken links
- 🖥️ The site is static; no backend is required
- 🎨 Modern CSS features are used with fallbacks for older browsers
- 👆 Touch support includes swipe detection for future mobile enhancements
- 🖨️ Print styles are included for document printing

## 🤝 Contributing
Contributions are welcome! To contribute:
1. 🍴 Fork the repository
2. 🌿 Create a new branch (`git checkout -b feature-branch`)
3. 💾 Make changes and commit (`git commit -m "Add feature"`)
4. 📤 Push to the branch (`git push origin feature-branch`)
5. 🔄 Open a pull request

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact
Made by Adrian Lesniak. For questions or feedback, open an issue on GitHub or email 📧 impersoftware@gmail.com.

---

<div align="center">

### 🎯 **Quick Start**
```bash
git clone <repository-url>
cd computer-monitors-website
python -m http.server 8000
```

### 🌟 **Key Features**
- 🌙 Dark Mode Toggle
- 📱 Responsive Design  
- ⚡ Smooth Animations
- 🎨 Modern UI/UX
- 🔍 SEO Optimized

### 📊 **Technologies Used**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

</div>
