# VibeThread Showcase Platform

An interactive, fully responsive e-commerce storefront interface featuring advanced layout compositions, dynamic theme properties, and micro-interactions.

## Features

* **Responsive Layouts:** Utilizes a mobile-first approach transitioning seamlessly between Flexbox columns on smaller viewports and a multi-column side-by-side layout on screens wider than `768px`.
* **CSS Grid Product Display:** Automatically adjusts product grids depending on screen widths (`1 column` for small mobiles, `2 columns` at `480px`, and `3 columns` for screens above `900px`).
* **Dark Mode Capability:** Centralized CSS root variables allow for instant interface theme toggling between standard Light mode and Slate Dark mode.
* **Micro-interactions:** Hover transitions on card items (`translateY` lifting effects and smooth drop-shadow scaling) provide a tactile, premium browsing experience.
* **Print Optimization:** Integrated `@media print` rules hide interactive wrappers (sidebars, navigation buttons) to deliver crisp, single-page catalog printouts.

## File Structure

* `index.html` - The markup containing semantic header, filter controls, product grids, and checkout slide-panels.
* `styles.css` - Custom styling rules containing design properties, layout components, and target media queries.

## Technology Stack

* Semantic HTML5
* Vanilla CSS3 (Custom Variables, Flexbox, Grid)

## Getting Started

1. Save `index.html` and `styles.css` in the same directory.
2. Open `index.html` in any web browser to view the interface.
3. Click the theme button (🌙) to toggle light and dark view states.