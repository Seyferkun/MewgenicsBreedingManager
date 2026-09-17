## 2024-05-18 - Making PySide6 icon-only buttons accessible
**Learning:** PySide6 icon-only buttons (`QPushButton` with symbol text like "↑" or "↓") need explicit accessibility configuration to be friendly for screen readers and visually clear for keyboard/mouse users. Simply setting text to a symbol is not enough.
**Action:** When adding or updating icon-only `QPushButton` widgets, ensure `setToolTip()`, `setAccessibleName()`, and `setCursor(Qt.PointingHandCursor)` are configured. Use localized strings (`_tr`) where possible for tooltips.
