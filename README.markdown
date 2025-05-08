# Computer Monitors - Technical Overview

## Overview
Computer Monitors - Technical Overview is an HTML-based educational website detailing CRT and LCD monitor technologies, connectors (VGA, DVI, HDMI, DisplayPort), and future displays (PDP, OLED). It features a table of contents with jQuery smooth scrolling, images, and references. Styled with custom CSS and Google Fonts for clarity.

## Features
- **Table of Contents**: Organized navigation with links to sections on CRT, LCD, connectors, and future technologies, using jQuery smooth scrolling.
- **Detailed Sections**: Covers construction, operating principles, mask/matrix types, pros/cons, and parameters for CRT and LCD monitors.
- **Connector Guide**: Explains DSUB, DVI, HDMI, and DisplayPort with images.
- **Future Technologies**: Discusses PDP and OLED displays.
- **Scroll-to-Top**: Animated "scrollup" button appears after scrolling 300px.
- **SEO**: Meta tags for description and keywords to enhance visibility.
- **Styling**: Uses `style.css`, Google Fonts (`Open Sans`), and images for visual clarity.

## Requirements
- Web browser (e.g., Chrome, Firefox, Safari)
- Internet connection for external resources:
  - jQuery (`https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js`)
  - jQuery ScrollTo (`jquery.scrollTo.min.js`)
  - Google Fonts (`Open Sans`)
- Local assets:
  - `style.css`: Main stylesheet
  - `jquery.scrollTo.min.js`: jQuery plugin for scrolling
  - `img/`: Images (e.g., `budowa-crt.png`, `zlacze1.png`)

## Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. Ensure the required assets are in place:
   - `style.css`: Stylesheet for layout and design.
   - `jquery.scrollTo.min.js`: jQuery plugin for smooth scrolling.
   - `img/`: Images for diagrams and connectors.
3. Host the site on a web server (e.g., Apache, Nginx) or open `index.html` directly:
   ```bash
   python -m http.server 8000
   ```
4. Access the site at `http://localhost:8000`.

## Usage
1. Open the website in a browser to view the homepage.
2. **Interface**:
   - **Table of Contents**: Click links to scroll to sections like CRT Construction, LCD Matrix Types, or HDMI Connectors.
   - **Content**: Read detailed explanations with images for CRT, LCD, connectors, and future technologies.
   - **Scroll-to-Top**: Click the "scrollup" button (appears after scrolling) to return to the top.
   - **References**: View sources in the final section.
3. **Actions**:
   - Use table of contents links for smooth scrolling to specific sections.
   - Scroll down to trigger the animated "scrollup" button after 300px.

## File Structure
- `index.html`: Main page with table of contents, content sections, and footer.
- `style.css`: Custom styles for layout and design.
- `jquery.scrollTo.min.js`: jQuery plugin for smooth scrolling.
- `img/`: Images for diagrams (e.g., `budowa-lcd.png`, `mat1.png`).
- `README.md`: This file, providing project documentation.

## Notes
- The site is in English (`lang="en"`) for broad accessibility.
- jQuery and ScrollTo plugin dependencies must load correctly for smooth scrolling.
- Images in `img/` must match referenced filenames to avoid broken links.
- The site is static; no backend is required.
- Ensure `style.css` is properly configured for consistent styling.
- References include textbooks and online sources; verify URLs for accuracy.
- The "scrollup" button enhances UX but requires jQuery to function.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, open an issue on GitHub or email impersoftware@gmail.com.