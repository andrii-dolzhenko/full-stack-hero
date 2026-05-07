# HTML Homework 08 - Float Layout Demo

> A static educational project that demonstrates how to build different block layouts using `float`, `margin`, and `clearfix`.

## Project Description

**HTML Homework 08** is a one-page demo website created for practicing classic CSS block positioning without using `flex` or `grid`.

The page presents plant cards arranged into several layout compositions:

| No. | Layout | What It Demonstrates |
|---|---|---|
| 1 | One block on the left, one block on the right | Basic usage of `float: left` and `float: right` |
| 2 | One block on the left, several blocks on the right | Grouping elements on different sides of a container |
| 3 | Two blocks on the left, two blocks on the right | Symmetrical card positioning |
| 4 | Three blocks on the right | A combination of one large card and two smaller stacked cards |
| 5 | Three centered blocks | Centering a grouped layout with `margin: 0 auto` |

## Features

- **Variant navigation** - quick links allow users to jump to each demo section.
- **5 ready-made float layouts** - the page visually demonstrates different ways to position blocks.
- **Plant cards** - each card includes an image, title, short description, and Wikipedia link.
- **Layout explanations** - `<details>` and `<summary>` blocks explain how each layout is built.
- **"How the Code Works" section** - describes the role of `float`, `margin`, `clearfix`, and responsive behavior.
- **Responsive layout** - complex float compositions become simpler and easier to read on tablets and phones.
- **Back-to-top button** - a fixed "Home" button returns the user to the top of the page.

## Implementation Highlights

### HTML

- Semantic page structure: `main`, `section`, `article`, `nav`, and `footer`.
- Accessible `alt` text for plant images.
- External links open in a new tab with `rel="noopener noreferrer"`.
- Native HTML elements `details` and `summary` are used for expandable explanations.

### CSS

```css
.plant-card--left {
  float: left;
}

.plant-card--right {
  float: right;
}
```

Main CSS techniques:

- `float` for positioning cards on the left or right side;
- `margin` for spacing between blocks;
- `clearfix` for clearing floated elements;
- CSS custom properties for colors, sizes, and spacing;
- `@media` queries for adapting the page to different screen widths;
- `transition` and hover effects for smooth card and button interactions.

## File Structure

```text
html-homework-08/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    ├── fonts/
    │   ├── Inter-Bold.woff2
    │   ├── Inter-Regular.woff2
    │   └── Inter-SemiBold.woff2
    └── img/
        ├── icons/
        └── plants/
```

## How to Run

1. Open `index.html` in a browser.
2. Review the **"Task"** section.
3. Use the navigation links to move between layout variants.
4. Expand the explanation below each layout.

## Technologies

| Technology | Usage |
|---|---|
| `HTML5` | Page structure |
| `CSS3` | Styling, float layouts, responsiveness |
| `WebP` / `SVG` | Plant images, decorative elements, and icons |
| `WOFF2` | Local Inter fonts |

## Learning Goal

This project helps practice:

- how `float` works;
- the difference between `float: left` and `float: right`;
- using `margin` to control spacing;
- clearing floats with `clearfix`;
- adapting older layout techniques for modern screen sizes.

---

© Project completed by Dolzhenko Andrii. All Rights reserved. May 2026.
