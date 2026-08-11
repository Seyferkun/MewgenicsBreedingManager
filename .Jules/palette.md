## 2025-03-01 - Add clear button to search/filter inputs

**Learning:** In PySide6 desktop applications, text input fields (QLineEdit) used for search or filtering can easily lack an intuitive way to clear the input, especially compared to native web inputs. Enabling the native clear button (`setClearButtonEnabled(True)`) provides immediate visual feedback and a one-click way to reset the filter, improving usability and reducing user friction.

**Action:** Whenever implementing a QLineEdit that serves as a search or filter field, always enable the clear button by calling `.setClearButtonEnabled(True)` to ensure a consistent and accessible experience across the application.