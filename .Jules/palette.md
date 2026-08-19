## 2024-05-18 - QLineEdit Clear Buttons
**Learning:** PySide6/Qt's QLineEdit supports a native clear button via `setClearButtonEnabled(True)`. This is a low-effort, high-impact a11y/UX improvement for search and filter inputs across the app, saving users manual text deletion.
**Action:** When creating new QLineEdit widgets for filtering or searching, always enable the clear button by default.
