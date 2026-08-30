## 2026-08-30 - PySide6 Clear Buttons on Inputs
**Learning:** Users often need to quickly clear search fields to reset list/table views in PySide6 applications. The native `setClearButtonEnabled(True)` method provides this out-of-the-box without needing custom icons or layouts.
**Action:** Use `setClearButtonEnabled(True)` on any QLineEdit serving as a search or filter input, and ensure these inputs always have descriptive placeholder text.
