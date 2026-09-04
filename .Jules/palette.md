## 2023-10-27 - Native Clear Buttons in PySide6
**Learning:** PySide6 QLineEdits used for searching or filtering can have a native, one-click clear button enabled via `setClearButtonEnabled(True)`. This significantly improves usability compared to making users manually backspace out search terms, especially in lists.
**Action:** Always check if filter/search inputs have `setClearButtonEnabled(True)` enabled and add it if missing. Also ensure they have a helpful placeholder text set via `setPlaceholderText`.
