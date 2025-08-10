# Coffee Break

A simple, stylish multi-page website built with **pure HTML5 and CSS3** — no frameworks, no JavaScript.

## Preview

Open `index.html` directly in your browser, or run a tiny static server (recommended) to avoid CORS issues with images on some setups.

```bash
# Option 1: using npx (Node.js required)
npx http-server .

# Option 2: VS Code Live Server
# Right-click index.html → “Open with Live Server”

Then visit: `http://localhost:8080` (or the port shown in your terminal).

## Features

- Clean, semantic HTML structure.
- Modular CSS: page-specific styles + shared “common” utilities.
- Responsive layout for common screen sizes.
- Multi-page navigation:
  - **Home** (`index.html`)
  - **Coffee Varieties** (`coffee_variety.html`)
  - **Coffee Places** (`coffee_place.html`)
  - **Contacts** (`coffee_contact.html`)

## Tech Stack

- **HTML5**
- **CSS3** (custom styles, no preprocessors or frameworks)
```
Вот это в формате **Markdown**:

```md
## Development Notes

- **Reset first:** `coffee_reset.css` should be loaded before other styles.
- **Shared rules:** `coffee_common.css` contains base typography, colors, and reusable classes.
- **Page styles:** each page has its own CSS file to keep concerns separated.
- **Images:** stored in `/img`. Keep filenames lowercase and web-friendly.

## How to Customize

1. Replace images in `/img` with your own (keep sizes similar for best results).
2. Update content inside each HTML file — sections are organized and commented for quick edits.
3. Adjust color palette and spacing in `coffee_common.css` for a global theme change.

## Roadmap (ideas)

- Add dark/light theme toggle (pure CSS `prefers-color-scheme`).
- Improve accessibility (tab order, focus states, landmarks).
- Add print styles for the varieties page.
- Optional: minify CSS for production.

## Author

Made by [GrayMurakami](https://github.com/GrayMurakami)
```
