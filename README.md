# goit-js-hw-08

Destructuring, events, libraries

## Project overview

This repository contains a JavaScript homework project implementing an image
gallery with a lightbox.

## Completed task: `js/gallery.js`

- Builds a gallery from a static `images` array of objects (`preview`,
  `original`, `description`).
- Renders gallery items into `ul.gallery` with clickable `<a>` links and `<img>`
  thumbnails.
- Prevents default link navigation and opens the full-size image in a modal via
  `basicLightbox`.
- Uses event delegation and click event handlers for interactive behavior.

## Usage

1. Open `index.html` in a browser.
2. Click a thumbnail to open the larger image in the lightbox.
3. Close the lightbox via built-in modal control (ESC or click outside,
   depending on `basicLightbox` behavior).

## Notes

- `src/js/gallery.js` is the core module for DOM creation and event handling.
- `css/styles.css` includes styles for `.gallery`, `.gallery-item`,
  `.gallery-link`, and `.gallery-image`.
- `basicLightbox` library is expected to be loaded in `index.html`.
