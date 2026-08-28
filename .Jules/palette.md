## 2025-02-23 - Add accessible names to QToolButtons

**Learning:** PySide6 `QToolButton` widgets used as icon-only actions (like "jump to pair" or toggle lists) are invisible to screen readers without an explicitly set accessible name, even if they have a tooltip or text that is hidden.
**Action:** When adding or auditing icon-only `QToolButton` (or `QPushButton`) widgets in PySide6, always add `btn.setAccessibleName("Descriptive Action Name")` alongside `btn.setToolTip()`.