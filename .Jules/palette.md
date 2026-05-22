## 2024-05-19 - Added Clear Buttons to Search Inputs
**Learning:** PySide6's `QLineEdit` widgets used as search or filter inputs often lack a clear button by default. This makes clearing the search query slightly tedious for keyboard users and requires an explicit select-all + delete action.
**Action:** Always enable `setClearButtonEnabled(True)` on any `QLineEdit` instances configured as search bars or filter inputs in PyQt/PySide applications to provide a native, accessible clear button.
