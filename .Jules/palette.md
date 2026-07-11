# Palette's Journal - Saham Pro

## 2026-07-11 - Initial Audit & Accessibility Fixes
**Learning:** Interactive elements like `<button>` nested inside `<a>` tags create a confusing experience for screen readers and are invalid HTML. Additionally, the lack of explicit focus indicators makes the site difficult to navigate for keyboard users.
**Action:** Replace nested buttons with styled spans and implement a global high-contrast `:focus-visible` style.
