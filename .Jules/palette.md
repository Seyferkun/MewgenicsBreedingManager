## 2026-09-30 - [Add Clear Buttons to Search Inputs]
**Learning:** Missing clear buttons in PySide6 search and filter inputs forces users to manually delete text, which impacts UX and accessibility for users relying on keyboard navigation or single-click clearing.
**Action:** Always enable `setClearButtonEnabled(True)` on QLineEdit widgets that function as search or filter inputs to provide a native, accessible clear button.
