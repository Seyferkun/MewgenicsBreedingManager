## 2024-05-19 - Pointer Cursor on Interactive Elements
**Learning:** PySide6 does not apply a hand/pointer cursor to `QPushButton` or `QToolButton` elements by default when hovering, contrary to common web patterns. Adding `setCursor(Qt.PointingHandCursor)` explicitly makes interactive elements feel more discoverable and responsive.
**Action:** Always check if buttons, especially icon-only and toggle buttons, have `setCursor(Qt.PointingHandCursor)` applied in PySide6 applications.
