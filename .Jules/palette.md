## 2024-10-19 - Standardize Search Clear Buttons
**Learning:** PySide6's QLineEdit supports a native, accessible clear button via `setClearButtonEnabled(True)`. Without it, users must manually select and delete text to reset searches/filters, which is cumbersome and less accessible.
**Action:** Always enable the native clear button on QLineEdit widgets used as search or filter inputs, and ensure they have a helpful placeholder text.
