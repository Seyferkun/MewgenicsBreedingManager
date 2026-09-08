## 2024-11-20 - Consistent clearable search fields
**Learning:** PySide6 provides a native `setClearButtonEnabled(True)` method on `QLineEdit` which gives users an easy way to clear search filters. Missing this on some search boxes created an inconsistent UX compared to other parts of the application.
**Action:** When adding or maintaining search or filter `QLineEdit` inputs in PySide6 applications, always ensure `setClearButtonEnabled(True)` is enabled and a helpful placeholder text is provided.
