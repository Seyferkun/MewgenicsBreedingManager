## 2025-03-09 - Consistent clear buttons on search fields
**Learning:** QLineEdit has a native clear button (setClearButtonEnabled), but it was inconsistently applied across various views, making navigation and filtering cumbersome for users.
**Action:** Ensure all search and filter QLineEdits use `setClearButtonEnabled(True)` to align with the core PySide6 UX expectation for input fields.
