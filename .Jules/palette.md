## 2024-05-24 - PySide6 Native Search Clear Buttons
**Learning:** Users need a quick way to clear search/filter inputs, especially when dealing with long lists of data. PySide6's QLineEdit has a native property `setClearButtonEnabled(True)` that handles this elegantly without requiring custom UI elements or signal wiring.
**Action:** Always enable `setClearButtonEnabled(True)` on any QLineEdit used for searching or filtering to provide a consistent and expected UX.
