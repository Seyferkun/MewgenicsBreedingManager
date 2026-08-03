## 2026-08-03 - Missing clear buttons on QLineEdit search inputs
**Learning:** PySide6 QLineEdit does not have a clear button by default, leading to inconsistent search input UX across the app.
**Action:** When implementing a QLineEdit that serves as a search or filter input, ensure setClearButtonEnabled is set to True and a helpful placeholder text is set.
