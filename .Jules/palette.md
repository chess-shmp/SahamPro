# Palette's Journal

## 2026-08-10 - Nested Interactive Elements inside Anchor Links
**Learning:** Having a nested `<button>` element inside an interactive anchor link (`<a>`) is invalid HTML5 semantics and creates a terrible UX and accessibility issue for screen readers and keyboard navigation. The nested button overrides/conflicts with the link's focus, and screen readers get confused by nested focusable elements. It is much better to style the inner CTA as a `<span>` with visual button cues, and let the outer `<a>` handle the interaction, ensuring smooth navigation.
**Action:** Replace nested `<button>` tags with styled `<span>` tags, ensuring `display: block` and `text-align: center` style rules are maintained on the span.
