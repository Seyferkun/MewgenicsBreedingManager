## 2026-06-25 - [Consistent Native Clear Buttons and Placeholder Text for Search Inputs]
**Learning:** [PySide6 `QLineEdit` widgets lack an automatic way to clear out the text after it is entered, and omitting context/placeholder text fails to convey intent for keyboard/screen-reader users]
**Action:** [Always append `setClearButtonEnabled(True)` to enable the native PySide6 clear icon for fast text clearing on filter/search widgets and assign `setPlaceholderText()` if none exists to aid user context]
