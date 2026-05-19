## 2024-03-24 - QLineEdit Clear Button
**Learning:** In PySide6 applications with long lists, providing a way to quickly clear a search input improves keyboard/mouse flow significantly compared to holding backspace.
**Action:** Use `setClearButtonEnabled(True)` as standard practice for any QLineEdit acting as a filter or search bar.
