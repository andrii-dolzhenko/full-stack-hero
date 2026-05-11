# HTML Homework 09 - Simple Site Landing Page

> A static one-page landing page built to practice semantic HTML structure, CSS spacing, Flexbox layout, responsive design, and reusable visual sections.

## Project Description

**HTML Homework 09** is a clean portfolio-style landing page named **Simple Site**.  
The project demonstrates how to build a structured web page with a header navigation, first-screen hero section, content blocks, project statistics, media preview, and footer.

The page is designed as a layout practice task with fixed design proportions, reusable CSS variables, and responsive rules for tablet and mobile screens.

## Page Sections

| Section | Purpose |
|---|---|
| `Header` | Contains the main navigation with anchor links to page sections. |
| `Hero` | Presents the main headline, short intro text, and call-to-action button. |
| `About` | Adds a centered informational block about the page owner or service. |
| `Stats` | Displays repeated project statistic items with icons and numbers. |
| `Process` | Shows a "How I Work" text block and a large video-preview image. |
| `Footer` | Contains the author name and copyright text. |

## Features

- **Single-page navigation** - menu links scroll to the main page sections.
- **Hero call-to-action** - a large first-screen block with a button linking to contacts.
- **Reusable section intro component** - consistent title and paragraph layout for content sections.
- **Project statistics strip** - repeated icon cards arranged with Flexbox.
- **Video preview block** - large responsive media area with a centered play button.
- **Responsive layout** - spacing, font sizes, navigation, stats, and media proportions adapt to smaller screens.
- **Accessible structure** - semantic sections, ARIA labels, hidden headings, and meaningful image descriptions.

## Implementation Highlights

### HTML

- Semantic elements are used for page structure: `header`, `nav`, `main`, `section`, and `footer`.
- Navigation uses anchor links for smooth movement between sections.
- Decorative icons use empty `alt` attributes, while meaningful media has descriptive `alt` text.
- The stats section includes a visually hidden heading for better document structure.

### CSS

```css
:root {
  --color-accent: #34547a;
  --container-max-width: 1150px;
  --font-size-hero: 48px;
}
```

Main CSS techniques:

- CSS custom properties for colors, typography, spacing, and component sizes;
- Flexbox for navigation, stats, and centered content patterns;
- responsive media handling with `aspect-ratio` and `object-fit`;
- hover and focus states for interactive elements;
- `@media` queries for tablet and mobile layout adjustments;
- utility class `.visually-hidden` for accessible hidden headings.

## File Structure

```text
html-homework-09/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── img/
        ├── favicon.svg
        ├── play-button.webp
        ├── project-icon.svg
        └── video-preview.webp
```

## How to Run

No build step is required.

1. Open the `html-homework-09` folder.
2. Open `index.html` in a browser.
3. Use the navigation menu to move between page sections.

## Technologies

| Technology | Usage |
|---|---|
| `HTML5` | Page structure and semantic sections |
| `CSS3` | Styling, layout, responsive behavior, and interactions |
| `Flexbox` | Navigation, stats layout, and component alignment |
| `Google Fonts` | Roboto font connection |
| `SVG` / `WebP` | Favicon, icons, play button, and media preview |

## Learning Goal

This project helps practice:

- building a complete one-page layout;
- organizing semantic sections;
- using CSS variables for consistent design values;
- working with Flexbox alignment and wrapping;
- styling buttons, navigation, and media blocks;
- adapting a fixed desktop layout for tablets and phones.

---

© Project completed by Dolzhenko Andrii. All Rights reserved. May 2026.
