# Palette's Journal - Saham Pro

## 2025-05-14 - Keyboard Navigation and Focus States
**Learning:** Landing pages often overlook keyboard users by not providing visible focus states, especially on dark themes where default browser rings might be hard to see. Additionally, wrapping interactive elements (like buttons) inside other interactive elements (like links) is a common mistake that confuses screen readers and breaks HTML validity.
**Action:** Always ensure `:focus-visible` provides a clear, high-contrast indicator. Use `span` or `div` for visual "buttons" when the entire container is already a link.
