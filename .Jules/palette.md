## 2024-05-20 - PySide6 Native Clear Buttons
**Learning:** PySide6 QLineEdits have a built-in `setClearButtonEnabled(True)` method that automatically adds a native, theme-appropriate "X" clear button when text is entered. Many custom search implementations in PySide apps miss this, requiring users to manually highlight and delete text.
**Action:** When implementing filter or search fields in PySide6, always add `.setClearButtonEnabled(True)` to the QLineEdit instance for immediate UX improvement.
