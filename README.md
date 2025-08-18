# Slozhno Sosredotochitsya

This is an adaptive, theme-switchable landing page built as part of a front-end development learning project. The design focuses on accessibility, responsive layouts, and interactive theme control.

## Features

- **Responsive design** – fully adapts to mobile, tablet, and desktop screen sizes.

- **Theme switching** – light, dark, and automatic modes with smooth transitions.

- **Pixel-perfect layout** – developed according to provided Figma mockups.

- **Semantic HTML5** – accessible and SEO-friendly markup.

- **CSS Grid & Flexbox** – modern layout techniques for flexible and maintainable structure.

- **Custom properties (CSS variables)** – centralized theme control and easy styling updates.

## Technologies Used

- HTML5 – semantic structure and accessible markup.

- CSS3:

     - custom properties for theme management.

     - flexbox and Grid for adaptive layouts.

     - media queries for responsive breakpoints.

     - CSS transitions for smooth visual effects.

- JavaScript (Vanilla) – theme switching logic with localStorage support.

- BEM methodology – Block-Element-Modifier naming convention for scalable and maintainable CSS.

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
