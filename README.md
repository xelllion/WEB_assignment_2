# WEB Assignment 2 — Advanced CSS (Flexbox & Grid)

Personal multi-page website built for Assignment #2 (Advanced CSS layout with
Flexbox and CSS Grid). The project covers five tasks: a Flexbox navigation
bar, a Flexbox card row, a Grid page layout with grid areas, a Grid image
gallery, and a portfolio page combining Flexbox and Grid.

## Author

- **Name:** Aruzhan Amerkhanova
- **Group:** SE-2529

## Project Structure

```
WEB_assignment_2/
│
├── index.html          # Task 0 — Flexbox navigation bar
├── styles.css
│
├── task1.html           # Task 1 — Flexbox card row
├── task1.css
│
├── task2.html           # Task 2 — CSS Grid page layout (grid-template-areas)
├── task2.css
│
├── task3.html           # Task 3 — CSS Grid image gallery
├── task3.css
│
├── task4.html           # Task 4 — Portfolio page (Flexbox + Grid)
├── task4.css
│
├── images/
│   ├── card-*.svg
│   ├── gallery-*.svg
│   └── project-*.svg
│
└── README.md
```

## Pages Overview

| Page | Description |
|---|---|
| **Task 0 — index.html** | Header built as a flex container: logo on the left, nav links on the right, vertically centered. This same header is reused as the site navigation on every page. |
| **Task 1 — task1.html** | A flex container with four equal-height skill cards (image, title, text, button), even gaps, and a lift-on-hover effect. |
| **Task 2 — task2.html** | Full-page CSS Grid layout using `grid-template-areas`: header across the top, sidebar on the left, main content on the right, footer across the bottom. |
| **Task 3 — task3.html** | A nine-image CSS Grid gallery with consistent gaps and a caption overlay that fades in on hover. |
| **Task 4 — task4.html** | Portfolio page combining both: Flexbox in the header nav, a two-column CSS Grid for projects/sidebar, and Flexbox inside each project card. |

## Technologies Used

- HTML5
- CSS3 (Flexbox and CSS Grid)

## How to Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/xelllion/WEB_assignment_2.git
   ```
2. Open `index.html` in your browser (or use the "Live Server" extension in your code editor).
3. Navigate between tasks using the nav bar at the top of each page.

## Notes

- All pages share the same flex header/navigation bar and footer for a consistent look.
- CSS custom color palette used throughout: `#332A3D`, `#42394E`, `#8E6DFF`, `#BDB6D7`.
