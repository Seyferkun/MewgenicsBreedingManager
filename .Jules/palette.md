## 2025-07-26 - Enable Clear Buttons in QLineEdit Search Fields
**Learning:** PySide6/Qt provides a built-in clear button functionality for `QLineEdit` via `setClearButtonEnabled(True)`, which significantly improves UX for search and filter inputs by allowing users to quickly clear their search queries. This is preferable to users having to manually select all and delete, making the UI more native-feeling and accessible.
**Action:** When adding or updating search/filter input fields (`QLineEdit`), ensure `setClearButtonEnabled(True)` is set alongside setting the placeholder text.
