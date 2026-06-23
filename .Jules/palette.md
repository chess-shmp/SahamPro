## 2026-06-23 - Nested Interactive Elements & Focus States
**Learning:** Nesting <button> inside <a> is invalid HTML and causes issues with screen readers and focus management. High-contrast focus states are essential for dark-themed landing pages where browser defaults are often invisible.
**Action:** Use <span> or <div> styled as a button when inside an <a> tag. Always apply explicit :focus-visible styles.
