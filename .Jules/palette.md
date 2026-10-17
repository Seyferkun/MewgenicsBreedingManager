## 2024-05-14 - PySide6 Search Consistency
**Learning:** For consistent PySide6 UX in the Python application, native search or filter inputs (`QLineEdit`) can be easily improved by enabling `setClearButtonEnabled(True)` to provide a built-in clear button affordance that users expect from modern search boxes.
**Action:** Always enable `setClearButtonEnabled(True)` for any `QLineEdit` that acts as a search, filter, or transient text input. Ensure a helpful placeholder text is also provided.
