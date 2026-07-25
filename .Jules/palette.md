## 2026-07-25 - Native Clear Buttons in Qt Search Inputs
**Learning:** Setting `setClearButtonEnabled(True)` on QLineEdits used for search/filtering provides a native, zero-friction way for users to clear their active filters without requiring backspacing or a custom button implementation.
**Action:** Default to enabling the native clear button on any QLineEdit intended for search or filtering across PySide/Qt applications to improve accessibility and convenience.
