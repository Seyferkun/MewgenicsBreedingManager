## 2023-10-27 - Consistent Search Input Clearing
**Learning:** In PySide6 desktop applications, ensuring `setClearButtonEnabled(True)` on `QLineEdit` widgets used for searching or filtering provides a native, accessible clear button. Some fields had it and others did not, breaking consistency.
**Action:** When building or modifying search/filter fields using `QLineEdit`, always append `.setClearButtonEnabled(True)` to provide users a direct way to reset the field.
