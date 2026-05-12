# HTML Homework 10 - Responsive Simple Site

A responsive version of the **Simple Site** landing page created to practice media queries, flexible layout behavior, responsive spacing, and adaptation for different screen sizes.

## Project Description

**HTML Homework 10** is a responsive landing page based on the existing **Simple Site** template.

The project focuses on adapting the desktop layout for different screen sizes, including mobile phones, tablets, laptops, and desktop screens. The layout keeps the original visual style of the Figma design while improving flexibility and readability on smaller devices.

The page includes a header navigation, hero section, about section, project statistics block, process/video section, and footer.

## Homework Goal

The goal of this homework is to adapt the **Simple Site** layout to responsive design.

The page should display correctly on screens starting from **375px width and larger**. The layout should remain readable, visually balanced, and convenient to use on mobile, tablet, and desktop devices.

## Main Requirements

| Requirement | Implementation |
|---|---|
| Media Queries | CSS media queries are used for tablet and mobile layouts. |
| Minimum Screen Width | The layout was tested from 375px and does not create horizontal scrolling. |
| Responsive Design | Spacing, alignment, text sizes, navigation, statistics, video, and footer adapt to different screen sizes. |
| Testing | The page was tested on mobile, tablet, laptop, and desktop viewport widths. |

## Tested Screen Sizes

The layout was checked on the following viewport widths:

| Width | Device Type | Result |
|---|---|---|
| 375px | Mobile phone | Works correctly without horizontal scroll. |
| 430px | Mobile phone | Content remains readable and balanced. |
| 480px | Large mobile phone | Navigation, button, and sections display correctly. |
| 768px | Tablet | Project statistics are arranged in a balanced 3 + 3 layout. |
| 1024px | Large tablet / small laptop | Layout remains close to the desktop structure. |
| 1440px | Desktop | Desktop layout works correctly. |
| 1920px | Large desktop | Layout matches the original Figma proportions. |

## Page Sections

| Section | Purpose |
|---|---|
| Header | Contains the main navigation with anchor links. |
| Hero | Presents the main headline, intro text, and call-to-action button. |
| About | Contains a short description section. |
| Stats | Displays repeated project statistic items with icons and numbers. |
| Process | Shows the "How I Work" section with a responsive video preview image. |
| Footer | Contains the author name and copyright text. |

## Features

- Responsive landing page based on the Simple Site template.
- Flexible container with a desktop maximum width and mobile side padding.
- Navigation adapts to smaller screens using Flexbox wrapping.
- Hero section is centered on mobile devices for better readability.
- Call-to-action button adapts to mobile width.
- Project statistics block rearranges for tablet and mobile screens.
- Video preview scales proportionally using `aspect-ratio`.
- Footer is aligned to the desktop layout on larger screens and centered on mobile.
- Smooth hover effects for links, button, and video play button.
- No horizontal scrolling at the required minimum width of 375px.

## Implementation Highlights

### HTML

- Semantic HTML structure is used: `header`, `nav`, `main`, `section`, and `footer`.
- Navigation uses anchor links for moving between page sections.
- The page contains one main `h1`.
- Content sections use appropriate `h2` headings.
- Decorative project icons use empty `alt=""`.
- The statistics section includes a visually hidden heading for better document structure.

### CSS

Main CSS techniques:

- CSS custom properties for colors, fonts, spacing, sizes, and transitions.
- Flexbox for layout, alignment, navigation, statistics, and responsive behavior.
- Media queries for tablet and mobile screen sizes.
- Flexible container with `max-width` and side padding.
- Responsive media handling with `width: 100%`, `aspect-ratio`, and `object-fit`.
- Utility class `.visually-hidden` for accessible hidden headings.
- Smooth hover transitions for interactive elements.

Example of responsive-related CSS logic:

```css
.container {
  width: 100%;
  max-width: var(--container-max-width);
  margin: 0 auto;
  padding-right: var(--container-padding);
  padding-left: var(--container-padding);
}

.process__image {
  width: 100%;
  aspect-ratio: 1110 / 600;
  object-fit: cover;
}

@media (max-width: 768px) {
  .hero {
    text-align: center;
  }

  .stats__list {
    max-width: 503px;
    gap: 34px 40px;
  }

  .footer {
    text-align: center;
  }
}
```

## File Structure

```text
html-homework-10-responsive-simple-site/
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

1. Open the `html-homework-10-responsive-simple-site` folder.
2. Open `index.html` in a browser.
3. Use browser developer tools to test different screen widths.
4. Check the published version through GitHub Pages.

## Technologies

| Technology | Usage |
|---|---|
| `HTML5` | Semantic page structure and content sections. |
| `CSS3` | Styling, layout, responsive behavior, and interactions. |
| `Flexbox` | Flexible layout, alignment, navigation, and statistics block. |
| `Media Queries` | Responsive adaptation for different screen sizes. |
| `Google Fonts` | Roboto font connection. |
| `SVG` / `WebP` | Favicon, project icons, play button, and video preview image. |
| `GitHub Pages` | Project publishing and browser testing. |

## Learning Goal

This project helps practice:

- adapting a desktop layout for responsive design;
- using media queries for different viewport widths;
- testing layouts from 375px and larger;
- working with flexible containers and responsive images;
- using Flexbox for alignment and wrapping;
- improving readability and spacing on mobile devices;
- preparing a project for GitHub Pages publication.

---

© Project completed by Dolzhenko Andrii. All Rights Reserved. May 2026.
