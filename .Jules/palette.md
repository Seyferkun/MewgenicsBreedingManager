## 2026-10-01 - Add Clear Buttons to Input Fields
**Learning:** For QLineEdits that act as search or filter fields in PySide6 interfaces, a clear button enables faster resetting of the field. This consistency significantly improves usability and accessibility since some search input widgets use it while others omitted it.
**Action:** Always enable the clear button (`setClearButtonEnabled(True)`) on QLineEdits meant for searching or filtering content within the application.
