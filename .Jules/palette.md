## 2025-02-12 - Added clear buttons to filter inputs
**Learning:** Adding `setClearButtonEnabled(True)` to QLineEdit fields used for filtering provides a native clear button "x" that makes quickly resetting searches much more intuitive without custom logic. Also, adding placeholder text helps users instantly understand the purpose of isolated inputs.
**Action:** When designing a search or filter input in PySide6, always enable `setClearButtonEnabled` and provide a helpful placeholder text by default to match native application expectations.
