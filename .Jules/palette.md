# Palette's Journal - Saham Pro UX & Accessibility Insights

## 2026-07-28 - Semantic Nested Button & Focus Outline Resolution
**Learning:** Nested button elements inside interactive anchor elements are invalid HTML and block proper accessibility screen reading. Additionally, when styling interactive component overlays (like anchor pricing cards), maintaining a distinct custom keyboard focus outline that is high-contrast is essential to support users who rely on keyboard navigation.
**Action:** Always replace nested `<button>` tags within `<a>` with non-interactive block elements like `<span class="price-btn">`, style them appropriately, and define global or component-specific `*:focus-visible` states with offset outlines so focus rings are never clipped.
