# coworking-space-site

Landing page for a playful coworking spaces directory. This is a small static site that showcases coworking options with images, brief descriptions, and a floating chatbox CTA.

## Overview

`coworking-space-site` is a simple static HTML/CSS project that demonstrates a landing page UI for coworking spaces. It's designed as a minimal, easy-to-read example for experimenting with layout, imagery, and basic interactions such as floating CTAs and buttons.

Key technologies used:

- HTML5 (`index.html`)
- CSS3 (`index.css`)
- Google Fonts (Montserrat)

## Features

- Clean header and navigation
- Large hero heading with a list of curated coworking spaces
- Reusable layout for each space item with image, caption, and `Book` button
- Floating chatbox button in the lower-right corner
- Simple, lightweight static site with no build tools or dependencies

## Preview

Open `index.html` in a browser to view the site. If you want to serve it locally for proper image and font behavior, see the instructions below.

## Getting Started (Development)

Prerequisites:

- A web browser (Chrome, Firefox, Safari, etc.).

To run a local web server (recommended):

```bash
# Start a simple HTTP server with Python 3
python3 -m http.server 8000

# Then open http://localhost:8000
```

You can also double-click `index.html` to open the page directly in your browser, but some systems may not serve local fonts or images properly that way.

## Project Structure

```
├── index.html       # Main static HTML page
├── index.css        # Styles for the page
├── images/          # Image assets for the site (icons and photos)
└── README.md        # This file
```

Images referenced in the demo:

- `images/pin.png`
- `images/burger.png`
- `images/hygge.jpg`
- `images/sky-garden.jpg`
- `images/generator.jpg`
- `images/message.png`

## Accessibility & Improvements (Ideas)

- Add alt text improvements and better accessibility attributes (ARIA) for interactive controls
- Make the layout responsive with media queries for mobile and tablet sizes
- Add hover & focus interactions for keyboard navigation
- Create a simple booking modal or real action on the `Book` button
- Implement a responsive menu for mobile and interactive toggling of nav (hamburger icon)

## Contributing

Contributions are welcome! For small static projects like this, a good first step is to fork the repo and open a PR with:

- Styling refinements and enhancements
- Accessibility updates
- Responsive design improvements

## License

This project is open-source; choose a license that fits your needs. If you'd like, you can use the MIT License.

---

If you'd like, I can add a small demo screenshot, basic accessibility fixes, or a minimal responsive layout next.
