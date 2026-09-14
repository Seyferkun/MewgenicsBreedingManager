## 2026-09-14 - Consistent Native Clear Buttons for Search Inputs
**Learning:** PySide6 provides a built-in `setClearButtonEnabled(True)` method for `QLineEdit` widgets, which adds a native and accessible clear ('X') button on the right side. This improves UX by offering an easy way to clear search filters consistently across different views without needing custom buttons or layouts.
**Action:** Always enable `setClearButtonEnabled(True)` on any `QLineEdit` used specifically for searching or filtering lists to maintain consistent app-wide UX and improve keyboard/pointer accessibility.
