# Palette's Journal

## 2026-08-01 - Nested Interactive Elements inside Links
**Learning:** Nesting interactive `<button>` tags inside `<a>` links is syntactically invalid HTML, causing screen reader confusion and redundant focus outlines. Converting them to non-interactive styling elements like `<span>` inside the parent link ensures semantic correctness.
**Action:** Replace nested `<button>` elements with `<span class="price-btn">` styled identically, with `display: block; text-align: center; cursor: pointer;`.
