# Full Stack Course Projects

> A collection of front-end homework projects created during a full-stack development course.

This repository contains several practice projects built with **HTML**, **CSS**, **JavaScript**, and basic front-end tooling. The main focus is learning semantic markup, page structure, navigation, forms, CSS selectors, styling, layout techniques, organizing multi-page websites, and practicing JavaScript fundamentals.

## Project Overview

The repository works as a course catalogue. Earlier homework assignments are still stored in local folders here, while newer assignments can live in separate repositories and be linked from the root `index.html`.

| # | Project | Status | Location | Description |
| --- | --- | --- | --- | --- |
| 1️⃣ | `homework-01` | ✅ Local | Folder | A basic HTML page about Ukraine's Eurovision 2026 representative, including text, an image, lists, preformatted content, and an external video link. |
| 2️⃣ | `homework-02` | ✅ Local | Folder | A multi-page HTML structure with pages for articles, catalog, gallery, contacts, navigation, and registration. |
| 3️⃣ | `homework-03` | ✅ Local | Folder | A styled multi-page website for **Canby Glass Design Studio** with custom layouts, navigation, images, icons, forms, and visual design. |
| 4️⃣ | `homework-04` | ✅ Local | Folder | A CSS selector practice page that demonstrates selector types, specificity, nesting, sibling selectors, attributes, IDs, classes, and pseudo-classes. |
| 6️⃣ | `homework-06` | ✅ Local | Folder | A layout practice project with table examples, structured pages, custom icons, and a Mondrian-style visual composition. |
| 7️⃣ | `homework-07` | ✅ Local | Folder | A multi-page CSS box model project covering block and inline elements, normalize, reset, display, box-sizing, float, overflow, positioning, and practical block construction. |
| 8️⃣ | `html-homework-08` | ✅ Local | Folder | A responsive float layout demo with plant cards, five block-positioning variants, navigation anchors, expandable explanations, and clearfix practice. |
| 9️⃣ | `html-homework-09-simple-site` | ✅ Local | Folder | A one-page Simple Site landing page with header navigation, hero content, about section, statistics strip, process media preview, and footer. |
| 🔟 | `homework-10-responsive-simple-site` | 🔗 Linked | Repository | A responsive continuation of Simple Site focused on media queries, flexible spacing, adaptive layout behavior, and viewport testing. |
| 1️⃣1️⃣ | `css-homework-11-simple-site-refactoring` | 🔗 Linked | Repository | A refactored Simple Site project with modular SCSS, Gulp build automation, minified stylesheet output, and responsive layout enhancements. |
| 1️⃣3️⃣ | `homework-13-svg-css-animation` | 🔗 Linked | Repository | Interactive SVG gallery with styled shapes and CSS animations; includes accessibility considerations and responsive layout. |
| 1️⃣4️⃣ | `homework-14-bootstrap` | 🔗 Linked | Repository | A responsive Bootstrap landing page for CANBY Glass Design Studio with carousel sections, dropdown/offcanvas navigation, product modals, accordion content, and a consultation form. |
| 1️⃣5️⃣ | `homework-15-tailwind` | 🔗 Linked | Repository | A responsive Vite and Tailwind CSS football prediction dashboard for the FIFA World Cup 2026 with match forecasts, schedule filters, player ratings, rules, modals, and theme switching. |
| 1️⃣7️⃣ | `homework-17-final-scss` | 🔗 Linked | Repository | A final responsive SCSS web project with component sections, modular partials, WebP images, hover/focus states, and an animated mobile burger menu. |
| JS 1️⃣ | `js-homework-01-tests` | 🔗 Linked | Repository | A JavaScript basics assignment with variables, data types, number formatting, BigInt practice, Vitest checks, and a browser demo that mirrors console output on the page. |

## Repository Features

- **Semantic HTML structure** for clear and accessible page markup.
- **Separate project organization** for homework assignments.
- **Reusable project organization** with assets, pages, styles, and documentation.
- **Custom CSS styling** for layouts, navigation, cards, forms, tables, float compositions, landing pages, responsive states, and visual demos.
- **Practice-focused pages** that demonstrate specific HTML and CSS concepts.
- **Responsive homework pages** that adapt layout examples for tablets and mobile screens.
- **Dynamic single-page homework apps** with JavaScript-rendered sections, filters, modals, and persisted UI state.
- **GitHub Pages support** through direct links to local homework folders and separate repositories.
- **Markdown documentation** for the repository and selected homework projects.

## Technologies Used

- HTML5
- CSS3
- JavaScript basics
- SVG assets
- Bootstrap 5
- SCSS
- Gulp
- Tailwind CSS 4
- Vite
- WebP images
- WOFF2 fonts
- Google Fonts
- ESLint

## Project Structure

```text
full-stack-course/
├── homework-01/
├── homework-02/
├── homework-03/
│   ├── assets/
│   │   ├── css/
│   │   └── img/
│   ├── pages/
│   └── index.html
├── homework-04/
├── homework-06/
├── homework-07/
├── html-homework-08/
│   ├── assets/
│   │   ├── css/
│   │   ├── fonts/
│   │   └── img/
│   ├── index.html
│   └── README.md
├── html-homework-09-simple-site/
│   ├── assets/
│   │   ├── css/
│   │   └── img/
│   ├── index.html
│   └── README.md
├── index.html
├── package.json
└── README.md
```

## How To Run

No build step is required for the HTML/CSS pages.

1. Open the project folder.
2. Choose one of the homework directories or use the root catalogue page.
3. Open the required `index.html` file in a browser.

For example:

```text
html-homework-09-simple-site/index.html
```

Folder-based GitHub Pages links in this catalogue follow this pattern:

```text
https://andrii-dolzhenko.github.io/full-stack-hero/html-homework-09-simple-site/
```

Separate homework repositories have their own GitHub Pages links, for example:

```text
https://andrii-dolzhenko.github.io/homework-10-responsive-simple-site/
```

```text
https://andrii-dolzhenko.github.io/homework-15-tailwind/
```

```text
https://andrii-dolzhenko.github.io/homework-17-final-scss/
```

```text
https://andrii-dolzhenko.github.io/js-homework-01-tests/
```

## Learning Goals

This project helps practice:

- creating valid HTML page structures;
- linking pages together;
- building forms;
- styling layouts with CSS;
- working with images and SVG files;
- understanding CSS specificity;
- positioning blocks with float and margin;
- clearing floated layouts with clearfix;
- building responsive one-page landing pages;
- building interactive Bootstrap-based landing pages;
- aligning content with Flexbox;
- adapting layouts with media queries;
- testing responsive pages across mobile, tablet, laptop, and desktop widths;
- building utility-first responsive interfaces with Tailwind CSS;
- creating JavaScript variables with primitive and structured values;
- formatting numbers and working with BigInt values;
- running JavaScript homework tests with Vitest;
- rendering dynamic single-page app sections from local JavaScript data;
- managing UI state, filters, modals, theme toggles, and localStorage;
- organizing SCSS with partial files, variables, mixins, and component sections;
- building animated mobile navigation and interactive hover/focus states;
- organizing project files;
- preparing a repository for front-end coursework.

## Author

**Andrii Dolzhenko**  
Full-stack development course student
