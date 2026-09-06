## 2024-05-18 - PySide6 QLineEdit UX Consistency
**Learning:** In PySide6 applications, `QLineEdit` widgets used for searching or filtering should consistently use `setClearButtonEnabled(True)` to provide a native, accessible clear button.
**Action:** When adding new search/filter inputs to a PySide6 GUI, proactively apply `setClearButtonEnabled(True)` during initialization.
