## 2024-05-18 - QLineEdit Native Clear Buttons
**Learning:** PySide6 provides a native clear button for `QLineEdit` via `setClearButtonEnabled(True)`. This is significantly more user-friendly for search and filter inputs than requiring manual text deletion, but it's not enabled by default. I discovered several list filtering inputs lacking this property, making them tedious to reset.
**Action:** Always enable `setClearButtonEnabled(True)` when creating a `QLineEdit` intended for searching or filtering lists to maintain consistent and accessible UX across the app.
