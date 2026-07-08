## 2025-06-01 - Add Clear Button and Placeholder to QLineEdit Search/Filter Fields
**Learning:** In PySide6, QLineEdit instances used for filtering/searching can easily be made more intuitive and accessible by enabling `setClearButtonEnabled(True)` for native clear buttons and setting a helpful placeholder text like `setPlaceholderText("Search...")`. This reduces cognitive load and allows keyboard/mouse-driven immediate clearing of inputs.
**Action:** When adding or updating a QLineEdit intended for search/filtering, always configure it with a clear button and a placeholder string.
