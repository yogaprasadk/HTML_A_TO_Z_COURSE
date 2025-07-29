# Copilot Instructions for HTML_A_TO_Z_COURSE

## Project Overview
This project is a collection of HTML tutorials and example files, organized by lecture, for learning and teaching HTML from basics to advanced topics. Each lecture folder contains a standalone HTML file demonstrating specific concepts.

## Structure & Conventions
- **Lecture Folders:** Each `Lecture X/` directory contains a single HTML file (e.g., `Lecture 1.html`, `index.html` for Lecture 8) focused on a particular topic.
- **Media Assets:**
  - `image/` contains images for use in HTML examples.
  - `Audio/` and `Videos/` contain media files referenced in some lectures.
- **No Build System:** There is no build, test, or transpile step. All files are static and can be opened directly in a browser.
- **Naming:** Use clear, descriptive names for new lecture files and assets. Follow the existing pattern (e.g., `Lecture 9.html`).
- **HTML Style:**
  - Use semantic HTML5 elements where possible.
  - Keep code readable and well-indented.
  - Demonstrate best practices for beginners (e.g., use `<thead>`, `<tbody>` for complex tables, alt text for images).

## How to Add Content
- To add a new example, create a new lecture folder and HTML file, or add to an existing one if appropriate.
- Reference images, audio, or video using relative paths (e.g., `image/download.jpg`).
- Keep each HTML file self-contained (no external CSS/JS unless teaching those topics).

## Key Files & Examples
- `Lecture 8/index.html`: Shows table usage, including a "Fruit Table" and a student info table.
- `README.md`: Contains links to video tutorials and a high-level course outline.

## AI Agent Guidance
- Do not add frameworks, build tools, or package managers.
- Do not introduce JavaScript or CSS unless the lecture is specifically about those topics.
- When generating HTML, prefer clarity and educational value over brevity.
- If updating a table or example, preserve the teaching intent and add comments if the change is non-obvious.

## Example: Adding a Table
To add a new table to a lecture file:
```html
<h2>New Table Title</h2>
<table border="1">
  <tr><th>Header 1</th><th>Header 2</th></tr>
  <tr><td>Value 1</td><td>Value 2</td></tr>
</table>
```

---
If you are unsure about a change, ask for clarification or check the README for context.
