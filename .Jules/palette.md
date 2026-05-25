## 2024-05-18 - Native Clear Buttons in PySide6
**Learning:** In PySide6, `QLineEdit` inputs used for searching or filtering should almost always use `.setClearButtonEnabled(True)` to provide a native, standard clear button ("X") to quickly reset the filter state, which is a significant accessibility and UX improvement over requiring manual deletion.
**Action:** Whenever introducing or reviewing a `QLineEdit` intended for search/filter functionality, ensure `setClearButtonEnabled(True)` is applied.
