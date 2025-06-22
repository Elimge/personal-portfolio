# Miguel Canedo - Personal Portfolio Website v2.5

This project is a complete refactor of my personal portfolio, evolved into a modern, dynamic, and visually immersive Single-Page Application (SPA). It is built from the ground up with a mobile-first approach and advanced CSS techniques to showcase my skills as a web developer focused on clean code and premium user experience.

## Description

This portfolio serves as a comprehensive digital resume, providing a seamless, one-page experience that includes:

*   A **fixed, "floating" header** with a frosted glass effect (`backdrop-filter`) that stays visible during navigation.
*   An **immersive hero section** that fills the viewport, creating a strong first impression.
*   A **"Projects" section** showcasing three key projects in a responsive grid layout.
*   A clean and functional **contact form**.
*   **Smooth, animated scrolling** between sections for fluid navigation.
*   **Advanced hover effects** and micro-interactions on all interactive elements.
*   A **"JavaScript-Ready" architecture** with CSS classes prepared for future scroll-triggered animations.

## Features implemented

*   **Single-Page Architecture (SPA):** All content is consolidated into a single `index.html` file for a faster, app-like user experience.
*   **Semantic HTML5 Structure:** Employs modern HTML5 tags (`<header>`, `<main>`, `<section>`, `<article>`) for a well-organized, accessible, and SEO-friendly document.
*   **Advanced CSS & Modern Practices:**
    *   **Flexbox for 1D Layouts:** Used for aligning components like the site header.
    *   **CSS Grid for 2D Layouts:** Implemented to create the robust and responsive grid for the project showcase.
    *   **Responsive Design with Media Queries:** Employs breakpoints at `1024px`, `768px`, and `480px` to ensure a flawless experience on all devices.
    *   **CSS Variables:** The entire theme is managed by custom properties in `:root` for consistency and easy maintenance.
    *   **"Sticky Footer" Implementation:** Uses Flexbox on the `body` to ensure the footer always stays at the bottom of the viewport, even on short content screens.
*   **Enhanced User Experience (UX):**
    *   **Fixed Header with `backdrop-filter`:** Creates a modern, translucent effect.
    *   **Advanced Hover Effects:** Smooth, CSS-based transitions are applied to all interactive elements, including a card hover that affects child elements.
*   **JavaScript-Ready:** The CSS includes prepared classes (`.reveal-on-scroll`) to easily implement scroll-triggered animations in the future.

## Technologies Used

*   HTML5
*   CSS3 (External Stylesheet)

## How to View

1.  Download or clone the project files.
2.  Ensure the `assets/` folder (containing `css/` and `img/`) is present in the same directory as `index.html`.
3.  Open `index.html` in any modern web browser (Chrome, Firefox, Edge, etc.).
4.  Scroll or use the navigation links to move smoothly between sections.
5.  Use the browser's developer tools to toggle between different device sizes to see the responsive design in action.

## File Structure
```bash 
.
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── img/
│       ├── logo.png
│       ├── profile-image.jpg
│       ├── profile-image.webp
│       ├── project-finance.jpeg
│       ├── project-inventory.jpg
│       └── project-vapor.jpg
└── README.md
```
## Author

*   **Miguel Canedo**
    *   E-mail: macv_09@hotmail.com
    *   GitHub: [@Elimge](https://github.com/Elimge) 

*  **Photo Credit**
    *   Images sourced from royalty-free stock photo websites.
    *   Profile picture by **Nelson Salcedo**. ([@JuiceHitCoder](https://github.com/JuiceHitCoder))