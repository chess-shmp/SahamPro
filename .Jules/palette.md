# Palette's Journal - Saham Pro Landing Page

This journal contains critical UX and accessibility learnings from working on the Saham Pro landing page.

## 2026-08-14 - Interactive Nested Elements & Focus States Accessibility
**Learning:** Nesting interactive tags such as `<button>` inside an `<a>` is invalid HTML and confuses screen readers. Standard browsers might bubble events unexpectedly, and some users might experience focus trapping. Using a semantic outer `<a>` with an inner `<span>` styled block-level ensures visual parity, perfect screen reader traversal, and robust custom accessibility labels. Additionally, keyboard focus visible indicators must always have high-contrast styling and proper offset to ensure they are not clipped by parent element card borders or container overflow.
**Action:** Replace nested interactive elements with custom block span components within `<a>` anchors, and configure generous `outline-offset` on high-contrast focus rings.
