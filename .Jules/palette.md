## 2024-05-14 - PySide6 QLineEdit Clear Button and Placeholders
**Learning:** For consistent PySide6 UX in the Python application, QLineEdits used for search/filter inputs should have `setClearButtonEnabled(True)` to provide a native clear button and should have placeholder text.
**Action:** When creating search inputs, always set `setClearButtonEnabled(True)` and `setPlaceholderText()`.
