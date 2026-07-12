# Palette's Journal

## 2026-07-12 - Semantic Integrity for Links
**Learning:** Nesting interactive elements like `<button>` inside `<a>` tags is a common accessibility violation that causes redundant screen reader announcements and invalidates HTML.
**Action:** Use a `<span>` styled as a button (e.g., `display: block`, `cursor: pointer`) inside anchor tags to preserve the visual UX while maintaining semantic correctness and accessibility.
