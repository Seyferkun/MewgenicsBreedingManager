## 2026-06-07 - Native Clear Buttons in QLineEdits
**Learning:** In PySide6, search and filter fields often require users to manually delete text to clear the filter. Enabling `setClearButtonEnabled(True)` on `QLineEdit` provides a native, accessible clear button (the 'x' icon) that improves usability without requiring custom UI elements or signal connections.
**Action:** Use `setClearButtonEnabled(True)` when adding new search or filter inputs to ensure a consistent and modern UX across the application.
