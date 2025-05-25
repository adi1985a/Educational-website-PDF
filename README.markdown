# 🖥️💡 DisplayTech Guide: Computer Monitors Uncovered 📜
_An HTML-based educational website providing a technical overview of CRT, LCD, and future display technologies, connectors, and their principles, enhanced with jQuery smooth scrolling and custom styling._

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![jQuery](https://img.shields.io/badge/jQuery-2.2.4-0769AD.svg?logo=jquery)](https://jquery.com/)
[![Google Fonts](https://img.shields.io/badge/Google%20Fonts-Open%20Sans-4285F4.svg?logo=googlefonts)](https://fonts.google.com/specimen/Open+Sans)

## 📋 Table of Contents
1.  [Overview](#-overview)
2.  [Key Features](#-key-features)
3.  [Screenshots (Conceptual)](#-screenshots-conceptual)
4.  [Technical Stack & Requirements](#-technical-stack--requirements)
5.  [Local Setup & Viewing](#️-local-setup--viewing)
6.  [Website Usage & Navigation](#️-website-usage--navigation)
7.  [File Structure](#-file-structure)
8.  [Important Notes & Considerations](#-important-notes--considerations)
9.  [Contributing](#-contributing)
10. [License](#-license)
11. [Contact](#-contact)

## 📄 Overview

**DisplayTech Guide: Computer Monitors Uncovered** is a static educational website built with HTML, CSS, and JavaScript (primarily jQuery for enhancements). It offers a detailed technical overview of various computer monitor technologies, including legacy CRT (Cathode Ray Tube) and modern LCD (Liquid Crystal Display) monitors, common display connectors (VGA, DVI, HDMI, DisplayPort), and a look into future display technologies like PDP (Plasma Display Panel) and OLED (Organic Light Emitting Diode). The site features an organized table of contents with **jQuery-powered smooth scrolling** for easy navigation, illustrative images, and a list of references. Styling is managed by a custom `style.css` and typography is enhanced with the "Open Sans" Google Font.

## ✨ Key Features

*   🧭 **Smooth Scrolling Table of Contents**:
    *   A well-structured navigation menu (Table of Contents) at the beginning of the page.
    *   Links to various sections: CRT Technology, LCD Technology, Display Connectors (VGA, DVI, HDMI, DisplayPort), and Future Display Technologies (PDP, OLED).
    *   Utilizes **jQuery** and the **jQuery ScrollTo plugin** (`jquery.scrollTo.min.js`) for smooth animated scrolling to the selected section.
*   📜 **Detailed Technology Sections**:
    *   **CRT Monitors**: Covers construction, operating principles, different mask types (e.g., shadow mask, aperture grille), advantages, disadvantages, and key parameters.
    *   **LCD Monitors**: Details construction, operating principles, matrix types (e.g., TN, IPS, VA), backlighting, pros, cons, and important parameters.
*   🔌 **Display Connector Guide**:
    *   Explains common video connectors: DSUB (VGA), DVI (Digital Visual Interface), HDMI (High-Definition Multimedia Interface), and DisplayPort.
    *   Includes images (e.g., `zlacze1.png`) to visually identify each connector type.
*   🔮 **Future Display Technologies**:
    *   Provides an overview of Plasma Display Panels (PDP) and Organic Light Emitting Diodes (OLED) as emerging or advanced display solutions.
*   ⬆️ **Scroll-to-Top Button**:
    *   An animated "scrollup" button (or similar) appears on the page after the user scrolls down a certain amount (e.g., 300px).
    *   Clicking this button smoothly scrolls the page back to the top, enhancing user experience on long pages.
*   🎨 **Custom Styling & Typography**:
    *   Styled with a dedicated stylesheet (`style.css`) for layout, presentation, and visual clarity.
    *   Utilizes the "Open Sans" Google Font for readable and modern typography.
    *   Incorporates images (located in an `img/` folder) to illustrate technical concepts, monitor construction, and connector types.
*   🔍 **SEO Considerations**: Includes essential meta tags for viewport configuration and a site description with relevant keywords to improve search engine visibility.
*   🇬🇧 **English Language Content**: The website content is presented in English (`lang="en"`), aiming for broad accessibility.

## 🖼️ Screenshots (Conceptual)

**Coming soon!**

_This section would ideally show screenshots of: the website's main page with the table of contents, examples of the detailed sections on CRT/LCD monitors with images, the display connector guide, and the scroll-to-top button in action._

## 🛠️ Technical Stack & Requirements

### Core Technologies:
*   **Structure**: HTML5
*   **Styling**: CSS3 (`style.css`)
*   **Interactivity & Enhancements**: JavaScript, jQuery (v2.2.4 via CDN), jQuery ScrollTo plugin (`jquery.scrollTo.min.js` - local or CDN)
*   **Fonts**: Google Fonts (Open Sans)

### Requirements:
*   **Web Browser**: Any modern web browser (e.g., Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).
*   **Internet Connection**: **Required** to load external resources:
    *   jQuery CDN: `https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js`
    *   Google Fonts (Open Sans)
    *   (If `jquery.scrollTo.min.js` is also CDN-hosted, that too).
*   **Local Assets**:
    *   `style.css` (stylesheet)
    *   `jquery.scrollTo.min.js` (jQuery plugin, if hosted locally)
    *   `img/` directory containing all referenced images (e.g., `budowa-crt.png`, `zlacze1.png`, `budowa-lcd.png`, `mat1.png`, etc.)

## ⚙️ Local Setup & Viewing

1.  **Clone or Download the Repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```
    *(Replace `<repository-url>` and `<repository-directory>` with your specific details, or simply download the files into a local folder).*

2.  **Ensure Asset Placement**:
    *   Verify that `style.css` is in the root directory (or its path correctly linked in `index.html`).
    *   Place `jquery.scrollTo.min.js` in the root directory (or update its script tag path in `index.html` if it's in a `js/` subfolder or loaded from a CDN).
    *   Confirm that the `img/` subfolder exists and contains all the necessary images referenced in the HTML (e.g., `budowa-crt.png`, `zlacze1.png`).

3.  **Open in Browser or Host Locally**:
    *   **Directly in Browser**: You can usually open `index.html` directly in your web browser (File > Open File).
    *   **Using a Simple HTTP Server (Recommended for consistent behavior, especially if local JS files interact)**:
        If you have Python installed, navigate to the project's root directory in your terminal and run:
        ```bash
        python -m http.server 8000
        ```
        Then, open your web browser and go to `http://localhost:8000`.
    *   Alternatively, use any other local web server solution (e.g., Live Server extension in VS Code).

## 💡 Website Usage & Navigation

1.  Open `index.html` in your web browser (ensure an internet connection for jQuery and Google Fonts if loaded from CDNs).
2.  **Interface**:
    *   **Table of Contents**: Located at the top of the page, with clickable links to different sections (e.g., "CRT Monitor Construction," "LCD Matrix Types," "HDMI Connectors").
    *   **Main Content Area**: Scroll down to read detailed explanations and view images related to CRT monitors, LCD monitors, various display connectors, and future display technologies.
    *   **Scroll-to-Top Button**: As you scroll down the page (more than 300px), an animated "scrollup" button (or similar) will appear, usually in a fixed position (e.g., bottom-right corner).
    *   **References Section**: At the end of the content, view a list of sources used for the information.
3.  **Actions**:
    *   **Smooth Scrolling**: Click on links within the Table of Contents to smoothly scroll to the corresponding section on the page.
    *   **Return to Top**: Click the "scrollup" button (when visible) to be smoothly scrolled back to the top of the page.
    *   Read through the educational content and view the illustrative images.

## 🗂️ File Structure

The project is expected to have the following basic file structure:

*   `index.html`: The main HTML file containing the table of contents, all content sections, and the footer.
*   `style.css`: The primary CSS file for styling the layout, typography, and visual elements.
*   `jquery.scrollTo.min.js`: The jQuery plugin file enabling smooth scrolling functionality (if hosted locally).
*   `img/` (subfolder): Contains all images used in the website, such as diagrams of monitor construction (`budowa-lcd.png`, `mat1.png`), connector images (`zlacze1.png`), etc.
*   `README.md`: This documentation file.

## 📝 Important Notes & Considerations

*   **English Language**: The website content is in English (`lang="en"`), designed for a broad audience.
*   **jQuery & Plugin Dependencies**: The smooth scrolling functionality and the scroll-to-top button depend on jQuery and the `jquery.scrollTo.min.js` plugin loading correctly. Ensure internet access if these are loaded from CDNs, or correct local paths if hosted locally.
*   **Image Paths**: All images referenced from the `img/` folder must exist and have their filenames and paths correctly specified in the HTML to avoid broken image links.
*   **Static Nature**: This is a static HTML, CSS, and JavaScript (client-side) website. No backend processing is involved.
*   **`style.css` Implementation**: The overall visual appeal, layout integrity, and responsiveness are heavily dependent on the CSS rules defined in `style.css`.
*   **References**: The "References" section includes textbook and online sources. It's good practice to ensure these links/citations are accurate and up-to-date.
*   **"scrollup" Button Behavior**: The appearance and animation of the scroll-to-top button are controlled by JavaScript (likely interacting with jQuery) based on scroll position.

## 🤝 Contributing

Contributions to the **DisplayTech Guide: Computer Monitors Uncovered** website are welcome! If you have ideas for:

*   Adding information on newer display technologies or connectors.
*   Improving existing explanations or diagrams.
*   Enhancing the CSS styling, layout, or responsiveness.
*   Optimizing JavaScript performance or updating jQuery/plugins.
*   Correcting any inaccuracies or broken links.

1.  Fork the repository.
2.  Create a new branch for your feature or content update (`git checkout -b feature/AddOLEDDetails` or `content/UpdateHDMISection`).
3.  Make your changes (HTML, CSS, JS, images, text).
4.  Commit your changes (`git commit -m 'Content: Add detailed explanation of OLED technology'`).
5.  Push to the branch (`git push origin content/UpdateHDMISection`).
6.  Open a Pull Request.

## 📃 License

This project is licensed under the **MIT License**.
(If you have a `LICENSE` file in your repository, refer to it: `See the LICENSE file for details.`)

## 📧 Contact

Project developed by **Adrian Lesniak**.
For questions or feedback, please open an issue on the GitHub repository.

---
✨ _Demystifying display technologies, from CRTs to OLEDs!_
