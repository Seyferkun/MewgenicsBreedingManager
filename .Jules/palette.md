
## 2024-05-18 - Qt Icon-Only Button Accessibility
**Learning:** Tooltips (`setToolTip`) alone are often insufficient for screen readers in PySide6/Qt for icon-only buttons. The screen reader needs `setAccessibleName` to read out the button's purpose correctly since the button's text is just an icon character (e.g., "\u2194").
**Action:** Always add `setAccessibleName()` in addition to `setToolTip()` when creating icon-only `QPushButton` or `QToolButton` elements to ensure full accessibility support.
