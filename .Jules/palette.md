## 2024-05-18 - Qt Icon-Only Button Accessibility
**Learning:** Tooltips (`setToolTip`) on `QToolButton` and `QPushButton` instances that only display an icon are sometimes not announced by screen readers.
**Action:** Always call `setAccessibleName()` on icon-only buttons to guarantee an accessible label is provided for assistive technologies.
