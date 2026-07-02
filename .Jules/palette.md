## 2026-07-02 - Accessible Interactive Link Containers
**Learning:** Nesting `<button>` elements inside `<a>` tags is invalid HTML and can confuse screen readers. For interactive cards that function as a single link but contain a "button" visual, it's better to use a styled `<span>` for the visual button while the parent `<a>` carries the interactive role.
**Action:** Use a block-level `<span>` with button-like styling (e.g., `.price-btn`) inside an anchor tag for accessible and valid "button-in-card" patterns.
