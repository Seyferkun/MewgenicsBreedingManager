## 2024-05-24 - Consistent Native Clear Buttons for Search Inputs
**Learning:** PySide6 provides a built-in clear button for `QLineEdit` via `setClearButtonEnabled(True)`. Users appreciate a quick way to clear search filters without manually backspacing, but it was inconsistently applied across various views in the app.
**Action:** Always enable `setClearButtonEnabled(True)` for any `QLineEdit` that functions as a search or filter input to ensure consistent and accessible native UI interactions.
