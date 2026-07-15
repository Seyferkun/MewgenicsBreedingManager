## 2024-05-24 - PySide6 Clear Buttons
**Learning:** Adding a native clear button to `QLineEdit` in PySide6 makes forms much easier to use, and many inputs in this app lack them.
**Action:** Always call `setClearButtonEnabled(True)` on QLineEdit widgets used as search or filter inputs.
