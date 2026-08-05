## 2026-08-05 - PySide6 Search Inputs
**Learning:** PySide6 QLineEdit inputs used for search or filtering benefit significantly from having a native clear button enabled (`setClearButtonEnabled(True)`) and a helpful placeholder text. Some search inputs were missing these, which reduced the discoverability and usability of the filtering functionality.
**Action:** Always enable the native clear button on QLineEdit instances used for filtering/searching and ensure they have a descriptive placeholder text in PySide6 applications.
