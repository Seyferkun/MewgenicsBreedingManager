## 2024-05-18 - Added accessible names and tooltips to icon-only buttons
**Learning:** PySide desktop accessibility requires equivalent ARIA handling via `.setAccessibleName()` combined with `.setToolTip()` for visual users, especially on icon-only QPushButtons. Additionally, providing pointer cursors `.setCursor(Qt.PointingHandCursor)` gives essential interaction cues for custom painted buttons that don’t look native.
**Action:** When adding or auditing icon-only buttons in PySide apps, immediately apply accessible names, tooltips, and appropriate cursor feedback.
