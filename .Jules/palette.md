## 2024-08-09 - Add clear buttons to search fields
**Learning:** Discovered that QLineEdit search/filter fields across the app lack a unified way to clear input quickly, which hinders keyboard users and generally slows down repetitive searching.
**Action:** Always enable `setClearButtonEnabled(True)` on PySide6 QLineEdits used for searching or filtering to provide a native, accessible clear button.
