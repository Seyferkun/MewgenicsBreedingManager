## 2024-06-25 - Search Input Usability
**Learning:** For PySide6 apps, `QLineEdit` fields used for filtering and searching often lack clear native ways to empty out the filter, which causes unnecessary repetitive keystrokes for users trying to clear long search strings.
**Action:** When reviewing PySide6 UIs with filtering options, identify all `QLineEdit` instances acting as search fields and ensure `setClearButtonEnabled(True)` is enabled to provide a native one-click clear button. Also make sure the purpose of the input is explicitly set using `setPlaceholderText`.
