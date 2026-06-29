## 2026-06-29 - Native Clear Buttons in QLineEdit
**Learning:** In PySide6 (and Qt generally), `QLineEdit` provides a native, integrated clear button via `setClearButtonEnabled(True)`. It's a low-effort, high-impact a11y/UX pattern that is easy to overlook, often resulting in inconsistent search and filter experiences across different views within the same application.
**Action:** Audit and ensure `setClearButtonEnabled(True)` is consistently applied to all search/filter input fields across all application views.
