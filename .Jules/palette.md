## 2024-05-24 - Cross-cutting QLineEdit enhancements
**Learning:** Adding clear buttons to Qt text inputs drastically improves UX on search and filter elements but is frequently overlooked since it defaults to disabled. Setting good placeholder text is equally important.
**Action:** Audit and enforce `setClearButtonEnabled(True)` + `setPlaceholderText` on all Qt `QLineEdit` used for filtering and search across the app.
