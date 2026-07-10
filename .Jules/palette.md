## 2026-07-10 - [Nested Interactive Elements]
**Learning:** Nesting interactive elements like `<button>` inside `<a>` tags is invalid HTML and causes significant issues for screen readers and keyboard navigation, as the focus and click behavior become ambiguous. In this project, the pricing cards were links, but contained a "Join Now" button inside them.
**Action:** Replace nested `<button>` elements with `<span>` or `<div>` elements and style them to look like buttons. This preserves the visual design while maintaining a clean, single-action focus for the parent anchor tag.
