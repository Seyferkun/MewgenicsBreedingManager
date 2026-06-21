## 2026-06-21 - Consistent Clear Buttons for PySide6 Search Inputs
**Learning:** In PySide6, search/filter inputs without a clear button can degrade accessibility and efficiency, as users are forced to manually delete text to reset the filter. Enabling `setClearButtonEnabled(True)` provides a native, expected UX for QLineEdits used for searching.
**Action:** For all PySide6 applications, when utilizing a `QLineEdit` as a search or filter input, ensure `setClearButtonEnabled(True)` is enabled for consistent and accessible user experience.
