# Palette's Journal

## 2026-08-05 - Semantic HTML and Interactive Link Nesting Issues
**Learning:** Nesting interactive `<button>` elements within interactive link tags (like `<a>`) violates HTML structural semantics and creates confusing accessibility tree models for screen readers. In addition, lack of focus-visible styles hides key interactive outlines from keyboard-only navigation users.
**Action:** Refactor interactive buttons nested in outer card links to semantic `<span>` elements styled to look like buttons, and provide a clear, high-contrast `:focus-visible` outline rules with non-zero `outline-offset` to keep indicators highly visible.
