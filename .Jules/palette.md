## 2025-01-20 - [Clear Buttons on Search Inputs]
**Learning:** PySide6 QLineEdits used for filtering/searching frequently lack clear buttons natively in this app, requiring manual clicks to clear text instead of a single tap which is worse UX and accessibility.
**Action:** Always enable `setClearButtonEnabled(True)` on QLineEdit instances used for filtering, searching, or querying.
