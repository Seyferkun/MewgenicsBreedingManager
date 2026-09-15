## 2024-05-18 - QLineEdit UX Improvement
**Learning:** PySide6/Qt provides a built-in `setClearButtonEnabled` method that adds a native "clear" (x) button to text inputs, drastically improving UX for filtering operations across the app. This is frequently missed but provides massive value for very little effort.
**Action:** Always enable the clear button (`setClearButtonEnabled(True)`) when instantiating `QLineEdit` components intended for search/filtering.
