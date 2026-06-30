# Palette's Journal - Saham Pro

This journal contains critical UX and accessibility learnings for the Saham Pro landing page.


## 2026-06-30 - Improving Membership Card Accessibility
**Learning:** Nesting interactive elements like <button> inside <a> is invalid HTML and causes a redundant tab order. Replacing the button with a <span> and providing a descriptive aria-label on the parent <a> significantly improves the experience for keyboard and screen reader users.
**Action:** Always avoid nesting interactive elements. Use a <span> for visual "buttons" within a link card and ensure the card itself has a clear aria-label describing its purpose and key information.
