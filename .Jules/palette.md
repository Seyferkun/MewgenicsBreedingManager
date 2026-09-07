## 2026-09-07 - Consistent native clear buttons for PySide6 filter inputs
**Learning:** PySide6 provides a native clear button functionality on QLineEdits which improves usability and accessibility for filter/search inputs, but it must be manually enabled via `setClearButtonEnabled(True)`. Applying it inconsistently across a desktop app results in poor user experience.
**Action:** When adding or auditing QLineEdit search/filter inputs, ensure `setClearButtonEnabled(True)` is consistently enabled across all such fields to improve filter usability without the need for custom buttons.
