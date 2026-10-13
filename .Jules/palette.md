## 2025-02-23 - Qt Icon-Only Button Accessibility
**Learning:** Tooltips (`setToolTip`) are not consistently read by screen readers in PySide6/Qt for icon-only buttons.
**Action:** When adding UX polish to `QPushButton` or `QToolButton` that contain only icons or symbols, always explicitly set `setAccessibleName` alongside the tooltip and `setCursor(Qt.PointingHandCursor)`.
