# Copilot Instructions for Odin Project HTML Boilerplate

## Project Overview
This is a simple HTML boilerplate project, structured for basic web development and learning purposes. It contains static HTML files and an image asset, with no build system, package manager, or external dependencies.

## Directory Structure
- `index.html`: Main landing page of the site.
- `pages/about.html`: Secondary page, typically for "About" information.
- `images/frieren.jpg`: Example image asset used in the site.

## Key Patterns & Conventions
- All pages are static HTML. No JavaScript, CSS, or server-side code is present.
- Use relative paths for linking images and pages (e.g., `images/frieren.jpg`, `pages/about.html`).
- Keep markup semantic and minimal. Use standard HTML5 elements (`<header>`, `<main>`, `<footer>`, etc.) where appropriate.
- No custom build, test, or deployment workflows are present. All changes are manual and immediately reflected in the file system.

## Editing Guidelines
- When adding new pages, place them in the `pages/` directory and link from `index.html`.
- When adding images, place them in the `images/` directory and use relative paths in HTML.
- Maintain consistent indentation and formatting across HTML files.
- Do not introduce frameworks, libraries, or tooling unless explicitly requested.

## Example: Linking Between Pages
```html
<!-- In index.html -->
<a href="pages/about.html">About</a>

<!-- In about.html -->
<a href="../index.html">Home</a>
```

## Example: Using Images
```html
<img src="../images/frieren.jpg" alt="Frieren">
```

## What NOT to Do
- Do not add JavaScript, CSS, or external dependencies unless asked.
- Do not create build scripts or configuration files.
- Do not change the directory structure without user approval.

---

If any conventions or patterns are unclear, please ask the user for clarification before proceeding with major changes.
