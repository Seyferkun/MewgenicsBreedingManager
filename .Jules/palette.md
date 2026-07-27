
## 2024-05-18 - QLineEdit Clear Button Accessibility
**Learning:** Standard search and filter inputs using `QLineEdit` in PySide6 do not provide an obvious way to clear their contents by default, which can be tedious for users repeatedly changing filters. Using `setClearButtonEnabled(True)` and providing a `setPlaceholderText` adds native, intuitive UX for clearing and identifying inputs.
**Action:** Always enable `setClearButtonEnabled(True)` and set a descriptive placeholder text on any `QLineEdit` intended for search or filtering to ensure consistent PySide6 UX and accessibility.
