# Web-development-part-2
JOHN DEERE SOUTH AFRICA WEBSITE - PART 2

Updated version includes:
- Automatic About Us image slideshow
- About Us hover effect for customer reading/content cards
- Cards lift slightly, highlight with John Deere green/yellow, and show a small 'Hover to explore' prompt
- Responsive/mobile-friendly behavior
- Reduced-motion accessibility support

Keep index.html, style.css and the images folder together after extracting the ZIP.
CSS
# John Deere South Africa Website – Part 2

## 1. Project Overview

This project is a redesigned **John Deere South Africa** website created for the Web Development Part 2 assignment. The website focuses on a clean, modern and responsive user experience while keeping the John Deere-inspired green, yellow, white and black colour palette.

The website is designed to present agricultural equipment, construction equipment, precision agriculture technology, company information, news and events, support information and South African contact/dealer details.

## 2. Purpose of the Website

The purpose of the website is to provide customers with clear and accessible information about John Deere products and solutions in South Africa. The layout uses clear navigation, readable typography, product images and call-to-action links to help visitors find information quickly.

## 3. Technologies Used

- HTML5 for the website structure and content.
- CSS3 using an external `style.css` stylesheet.
- JavaScript for the automatic About Us image slideshow.
- Responsive CSS media queries for desktop, tablet and mobile screen sizes.
- CSS hover and focus effects for interactive elements.
- JPG image assets stored in the `images` folder.

## 4. Website Sections

The main `index.html` page contains:

1. **Home** – hero section, introductory message and featured products.
2. **Featured Products** – tractors, combines, construction and Precision Ag.
3. **Latest News** – product news, smart farming and sustainable agriculture.
4. **Stay Updated** – newsletter subscription area.
5. **About Us** – company information, mission, vision, values and sustainability.
6. **Products & Solutions** – agricultural, construction, forestry and Precision Ag solutions.
7. **Support** – customer support and enquiry information.
8. **Contact & Dealer Locator** – South African contact and dealer information.
9. **News & Events** – additional news and event content.
10. **Footer** – quick links, contact information and supporting information.

## 5. Design Choices

### Colour Palette

The website uses:

- **Green** – represents John Deere branding and agriculture.
- **Yellow** – used for highlights, buttons and interactive accents.
- **White** – keeps the interface clean and readable.
- **Black/Dark colours** – used for contrast and footer/navigation areas.

### Typography

The stylesheet uses:

- **Poppins** for headings and important titles.
- **Open Sans** for body text and supporting information.

### Layout

The website uses structured sections, tables from the supplied HTML structure, flexible CSS rules and responsive media queries. The CSS also includes spacing, borders, shadows, typography and interactive states.

## 6. Responsive Design

The website includes breakpoints for different screen sizes. The CSS contains media queries for:

- Desktop screens.
- Tablet-sized screens.
- Mobile screens.
- Smaller mobile screens.

Relative sizing is used where appropriate so that content can adapt to different viewport widths.

## 7. Images

The website uses **9 generated/cropped image assets**, which is below the maximum of 50 images requested for the project.

The images are used for:

- Hero tractor banner.
- Tractors.
- Combines.
- Construction equipment.
- Precision Agriculture.
- Product/news content.
- Smart farming.
- Sustainability.
- About John Deere.

All image files are stored in the `images` folder and are referenced using relative paths from `index.html`.

## 8. About Us Image Slideshow

The About Us section includes an interactive image slideshow.

Features include:

- Four About Us images.
- Automatic transition approximately every 4.5 seconds.
- Previous and Next buttons.
- Clickable slide indicator dots.
- Smooth transition animation.
- Responsive sizing for smaller screens.
- `prefers-reduced-motion` support for users who prefer less animation.

## 9. About Us Hover Effect

A hover effect has been added to the About Us information cards.

When the customer moves the mouse over the About Us content:

- The card lifts slightly.
- A border highlight appears.
- The background becomes lightly highlighted.
- The heading changes to a stronger green.
- A small “Hover to explore” message appears.
- A shadow gives the card more visual depth.

This effect provides visual feedback and makes the About Us information feel more interactive.

## 10. Accessibility

The website includes several accessibility considerations:

