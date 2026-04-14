## 2024-04-14 - Semantic Form Labels
**Learning:** This codebase incorrectly uses `<div>` elements for form labels instead of semantic `<label>` tags, reducing accessibility for screen readers and forcing users to click exactly on the form control rather than the larger target area provided by a linked label.
**Action:** When auditing forms, replace `<div>` labels with `<label for="...">` to improve accessibility and increase clickable target areas.
