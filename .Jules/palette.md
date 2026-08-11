## 2026-08-11 - Resolving Interactive Nesting and Clipped Keyboard Focus Rings
**Learning:** Nesting interactive `<button>` elements within an outer card anchor `<a>` link is semantically invalid and disrupts assistive technologies. Additionally, high-contrast focus rings can be clipped by parent boundary limits unless adjusted with `outline-offset`.
**Action:** Always refactor nested buttons inside block-level links to styled structural elements (such as `span` with `display: block` and `text-align: center`) and explicitly apply `outline-offset` to keyboard-navigable focus states.
