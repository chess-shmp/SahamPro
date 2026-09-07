## 2026-09-07 - Refactored Card CTAs and Keyboard Focus States
**Learning:** Nesting interactive `<button>` elements inside card anchor `<a>` tags causes invalid HTML semantics and broken screen reader focus. Additionally, external WhatsApp links without pre-filled message parameters increase interaction friction.
**Action:** Replace nested `<button>` tags with `<span class="price-btn">` styled as buttons, apply global `:focus-visible` outline styles, and append package-specific `?text=` query parameters and `target="_blank" rel="noopener noreferrer"` attributes to WhatsApp CTAs.
