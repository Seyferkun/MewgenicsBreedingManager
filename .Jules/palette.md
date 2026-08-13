## 2024-05-24 - QLineEdit UX Consistency
**Learning:** PyQt/PySide6 QLineEdit elements used for filtering do not inherently show a clear button, leading to a suboptimal UX when quickly resetting searches. Adding setClearButtonEnabled(True) natively solves this and improves desktop accessibility.
**Action:** When creating text search or filter inputs, verify if setClearButtonEnabled(True) is enabled by default or needs explicit setting across all related views.
