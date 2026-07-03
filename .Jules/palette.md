# Palette's Journal - Saham Pro

## 2026-07-03 - Nested Interactive Elements in Pricing Cards
**Learning:** Nesting <button> inside <a> is invalid HTML and causes confusing behavior for screen readers and keyboard navigation, as both are interactive. Replacing the inner button with a styled <span> maintains visual integrity while ensuring a single, clear interactive target.
**Action:** Always verify that call-to-action cards wrapping entire blocks do not contain nested buttons; use semantic spans with button-like styling instead.
