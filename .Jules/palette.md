## 2026-07-15 - [Accessibility] Refactoring Nested Interactives
**Learning:** Nesting <button> inside <a> is invalid HTML and causes confusing behavior for screen readers and keyboard users. Replacing the button with a <span> styled as a button preserves visual intent while maintaining correct accessibility semantics.
**Action:** Always refactor nested interactive elements by converting the inner element to a non-interactive tag (like <span>) and applying button-like styles to it.
