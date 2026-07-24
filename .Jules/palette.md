## 2024-05-18 - Missing Clear Buttons on Search Inputs
**Learning:** PySide6 QLineEdit inputs used for searching and filtering often lack native clear buttons, reducing accessibility and adding friction when users need to clear queries quickly.
**Action:** Always enable the clear button (`setClearButtonEnabled(True)`) on QLineEdit components that are used as search or filter inputs.
