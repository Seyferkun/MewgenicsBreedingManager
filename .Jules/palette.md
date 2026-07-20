## 2024-11-20 - Ensure consistent use of native clear buttons in QLineEdit

**Learning:** When dealing with PySide6, using `setClearButtonEnabled(True)` natively gives the user an easily accessible button to clear standard search/filter inputs, providing a huge usability benefit over forcing them to manually highlight and backspace text. Additionally, setting a helpful placeholder ensures the context of a search input is clear to the user.

**Action:** Always check if a search `QLineEdit` widget has `setClearButtonEnabled(True)` and `setPlaceholderText()` properly initialized, and implement them to improve usability where appropriate.