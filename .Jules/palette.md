## 2026-04-16 - Custom Interactive UI Elements
**Learning:** Interactive text toggles built using `<div>` elements with `onclick` handlers are inaccessible to keyboard users and screen readers, as they lack default focusability and semantic meaning.
**Action:** Always use native `<button>` elements for custom interactive toggles. Additionally, provide ARIA attributes like `aria-expanded` and `aria-controls` to communicate the state and relationship to screen readers, and include `:focus-visible` styles to indicate keyboard focus.
