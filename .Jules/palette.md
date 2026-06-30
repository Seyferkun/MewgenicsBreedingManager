## 2024-07-26 - Clear Button UX on QLineEdit
**Learning:** PySide6 QLineEdit supports a native clear button (X icon) that appears when text is entered, providing immediate user feedback and saving an explicit text deletion step. It's an easy win for search and filter inputs.
**Action:** Always enable `setClearButtonEnabled(True)` on QLineEdit widgets that are used primarily for search or filtering across the application.
