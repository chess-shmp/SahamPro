## 2026-07-24 - Interactive Nesting and Keyboard Focus Affordance

**Learning:** Nesting interactive elements like `<button>` inside an anchor tag `<a>` is an HTML validation error and causes severe screen reader navigation issues. Additionally, high-contrast `:focus-visible` outline styles with an `outline-offset` prevent outline clipping by parent container boundaries and provide a clear keyboard navigation path.

**Action:** Replace nested interactive components within links with semantic non-interactive sub-elements (like a `<span>` styled as a button with `display: block`), and apply global focus-visible indicators to all navigable targets.
