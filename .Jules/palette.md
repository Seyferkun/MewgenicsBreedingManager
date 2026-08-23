## 2024-06-25 - Enable Clear Buttons on Search Inputs
**Learning:** Native clear buttons (`setClearButtonEnabled(True)`) provide a significant accessibility and UX win on desktop applications, allowing users to quickly wipe filters or search terms without repeatedly backspacing or selecting all text.
**Action:** When implementing `QLineEdit` fields used for searching or filtering, always ensure `setClearButtonEnabled(True)` is set alongside a helpful placeholder text.
