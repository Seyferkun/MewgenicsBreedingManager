
## 2026-07-29 - Native Clear Buttons in PySide6 QLineEdits
**Learning:** PySide6 provides a native `setClearButtonEnabled(True)` method for `QLineEdit` which perfectly handles the display of a clear (X) button inside search and filter fields. This is much better UX than manual clear buttons or expecting the user to select-all and delete text, particularly because it only appears when text is present.
**Action:** When working on PySide6 applications, always enable `setClearButtonEnabled(True)` for any `QLineEdit` that functions as a search or filter input, and ensure it is paired with descriptive placeholder text.
