## 2026-06-22 - Initial UX Audit & Accessibility Standards
**Learning:** Nested interactive elements (like <button> inside <a>) break semantic HTML and cause issues for screen readers. High-contrast focus states are essential for dark-themed landing pages where default browser outlines are nearly invisible.
**Action:** Always verify HTML validity for nested elements and explicitly define high-contrast :focus-visible styles in the global stylesheet.
