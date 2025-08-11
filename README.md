# Slozhno Sosredotochitsya

This is an adaptive, theme-switchable landing page built as part of a front-end development learning project. The design focuses on accessibility, responsive layouts, and interactive theme control.

## Features

-**Responsive design** – Fully adapts to mobile, tablet, and desktop screen sizes.

-**Theme switching** – Light, dark, and automatic modes with smooth transitions.

-**Pixel-perfect layout** – Developed according to provided Figma mockups.

-**Semantic HTML5** – Accessible and SEO-friendly markup.

-**CSS Grid & Flexbox** – Modern layout techniques for flexible and maintainable structure.

-**Custom properties (CSS variables)** – Centralized theme control and easy styling updates.

## Technologies Used

-HTML5 – Semantic structure and accessible markup.

-CSS3:

     -Custom properties for theme management.

     -Flexbox and Grid for adaptive layouts.

     -Media queries for responsive breakpoints.

     -CSS transitions for smooth visual effects.

-JavaScript (Vanilla) – Theme switching logic with localStorage support.

-BEM methodology – Block-Element-Modifier naming convention for scalable and maintainable CSS.

## File Structure

```
.
├── index.html          # Main HTML file  
├── styles/  
│   ├── globals.css     # Global resets and shared styles  
│   ├── variables.css   # CSS variables for default (dark) theme  
│   ├── dark.css        # Dark theme styles  
│   ├── light.css       # Light theme styles  
│   └── style.css       # Layout and component styles  
├── script.js           # Theme switching logic  
└── images/             # Project images and icons
```

## How It Works

On load, the script checks localStorage for a saved theme.

The user can switch between themes using the theme menu buttons.

In auto mode, the page adapts to the system’s preferred color scheme (prefers-color-scheme).

Styles are organized by theme and by layout component using BEM conventions.
