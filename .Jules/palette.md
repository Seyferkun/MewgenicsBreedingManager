## 2024-05-18 - QLineEdit UX Polish
**Learning:** PySide6 `QLineEdit` inputs used for searching or filtering are inconsistent; some have `setClearButtonEnabled(True)` and `setPlaceholderText(...)`, while others don't. Memory explicitly advises enabling this native clear button and adding placeholders for search/filter inputs.
**Action:** Ensure `setClearButtonEnabled(True)` is used for all QLineEdit instances that serve as search or filter inputs, and that they have descriptive placeholders.
