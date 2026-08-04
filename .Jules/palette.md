# Palette's Journal - Saham Pro UX & Accessibility Insights

## 2026-08-04 - Fixing Nested Interactive Elements and Custom WhatsApp CTA Contexts
**Learning:** Nesting `<button>` inside an anchor `<a>` tag violates the HTML specification, breaking semantic layout, keyboard navigation, and screen reader interaction flows. Standardizing nested CTA designs to use block-level spans (`display: block; text-align: center`) within parent anchor tags maintains CSS fidelity without introducing redundant accessibility nodes. Additionally, adding tailored WhatsApp pre-filled text queries (e.g., specific package names) minimizes user contact friction and immediately aligns conversational expectations.
**Action:** When working on link-wrapped cards, replace nested interactive buttons with semantic spans styled appropriately. Always enrich external communication links with tailored context queries and standard visual target cues.
