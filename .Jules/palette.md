# Palette's Journal - Critical Learnings Only

## 2026-07-31 - Keyboard Accessibility and HTML Validation in Indonesian Landing Page
**Learning:** Nested buttons inside anchor links cause illegal HTML and make keyboard focus behavior confusing. High-contrast focus indicators must use `outline-offset` to avoid clipping. WhatsApp CTA conversion rate benefits immensely from pre-filled custom message templates with appropriate URL encoding.
**Action:** Replace nested `<button>` inside `<a>` with a styled `<span>` with `display: block` and `text-align: center`. Implement `:focus-visible` styles using `outline` and `outline-offset`. Ensure all social links have pre-filled localized parameters, `target="_blank"`, and `rel="noopener noreferrer"`.
