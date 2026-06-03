## 2024-05-18 - [Add Clear Button for Search/Filter Inputs]
**Learning:** PySide6 provides a native `setClearButtonEnabled(True)` method for `QLineEdit` which gives a consistent and accessible clear button, specifically useful for search and filter text inputs.
**Action:** Always enable `setClearButtonEnabled(True)` on any `QLineEdit` that functions as a search or filter input in PySide6 to enhance UX with zero additional custom widget code.
