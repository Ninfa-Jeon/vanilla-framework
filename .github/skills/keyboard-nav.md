---
name: Keyboard Navigation & Focus
description: Validate that all functionality is accessible via keyboard only
---

## Logic Rules:

1. **Focus Indicators:** Flag any CSS that includes `outline: none` or `outline: 0` without providing a high-visibility `:focus` alternative.
2. **Tab Order:** Flag `tabindex` values greater than `0`. Ensure logical DOM order matches visual order.
3. **Interactive Elements:** Any `div` or `span` with an `onClick` event MUST have a keyboard equivalent (`onKeyDown` for Enter/Space).
4. **Focus Traps:** Identify modals/drawers. Confirm focus is moved to the modal on open and returned to the trigger on close.
