## 2026-10-05 - Icon-Only Button Accessibility in PySide6
**Learning:** Screen readers cannot interpret icon-only buttons (like `QToolButton` or `QPushButton`) unless they are given an explicit accessible name. Tooltips alone are sometimes not sufficient for full accessibility compliance in Qt.
**Action:** Always add `setAccessibleName()` alongside `setToolTip()` and `setCursor(Qt.PointingHandCursor)` when creating icon-only buttons in PySide6 to ensure they are fully usable by screen reader users.
