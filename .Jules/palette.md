## 2024-07-11 - Native Clear Buttons in PySide6 QLineEdit
**Learning:** PySide6 provides a native `setClearButtonEnabled(True)` method for `QLineEdit`. Using this is much better UX than custom clear buttons or forcing users to backspace their search queries, especially for search/filter inputs. We need to ensure all search inputs have this enabled.
**Action:** Always enable `setClearButtonEnabled(True)` for any `QLineEdit` used as a search, filter, or easily-cleared input.
