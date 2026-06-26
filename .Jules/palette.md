## 2024-05-18 - [Add Clear Button to Search Fields]
**Learning:** When building search and filter boxes with PySide6/PyQt, developers frequently overlook native features like `setClearButtonEnabled(True)`. Without it, users are forced to backspace through their queries to reset the filter, which hurts the overall UX significantly for frequently used forms.
**Action:** Always check if a `QLineEdit` is being used as a search input or filter and ensure it has `setClearButtonEnabled(True)` to streamline navigation and state clearing.
