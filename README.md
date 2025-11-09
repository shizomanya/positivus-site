<div align="center">
<h1>Positivus — Creative Agency Website</h1>

<p>
  A modern and fully responsive multi-section landing page for a <b>digital marketing agency</b> called <b>Positivus</b>.<br />  
  The project emphasizes a clean structure, scalable SCSS architecture and a strong visual identity built with <b>HTML5</b> and <b>SCSS (CSS3)</b>.
</p>

<p>
<a href="#about">About</a> •
<a href="#features">Features</a> •
<a href="#technologies">Technologies</a> •
<a href="#scss-architecture">SCSS Architecture</a> •
<a href="#installation">Installation</a> •
<a href="#preview">Preview</a>
</p>
</div>

---

<details><summary style="font-size:larger;"><b>Table of Contents</b></summary>

- [About](#about)
- [Features](#features)
- [Technologies](#technologies)
- [SCSS Architecture](#scss-architecture)
- [Installation](#installation)
- [Preview](#preview)

</details>

---

## About

**[Positivus](https://shizomanya.github.io/positivus-site)** is a responsive landing page concept for a creative digital marketing agency.  
The goal of this project is to deliver a visually appealing, structured, and accessible web layout that effectively presents brand identity, services, and client trust.

The design focuses on:

- Clean, scalable SCSS architecture with variables and mixins
- Consistent and modern visual hierarchy
- Fully responsive sections for all screen sizes
- Semantic HTML structure and reusable components

This layout serves as a solid foundation for future expansion — including JavaScript interactivity, CMS integration, or motion effects.

---

## Features

- **Fully responsive design** for desktop, tablet, and mobile
- **SCSS preprocessor** with modular structure and variables
- **CSS Grid & Flexbox** for adaptive and balanced layouts
- **Reusable UI components** (buttons, cards, sections)
- **Optimized typography and spacing system** using relative units and clamp()
- **Semantic HTML5 markup** for accessibility and SEO
- **Easily extendable structure** for JS animations or dynamic content

---

## Technologies

The project was built using:

- **HTML5** — semantic and accessible structure
- **SCSS (CSS3)** — modular, maintainable styles with variables and mixins
- **Flexbox & Grid** — modern responsive layout techniques
- **Google Fonts** — _Space Grotesk_
- **No frameworks** — fully handcrafted design
- _(Ready for integration with JavaScript, GSAP, or CMS platforms)_

---

## SCSS Architecture

This project follows the **7-1 SCSS architecture pattern**, ensuring scalability and maintainability.

```
styles/
│
├── _variables.scss      # Global color palette, spacing, typography
├── _mixins.scss         # Reusable mixins (media queries, flex helpers)
├── _globals.scss        # Base styles (html, body, typography)
├── _normalize.scss      # CSS reset for browser consistency
├── _fonts.scss          # Font-face declarations
├── _utils.scss          # Utility classes and helper styles
├── _media.scss          # Breakpoints and responsive helpers
│
├── blocks/              # Component-based SCSS files (BEM naming)
│   ├── _header.scss
│   ├── _hero.scss
│   ├── _services.scss
│   ├── _reviews.scss
│   ├── _team.scss
│   ├── _footer.scss
│   └── …
│
├── styles.scss          # Main SCSS entry importing all partials
├── styles.css           # Compiled CSS file
└── styles.css.map       # Source map for debugging
```

**Benefits of this setup:**

- Centralized variable and color management
- Reusable and modular component structure
- Simplified scaling for new pages or sections
- Consistent and maintainable responsive design

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shizomanua/positivus-site.git
   cd positivus-site
   ```
2. Ensure all folders remain intact (images/, fonts/, styles/).
3. Compile SCSS to CSS (if not precompiled):

```
sass styles/styles.scss styles/styles.css
```

4. Open the project in your browser:
   - Double-click index.html, or
   - Use the Live Server extension in VS Code for a smoother experience.

---

## Preview

> [Positivus site (Demo)￼](https://shizomanya.github.io/positivus-site)

![Preview Screenshot](/images/preview.png)
