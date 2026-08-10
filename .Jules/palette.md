## 2026-08-10 - PySide6 Input Search & ToolButton Accessibility
**Learning:** For a more native user experience and improved accessibility, QLineEdit elements used for searching should have the clear button enabled. Icon-only QToolButtons require an accessible name set for screen readers, which can typically be mapped directly from their tooltip text.
**Action:** When implementing new search bars using PySide6's QLineEdit, call `setClearButtonEnabled(True)`. When creating icon-only QToolButtons, always call `setAccessibleName()` using the tooltip string.
