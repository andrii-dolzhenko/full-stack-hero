# Homework 06: Tables and Composition

## Project Overview

**Homework 06** is a small static HTML and CSS project focused on building table-based layouts, page navigation, and a visual composition inspired by Piet Mondrian. The project includes a home page that links to three separate task pages: two structured HTML table exercises and one geometric color composition.

The project is written with semantic HTML, shared CSS styling, responsive layout rules, and reusable visual components.

## What the Project Does

The website provides a simple navigation hub for viewing several layout exercises:

- **Home page**: introduces the assignment and provides large visual links to each task page.
- **Table 1**: demonstrates a basic table layout with merged cells using `rowspan` and `colspan`.
- **Table 2**: demonstrates a more complex parent table with a nested child table.
- **Mondrian page**: recreates an abstract grid composition using an HTML table, custom column widths, row heights, borders, and primary color blocks.

## Functional Features

- Multi-page static website structure.
- Shared top navigation across all pages.
- Active navigation state for the current page.
- Responsive page card layout for desktop and mobile screens.
- Styled table captions and table cells.
- Use of `rowspan`, `colspan`, and nested tables.
- Mondrian-style composition built with table rows, columns, and CSS classes.
- Custom SVG favicon and page icons.
- Hover and focus states for interactive links.

## Project Structure

```text
homework-06/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       ├── favicon.svg
│       ├── mondrian-icon.svg
│       ├── table-01-icon.svg
│       └── table-02-icon.svg
└── pages/
    ├── mondrian.html
    ├── table1.html
    └── table2.html
```

## Technologies Used

- **HTML5** for page structure and table markup.
- **CSS3** for layout, visual styling, responsive behavior, and interaction states.
- **SVG assets** for icons and the favicon.

## Design and Styling Notes

The interface uses a warm, classroom-style visual theme with soft gradients, bordered cards, serif headings, and clear navigation buttons. The table pages keep the layout centered and readable, while the Mondrian page uses strong black borders and red, yellow, blue, white, and black blocks to imitate the visual language of geometric abstraction.

## How to Open

Open `index.html` in a browser and use the navigation links to move between the assignment pages.

    © Project completed by Dolzhenko Andrii. All Rights reserved. April 2026.
