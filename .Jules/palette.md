## 2024-08-22 - Missing Search Clear Buttons
**Learning:** PySide6 provides a native way to allow clearing of `QLineEdit` fields using `setClearButtonEnabled(True)`. This is a vital UX element for search/filter inputs to allow quick resets, but was missed in several newer views.
**Action:** Always enable `setClearButtonEnabled(True)` on any `QLineEdit` used for searching or filtering across the app.

## 2024-08-22 - Icon-only buttons lacking accessible names
**Learning:** `QToolButton` elements that use text symbols (like "↗") or icons without textual labels are opaque to screen readers. Relying only on `setToolTip()` is insufficient for full accessibility in PySide6.
**Action:** Consistently set `.setAccessibleName("...")` on any icon-only interactive elements (`QPushButton`, `QToolButton`) to ensure proper screen reader support.
