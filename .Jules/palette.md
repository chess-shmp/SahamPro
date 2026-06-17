## 2026-06-17 - Semantic HTML and Focus Visibility
**Learning:** Nesting interactive elements like `<button>` inside `<a>` is invalid HTML and causes issues with screen readers and focus management. Even if visually styled correctly, it breaks the accessibility tree.
**Action:** Use a `<span>` or `<div>` styled as a button inside anchors to maintain visual design while ensuring semantic correctness. Always provide global `:focus-visible` styles to ensure keyboard users have clear visual feedback, especially on dark-themed landing pages where default browser outlines might have poor contrast.
