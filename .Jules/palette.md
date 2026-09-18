## 2026-09-18 - Add native clear buttons to QLineEdit search inputs
**Learning:** PySide6/Qt supports a native clear button within QLineEdit elements via `setClearButtonEnabled(True)`. Missing this attribute reduces accessibility and convenience, notably in search or filter inputs.
**Action:** Always enable the clear button (`setClearButtonEnabled(True)`) on `QLineEdit` text fields when used as search/filter boxes to provide consistent and efficient UX.
