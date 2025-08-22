# Invitation Template

This is a single-page HTML/CSS template that recreates the "PANINI NIL LOUNGE" invitation layout.

## How to use
1. Place your smoke/abstract background image at `assets/background.jpg`.  
   - If you keep a different file name, update the URL in `.canvas` in `styles.css`.
2. Open `index.html` in a browser to preview.
3. Edit the text directly in `index.html`:
   - Brand plaque: `<span class="brand-text">PANINI</span>`
   - Headline: `.headline-left` and `.headline-right`
   - Date/Time/Venue: the `.event-line` elements
   - Body copy: `.details`
   - Address: `.address`
   - Bottom ribbon: `.ribbon > span`
   - Bottom left capsule: `.capsule`
4. Replace `assets/badge-placeholder.svg` with your logo or badge and update the `<img class="badge" ...>` `src` if needed.
5. Colors, sizes, and shadows can be tuned at the top of `styles.css` via CSS variables.

## Exporting
- Use your browser's "Print to PDF" to get a high-resolution PDF.
- For PNG/JPG: open DevTools, set zoom to 100%, make the canvas as large as your screen allows, then take a full-size screenshot of the poster area. Alternatively, print to PDF and convert to image.

## Notes
- The canvas is designed at a 1080x1350 aspect ratio (Instagram-friendly). It scales responsively but keeps proportions.
- Fonts: Bebas Neue (headings) and Montserrat (body). Both are loaded from Google Fonts.
- Currently uses `assets/background.svg` as a placeholder. Replace with your own `background.jpg` for the final version.