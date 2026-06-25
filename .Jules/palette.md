## 2026-06-25 - Improving Keyboard Accessibility and Semantic Validity

**Learning:** Interactive elements like `<button>` must not be nested inside `<a>` tags as it violates HTML standards and causes inconsistent behavior in screen readers and browsers. Additionally, dark-themed pages often have poor default focus indicator contrast, making keyboard navigation difficult.

**Action:** Use a `<span>` or `<div>` styled to look like a button when placing it inside an anchor tag. Always implement high-contrast `:focus-visible` styles (e.g., `3px solid #60a5fa`) to ensure clear visual feedback for keyboard users. Adding pre-filled messages to WhatsApp CTA links via `?text=` also reduces user friction by setting clear context for the interaction.
