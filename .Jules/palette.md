## 2024-05-15 - Enable Native Clear Buttons on Qt Line Edits
**Learning:** PySide6 `QLineEdit` widgets used for search or filtering provide a native cross-platform clear button ("x") when `setClearButtonEnabled(True)` is called. Users often want a quick way to clear filters to see all results, and a built-in button is more intuitive than manually backspacing.
**Action:** When implementing `QLineEdit` widgets meant for search, filter, or query inputs in PySide6 applications, always call `.setClearButtonEnabled(True)` and ensure a helpful placeholder text is set for better UX.
