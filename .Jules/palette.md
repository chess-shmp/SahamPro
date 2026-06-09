## 2025-05-15 - Improving Landing Page Micro-UX & Accessibility

**Learning:** Interactive elements like `<button>` must not be nested inside `<a>` tags as it is invalid HTML and causes issues for screen readers. Using a styled `<div>` or `<span>` inside the link maintains visual consistency while ensuring accessibility. Additionally, adding high-contrast `:focus-visible` styles and pre-filling WhatsApp CTA messages significantly reduces friction and improves navigation for all users.

**Action:** Always verify HTML nesting for interactive elements. Use specific pre-filled messages for CTAs to guide user intent. Implement global `:focus-visible` styles as a standard practice for better keyboard accessibility.
