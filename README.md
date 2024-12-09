# Coffee Shop Website

## Overview

The **Coffee Shop Website** is a fully responsive, interactive, and professional platform that reflects the modern identity of a coffee shop. Designed with a keen focus on user experience, the website showcases menu items, branding, and product offerings with elegant visuals, smooth animations, and intuitive layouts. SCSS was utilized for clean, modular styling, ensuring scalability and maintainability.

This project combines advanced web development principles and creative design to provide users with an engaging browsing experience across all devices.

---

## Features

### **Design and Functionality**

- **Pixel-Perfect Mockup Implementation**: The design precisely matches the mockups, ensuring a professional and polished appearance.
- **Responsive Design**: Layouts adjust dynamically across mobile, tablet, and desktop screens.
- **Interactive Animations**:
  - **Button Animation**: Buttons provide visual feedback when clicked.
  - **Spin Animation**: Rotating elements for enhanced product visuals.
  - **Flashing Animation**: Dynamic flashing effects on promotional banners.
- **Structured Codebase**: Organized file structure with SCSS partials for reusability and scalability.

### **SCSS-Driven Styling**

- Centralized variables for typography, colors, and spacings.
- Nesting and mixins for cleaner and DRY (Don't Repeat Yourself) code.
- Breakpoints for responsive design included directly within SCSS.

### **User Experience Enhancements**

- **Clean Typography**: Uses "Open Sans" for modern and legible text.
- **Professional Branding**: Custom logos, color palette, and imagery create a cohesive brand identity.
- **Clear Navigation**: Easily accessible menus and links for intuitive navigation.

---

## Key Learnings and Concepts

### **Web Development Skills**

1. **Responsive Design**: Learned to create layouts that adapt across various screen sizes using media queries and flexible units like `rem` and `percent`.
2. **SCSS**: Gained expertise in:
   - Using variables to manage design consistency.
   - Structuring SCSS with partials for reusable components.
   - Leveraging mixins and nesting for cleaner, modular code.
3. **CSS Animations**:
   - Mastered creating animations with `@keyframes`, transitions, and easing functions.
   - Integrated animations for user interactions (e.g., hover, click) to make the interface engaging.
4. **HTML5 Semantics**: Used proper semantic tags (`header`, `section`, `article`, etc.) for better accessibility and SEO.
5. **CSS Resets**: Incorporated a modern reset stylesheet to ensure consistency across browsers.

### **File and Project Organization**

- Created a clear and structured file hierarchy:
  - **assets/**: Houses images, logos, and other static assets.
  - **scss/**: Organized styles with partials and SCSS utilities for scalable design.
  - **pages/**: Separate HTML files for different pages (e.g., `menu.html`).

---

## Project Structure

```plaintext
COFFEE_SHOP/
├── assets/
│   ├── images/
│   │   ├── coffee-beans.svg
│   │   ├── coffee-circle.jpg
│   │   ├── coffee-cup.svg
│   │   ├── coffeebeans-hero.png
│   │   ├── coffeebeans.png
│   │   ├── coldbrew.png
│   │   ├── coldbrewbackground.png
│   │   ├── inhousebrew.png
│   │   ├── planting.svg
│   │   └── tiltedcan.png
│   ├── logos/
│   │   ├── coffee-beans-footer.svg
│   │   ├── coffee-beans-logo.svg
│   │   ├── Facebook-Icon.svg
│   │   ├── Instagram-Icon.svg
│   │   └── Yelp-Icon.svg
├── pages/
│   └── menu.html
├── scss/
│   ├── partials/
│   │   └── _global.scss
│   ├── landing.scss
│   ├── menu.scss
├── index.html
├── README.md
```


## Technologies Used

1. **HTML5** : For semantic and structured markup.
2. **CSS3** : For animations, transitions, and responsive layouts.
3. **SCSS** : For modular, DRY, and reusable styling.
4. **Modern CSS Reset** : Ensures consistent rendering across all browsers.
5. **Git & GitHub** : For version control and code sharing.

## Screenshots

### Landing Page

### Menu Page

### Mobile View

## Animations in Detail

1. **Button Animation** :

* Smoothly animates when clicked, providing instant user feedback.
* Implemented with CSS pseudo-classes and `@keyframes`.

1. **Spin Animation** :

* Rotates elements infinitely for dynamic visuals.
* Controlled by CSS properties like `transform` and `animation`.

1. **Flashing Animation** :

* Creates a flashing effect on the discount banner to attract attention.
* Utilizes `@keyframes` for background color transition 

## Future Enhancements

1. **JavaScript Features** :

* Add dynamic menu interactions like a shopping cart.
* Enable interactive forms and live search.

1. **Backend Integration** :

* Connect the website to a database to manage menu updates dynamically.

1. **Advanced Animations** :

* Enhance existing animations using JavaScript for smoother transitions.