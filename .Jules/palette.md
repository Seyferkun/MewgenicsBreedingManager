## 2025-02-12 - Add clear button to PySide6 QLineEdits
**Learning:** PySide6/Qt provides a built-in `setClearButtonEnabled(True)` method for `QLineEdit` which creates a native 'x' clear button inside the text input field. This is very useful for search and filter fields, providing a native micro-UX improvement without custom UI components.
**Action:** When adding or updating search or filter fields (`QLineEdit`), enable `setClearButtonEnabled(True)` by default to improve usability for resetting queries.
