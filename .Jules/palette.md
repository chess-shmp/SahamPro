# Palette's Journal - Critical Learnings Only

This journal contains critical UX/accessibility insights, including reusable patterns, unexpected behaviors, or rejected changes.

## 2026-07-21 - Interactive elements nested inside anchor links

**Learning:** Having an interactive element (such as a `<button>`) nested within another interactive element (such as an `<a>` anchor link) is an accessibility and HTML validity issue. Screen readers get confused, and the nested element is not focusable or clickable independently in a standard-compliant way.

**Action:** Refactor nested `<button>` elements inside parent `<a>` tags into `<span>` or `<div>` elements styled to look like buttons, ensuring they use `display: block` or `display: inline-block` to fill the space and preserve styling.
