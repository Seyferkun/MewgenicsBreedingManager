## 2024-06-19 - QLineEdit Native Search Clearing
**Learning:** PySide6 provides a native way to clear `QLineEdit` fields used for filtering and search. Missing this clear button creates friction, especially for screen reader users or keyboard navigators who want to reset filter states quickly without selecting all text and deleting it.
**Action:** Always enable `setClearButtonEnabled(True)` on any `QLineEdit` that acts as a search or filter input to provide a consistent, native UX pattern across the app.
