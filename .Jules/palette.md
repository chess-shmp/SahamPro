## 2026-07-04 - Accessible Interactive Components

**Learning:** Nesting interactive elements like `<button>` inside `<a>` tags is invalid HTML and causes screen reader confusion. While browsers may attempt to render them, the accessibility tree becomes unpredictable. Replacing nested buttons with styled `<span>` elements while maintaining the parent anchor tag preserves both the visual call-to-action and keyboard/screen reader accessibility.

**Action:** Always verify semantic HTML structure. Use CSS to style spans or divs as buttons when they must live inside an anchor tag for navigation. Use `aria-label` on the parent link to provide clear context for screen readers when the visual text might be ambiguous.
