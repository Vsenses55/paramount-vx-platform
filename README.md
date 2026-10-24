# Paramount VX — Prototype

Functional prototype of the Paramount VX virtual event experience (UX Redesign 2023), built from the Figma Design page.

**Screens:** On-boarding → Bronson Plaza → Lobby → Theater

The layout is fixed at 1920×1080 (the Figma frame size) and scales down proportionally on smaller screens.

## Run locally
Open `index.html` in a browser. No build step.

## Structure
- `index.html` — markup, styles and script for every screen and component
- `assets/` — backgrounds and icons exported from Figma

Each element carries a `data-component` attribute matching its Figma component name (e.g. `button-white`, `panel-chat`, `direction-controller`), ready for the design system.

## Hosting
Published with GitHub Pages from the `main` branch, root folder.
