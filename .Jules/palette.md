# Palette's Journal - Critical Learnings Only

## 2026-07-19 - Semantic HTML and WhatsApp Referral Flow
**Learning:** Nesting interactive tags like `<button>` directly inside focusable parent anchor links (`<a>`) is invalid HTML5 that causes unpredictable accessibility issues for screen readers and breaks keyboard tab sequences. Replacing them with styled children (e.g., `<span class="price-btn">`) and explicitly setting high-contrast `:focus-visible` styles resolves these issues completely. Additionally, appending distinct URL-encoded parameters to WhatsApp links reduces friction and increases user conversions by pre-defining their selected tier.
**Action:** When a link contains a button-like element, always render the button-like element as a `<span>` styled with `display: block` and `text-align: center`, and ensure focus is captured beautifully via the parent container. App-specific messaging context should be embedded directly into external target links.
