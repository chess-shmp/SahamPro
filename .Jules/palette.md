
## 2026-06-27 - [Accessibility and Interaction Refinement]
**Learning:** Nested interactive elements like <button> inside <a> are invalid HTML and confusing for screen readers. Refactoring these to <span> while applying a descriptive aria-label to the parent <a> maintains the visual design while ensuring accessibility. Additionally, pre-filling WhatsApp messages significantly reduces user friction by providing context for the interaction immediately.
**Action:** Always verify HTML validity for nested interactive elements and use parent-level ARIA labels to provide context for complex card-style links.
