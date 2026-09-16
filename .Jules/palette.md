## 2024-05-15 - Add Clear Button to QLineEdit Search Fields
**Learning:** For PySide6 QLineEdit search inputs, always enable the native clear button (`setClearButtonEnabled(True)`) and ensure a clear placeholder text is set. This improves the UX by providing users a simple, one-click action to clear their filters instead of forcing them to backspace through text.
**Action:** When implementing new search fields or auditing existing ones, automatically apply `setClearButtonEnabled(True)` along with appropriate placeholders to maintain a consistent and accessible UI.
