## 2023-10-26 - Native Clear Button for QLineEdit
**Learning:** PySide6's `QLineEdit` has a built-in method `setClearButtonEnabled(True)` which provides a native, accessible clear icon (typically an 'x') for search inputs, removing the need to implement custom clear buttons and manual state handling.
**Action:** Use `setClearButtonEnabled(True)` on any `QLineEdit` that acts as a search, filter, or query input to provide consistent and accessible UX across the application.
