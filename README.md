# Solar System Explorer

Interactive Three.js-based solar system playground with info and control panels for tweaking simulation settings.

## Getting Started
- Open `index.html` in a modern browser (or serve the folder with any static server).
- Allow WebGL; audio is optional but recommended.

## Controls
- Drag to rotate the view; scroll/pinch to zoom; click/tap objects to focus.
- Use the left info panel for planet details and pins; use the right control panel for speed, time jumps, camera presets, and modes.
- On mobile (≤640px), the info and control panels are hidden by default; use the two top-center toggle buttons to show/hide each panel without wrapping.

## Panels and Tools
- Search, calculator, mission planner, and comparison modal are available via their respective buttons.
- Panels are draggable/scrollable and capped to 90vh on desktop to stay visible.

## Notes
- Tailwind CDN is used for utility classes; no build step required.
- Tested in Chromium-based browsers; enable hardware acceleration for smooth rendering.
