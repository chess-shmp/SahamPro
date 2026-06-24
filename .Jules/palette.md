## 2026-06-24 - Semantic Refactoring for Interactive Cards
**Learning:** Nesting a `<button>` inside an `<a>` tag is an invalid HTML pattern that creates ambiguous focus states and confuses screen readers. This pattern is common in pricing cards where a "button" is visually desired inside a clickable link.
**Action:** Replace the nested button with a `<span>` (styled as a button) and apply a descriptive `aria-label` to the parent `<a>` tag. This maintains visual design while ensuring HTML validity and clear accessibility context.