- Descriptive `alt` text is provided for website images.
- Buttons include accessible labels where appropriate.
- Keyboard focus states are included for interactive slideshow controls.
- The slideshow supports `prefers-reduced-motion`.
- Text and background colours are selected to provide clear visual contrast.
- Semantic HTML elements such as `header`, `main`, `section` and `footer` are used.

## 11. File Structure

```text
John_Deere_South_Africa_Website
│
├── index.html
├── style.css
├── README.md
├── README.txt
│
└── images/
    ├── hero-tractor.jpg
    ├── tractor.jpg
    ├── combine.jpg
    ├── construction.jpg
    ├── precision-ag.jpg
    ├── news-products.jpg
    ├── news-smart-farming.jpg
    ├── news-sustainability.jpg
    └── about-john-deere.jpg
```

## 12. How to Run the Website

1. Download the ZIP file.
2. Extract the ZIP file using **Extract All**.
3. Open the extracted website folder.
4. Make sure `index.html`, `style.css` and the `images` folder are in the correct locations.
5. Double-click `index.html` to open the website in a browser.
6. Test the navigation links, slideshow, hover effects and responsive layout.

**Do not open the HTML file from inside the ZIP archive.** Extract the complete folder first so that the CSS and images can load correctly.

## 13. Part 2 Changelog

### Update 1 – External CSS
- Added/used `style.css` as the external stylesheet.
- Linked the stylesheet to `index.html`.
- Added common typography, spacing, layout and visual styling.

### Update 2 – Desktop Styling
- Applied the John Deere-inspired green, yellow, white and black colour palette.
- Added heading and body typography.
- Added borders, shadows, spacing and interactive states.
- Styled product and news sections.

### Update 3 – Responsive Design
- Added media queries for tablet and mobile screen sizes.
- Adjusted image sizes and content spacing for smaller screens.
- Added mobile-friendly styling.

### Update 4 – Website Images
- Added 9 image assets to improve the visual presentation of the website.
- Added descriptive alternative text to images.
- Kept the total image count below 50.

### Update 5 – About Us Slideshow
- Added four images to the About Us slideshow.
- Added automatic image transitions.
- Added Previous/Next controls.
- Added clickable slide indicators.
- Added responsive and reduced-motion support.

### Update 6 – About Us Hover Interaction
- Added hover styling to About Us information cards.
- Added visual highlighting, elevation and colour changes.
- Added a small “Hover to explore” interaction message.
- Added mobile behaviour so the hover effect does not interfere with small-screen use.

## 14. Testing

The website should be tested in a modern browser such as Chrome, Edge or Firefox.

Testing should include:

- Desktop screen size.
- Tablet screen size.
- Mobile screen size.
- Navigation links.
- Product and news links.
- Image loading.
- About Us slideshow.
- Previous/Next slideshow controls.
- Slideshow indicator buttons.
- About Us hover effect.
- Keyboard focus on interactive controls.
- Different viewport widths using browser Developer Tools.

## 15. References

- MDN Web Docs. (2026). *CSS: Cascading Style Sheets*. Mozilla Developer Network.  
  https://developer.mozilla.org/en-US/docs/Web/CSS

- MDN Web Docs. (2026). *Responsive web design*. Mozilla Developer Network.  
  https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design

- MDN Web Docs. (2026). *Media query fundamentals*. Mozilla Developer Network.  
  https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries

- MDN Web Docs. (2026). *CSS media queries*. Mozilla Developer Network.  
  https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries

- MDN Web Docs. (2026). *CSS layout*. Mozilla Developer Network.  
  https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout

- MDN Web Docs. (2026). *Guidelines for writing CSS code examples*. Mozilla Developer Network.  
  https://developer.mozilla.org/en-US/docs/MDN/Writing_guidelines/Code_style_guide/CSS

- World Wide Web Consortium (W3C). (2025). *Web Content Accessibility Guidelines (WCAG) 2*. W3C Web Accessibility Initiative.  
  https://www.w3.org/WAI/standards-guidelines/wcag/

## 16. Conclusion

The updated website applies CSS styling, responsive design, imagery and interactive features to create a more engaging John Deere South Africa website. The About Us section has been enhanced with both an automatic slideshow and hover interaction, while the overall website remains structured around the requirements of the Part 2 design and responsive styling work.
