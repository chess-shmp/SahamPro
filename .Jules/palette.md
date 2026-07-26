## 2026-07-26 - Fix Nested Interactive Elements & Keyboard Focus

**Learning:** Nesting interactive HTML elements (like a `<button>` inside an `<a>` anchor) is highly illegal semantically, leading to severely degraded screen reader accessibility and unpredictable keyboard navigation across web browsers. Additionally, removing default browser outlines without a high-contrast replacement completely leaves keyboard-only users blind on focus transitions.

**Action:** Replace nested `<button>`s inside links with styled inline block element equivalents (like a `<span>` styled with identical button attributes). Ensure default outlines are always replaced with high-contrast `:focus-visible` styles (`outline: 3px solid #60a5fa; outline-offset: 4px;`) to fully support accessibility without compromising design aesthetic under standard interactions.
