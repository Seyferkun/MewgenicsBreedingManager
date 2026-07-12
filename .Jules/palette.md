## 2024-07-12 - Ensure PySide6 Filter Inputs Have Clear Buttons and Placeholders
**Learning:** PySide6 QLineEdits used for searching or filtering can easily lack discoverability if they don't have placeholder text, and they require extra user effort to clear if they don't have a clear button enabled via `setClearButtonEnabled(True)`.
**Action:** Always enable `setClearButtonEnabled(True)` and set a descriptive placeholder text on any `QLineEdit` intended to be used as a search or filter input to improve native UX and discoverability.
