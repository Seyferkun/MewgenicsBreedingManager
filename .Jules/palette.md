## 2024-03-01 - Native clear buttons for PySide6 QLineEdit
**Learning:** PySide6 provides a built-in `setClearButtonEnabled(True)` method for `QLineEdit` which is extremely useful for search and filter inputs, rather than having to manually build one and manage the state.
**Action:** When adding search or filter inputs, verify if they are standard `QLineEdit` components. If they are, always enable `setClearButtonEnabled(True)` for a better out-of-the-box native UX for the user.
