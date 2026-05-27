## 2024-05-24 - Consistent Search Input Clearing
**Learning:** Providing a native clear button on search/filter QLineEdits improves keyboard accessibility and provides a smoother UX compared to manual backspacing, which users expect in modern desktop apps.
**Action:** Always enable `setClearButtonEnabled(True)` on QLineEdit widgets used for search or filtering in PySide6.
