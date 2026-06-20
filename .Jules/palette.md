## 2026-06-20 - Accessible Membership Cards and Intent-based WhatsApp CTAs
**Learning:** For landing pages with pricing cards, using an `aria-label` on the parent anchor (e.g., "Join Pro - 100K/month") provides a better screen reader experience than reading individual card elements. Pre-filling WhatsApp messages with tier-specific intent (e.g., `?text=...`) significantly reduces user friction.
**Action:** Use `aria-label` for summary descriptions on complex interactive cards and utilize pre-filled message parameters for messaging-based CTAs.

## 2026-06-20 - High-Contrast Focus Visibility on Dark Themes
**Learning:** Default browser focus rings often have poor contrast on dark, glow-heavy designs. A custom `:focus-visible` outline with `outline-offset` ensures accessibility without interfering with the visual aesthetics of the UI.
**Action:** Implement global `:focus-visible` styles with appropriate offsets for all keyboard-accessible elements.
