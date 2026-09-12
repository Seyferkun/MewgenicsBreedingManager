## 2026-09-12 - Native Clear Buttons in QLineEdit
**Learning:** PySide6's QLineEdit has a built-in `setClearButtonEnabled(True)` method which automatically adds a native clear button (an 'x' icon) when the input contains text. This is a simple, standardized way to improve UX for search and filter fields without custom widgets or layouts.
**Action:** Always enable `setClearButtonEnabled(True)` on any QLineEdit used for searching or filtering to provide a quick way for users to clear their input and reset the filter state.
