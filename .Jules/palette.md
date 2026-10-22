## 2025-02-09 - Systematically add native clear buttons to QLineEdits
**Learning:** PySide6 provides a built-in method `setClearButtonEnabled(True)` that adds a native, accessible clear (X) button inside QLineEdits. This is cleaner and more accessible than implementing custom clear buttons inside or alongside search fields.
**Action:** Always enable `setClearButtonEnabled(True)` on QLineEdit widgets used as search or filter inputs across the application for better UX and consistency.
