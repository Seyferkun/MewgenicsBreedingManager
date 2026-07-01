## 2024-05-18 - QLineEdit Clear Buttons
**Learning:** PySide6/Qt provides a built-in `setClearButtonEnabled(True)` method for `QLineEdit` which gives users a native, accessible clear button (the "x" icon) inside search/filter boxes. This is a quick and effective UX win for inputs used for filtering long lists.
**Action:** When adding or auditing search/filter inputs in PyQt/PySide apps, always ensure `setClearButtonEnabled(True)` is set.
