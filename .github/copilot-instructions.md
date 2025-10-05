# Copilot Instructions for PracticaCss

## Project Overview
This is a static web project focused on CSS practice and UI design. The main components are:
- `index.html`: The entry point for the site, containing the main HTML structure.
- `css/`: Contains CSS files for styling different sections (e.g., `style_header.css`, `style_login.css`).
- `img/` and `img/icon/`: Store images and icons used throughout the site.
- `fuente/`: Custom fonts for unique typography.

## Architecture & Patterns
- **Separation of Concerns**: HTML, CSS, images, and fonts are organized in dedicated folders.
- **CSS Structure**: Each major UI section has its own CSS file. For example, login-related styles are in `css/style_login.css`.
- **Font Usage**: Custom fonts are loaded from the `fuente/` directory, typically via `@font-face` in CSS files.
- **Image Management**: Images are referenced relative to the `img/` directory. Icons are further organized in `img/icon/`.

## Developer Workflows
- **Live Preview**: Use a local server (e.g., Five Server) for live reloading and previewing changes. No build step is required.
- **Adding Styles**: Create new CSS files in `css/` for new UI sections. Link them in `index.html` as needed.
- **Font Integration**: Add new fonts to `fuente/` and update CSS with `@font-face` rules.
- **Image Updates**: Place new images in `img/` or `img/icon/` and reference them in HTML/CSS.

## Project-Specific Conventions
- **File Naming**: CSS files are named by section (e.g., `style_header.css`).
- **Font Files**: Use `.ttf` and `.otf` formats for custom fonts.
- **No JavaScript**: The project is currently static and does not use JavaScript.
- **No Build Tools**: All files are served as-is; no compilation or bundling.

## Integration Points
- **Five Server**: Used for live preview. Start the server from VS Code for instant updates.
- **Custom Fonts**: Ensure font paths are correct when referencing in CSS.

## Examples
- To add a new login page style:
  1. Create `css/style_login.css`.
  2. Link it in `index.html`.
  3. Use images from `img/` and fonts from `fuente/` as needed.

## Key Files & Directories
- `index.html`: Main HTML file.
- `css/`: All CSS stylesheets.
- `img/`, `img/icon/`: Images and icons.
- `fuente/`: Custom fonts.

---
For questions or unclear conventions, review existing CSS files and `index.html` for examples. Ask for feedback if any workflow or pattern is not documented here.