---
name: Color Contrast Validation
description: Ensure text and interactive elements meet WCAG 2.1 AA contrast ratios
---

## Logic Rules:

1. **Standard Text:** Must maintain a contrast ratio of at least 4.5:1.
2. **Large Text (18pt+ or 14pt bold):** Must maintain at least 3:1.
3. **UI Components/Graphics:** Check that borders and icons have 3:1 contrast against background.
4. **Calculated Focus:** If hex codes are present in CSS/Tailwind, flag ratios below thresholds.
5. **Action:** If contrast cannot be determined (e.g., dynamic themes), flag for manual review with a "Contrast Warning."
