## 2026-06-21 - Accessible CTA Structure and Interaction
**Learning:** Interactive elements like <button> must not be nested inside <a> tags as it violates HTML specifications and confuses screen readers. Additionally, pre-filling WhatsApp messages reduces user friction and provides immediate context for the interaction.
**Action:** Use <span> with button-like styling inside anchors for complex CTAs. Always append context-aware query parameters (e.g., ?text=...) to external messaging links to guide the user's first message.
