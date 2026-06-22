## 2024-06-22 - QLineEdit Search Clear Buttons
**Learning:** By default, PySide6/Qt `QLineEdit` widgets used for filtering/searching lack a built-in mechanism to quickly clear the input, requiring users to manually select and delete text.
**Action:** Always enable `setClearButtonEnabled(True)` on `QLineEdit` fields used for filtering and searching. Ensure they also have an appropriate `placeholderText` set for context.
