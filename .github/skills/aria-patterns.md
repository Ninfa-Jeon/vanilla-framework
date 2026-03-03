---
name: ARIA Patterns & Semantics
description: Validate the programmatic "name, role, and value" of UI elements
---

## Logic Rules:

1. **Redundant Roles:** Flag `role="button"` on a `<button>` tag (it's redundant).
2. **Missing Labels:** Every icon-only button (e.g., `<button><i class="icon-settings" /></button>`) must have an `aria-label` or `title`.
3. **Aria-Expanded:** Ensure toggle buttons (dropdowns, accordions) dynamically update the `aria-expanded` state.
4. **Landmarks:** Verify the presence of `<main>`, `<nav>`, and `<header>` for page structure.
