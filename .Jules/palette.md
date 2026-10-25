## 2025-02-20 - Adding Clear Buttons to Search Inputs
**Learning:** For QLineEdit search fields in PySide6/Qt applications, not having a clear button can be frustrating for users making repetitive filter queries. Enabling `setClearButtonEnabled(True)` natively handles this without needing a custom button, creating a better micro-interaction. Also adding `setToolTip()` enhances the accessibility.
**Action:** Always enable `setClearButtonEnabled(True)` on QLineEdit widgets that function as search or filter fields, and ensure they have an accessible tooltip.
