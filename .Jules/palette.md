## 2026-07-13 - Accessibility Fix: Nested Interactive Elements
**Learning:** Nesting a `<button>` inside an `<a>` tag is invalid HTML and causes issues for screen readers and keyboard navigation, as both are interactive elements that compete for focus and activation.
**Action:** Refactor nested `<button>` elements to `<span>` or `<div>` styled as buttons when they are wrapped in an anchor tag. Ensure the new element has `display: block` and `cursor: pointer` to maintain the intended UX and visual affordance.
