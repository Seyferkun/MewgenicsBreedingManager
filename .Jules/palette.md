## 2024-10-15 - Enable Native Clear Button for Qt Inputs
**Learning:** In Qt/PySide6, `QLineEdit` widgets don't natively show a clear button unless configured, which can make it tedious to clear search inputs or filters using just the mouse. Setting this to True adds native accessibility without custom clear button implementations.
**Action:** Always enable `setClearButtonEnabled(True)` on `QLineEdit` widgets when they are used for search, filtering, or inputting text that users frequently need to clear.
