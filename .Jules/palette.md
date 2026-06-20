## 2026-06-20 - Consistent Clear Buttons in PySide6 QLineEdits
**Learning:** PySide6's QLineEdit supports a native clear button via `setClearButtonEnabled(True)`. It is an effective and robust UX enhancement because clicking it automatically clears the text and fires the `textChanged` signal, cleanly integrating with existing filter logic without additional boilerplate.
**Action:** Always enable `setClearButtonEnabled(True)` on search and filter inputs in PySide6 applications for consistent and intuitive UX.
