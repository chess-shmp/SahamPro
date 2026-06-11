# Palette's Journal

## 2026-06-11 - Initial Workspace Setup
**Learning:** The repository is a static landing page for 'Saham Pro' (Indonesian stock community) consisting of index.html and style.css, with no package.json or build system.
**Action:** Use a Python HTTP server for local testing: `python3 -m http.server 8000`.

## 2026-06-11 - CTA Nesting Accessibility
**Learning:** Interactive elements like <button> must not be nested inside <a> tags; use a <div> or <span> styled as a button to maintain HTML validity and accessibility.
**Action:** Refactor pricing cards to replace nested <button> with a styled <span>.
