## 2025-05-14 - Nested Interactive Elements Accessibility
**Learning:** Nesting a `<button>` inside an `<a>` tag is invalid HTML and causes conflicting behaviors for screen readers and keyboard users. Screen readers may only announce one of the elements, and click events can be unpredictable.
**Action:** Use a `<span>` or `<div>` styled as a button for visual elements inside an `<a>` tag to maintain semantic validity and accessibility.
