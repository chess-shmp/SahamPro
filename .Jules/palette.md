# Palette's Journal - Saham Pro

## 2026-06-13 - Micro-UX and Accessibility Enhancements
**Learning:** Found that the landing page had several common micro-UX and accessibility issues:
1. **Invalid HTML Nesting:** Interactive elements like `<button>` were nested inside `<a>` tags. This is invalid HTML and can confuse screen readers or break event bubbling. Replaced the button with a semantic `<span>` styled as a button.
2. **Generic CTAs:** WhatsApp links were generic. Adding a pre-filled `text` parameter (`wa.me/number?text=...`) creates a "warm" start for the user and sets expectations for the business.
3. **Keyboard Navigation:** The site lacked visible focus indicators. Adding a global `:focus-visible` style ensures accessibility for keyboard users without affecting mouse users.

**Action:** Always verify semantic HTML validity (especially nesting of interactive elements) and look for opportunities to reduce user friction in external communication channels like WhatsApp by using pre-filled messages.
