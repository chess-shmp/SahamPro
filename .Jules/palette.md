# Palette's Journal

## 2026-07-01 - Initial Project Setup
**Learning:** The repository is a static landing page for 'Saham Pro' (Indonesian stock community) consisting of index.html and style.css, with no package.json or build system.
**Action:** Use a Python HTTP server for local testing: `python3 -m http.server 8000`. Use Playwright for visual verification.

## 2026-07-01 - Accessibility and Focus States
**Learning:** Interactive elements nested inside anchor tags (like buttons) are invalid HTML and confuse screen readers. High-contrast focus indicators are essential for keyboard navigability on dark-themed landing pages.
**Action:** Refactor nested buttons to spans with `display: block` and `cursor: pointer`. Implement global `:focus-visible` styles with `outline-offset` to prevent clipping.
