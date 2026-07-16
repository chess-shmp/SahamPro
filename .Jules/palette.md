# Palette's Journal - Saham Pro

This journal tracks critical UX and accessibility learnings for the Saham Pro landing page.

## 2026-07-16 - Invalid Interactive Nesting Pattern
**Learning:** Found `<button>` elements nested inside `<a>` tags in the membership section. This is invalid HTML that causes confusion for screen readers and breaks the expected interaction model (as both are focusable).
**Action:** Replace nested `<button>` with a `<span>` styled as a button to preserve visual appearance while maintaining valid semantic HTML and accessibility.
