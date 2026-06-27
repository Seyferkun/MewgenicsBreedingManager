## 2024-03-24 - Consistent clear actions for search
**Learning:** PySide6 QLineEdits have a built-in clear button option which many of the application's search inputs weren't utilizing, resulting in a suboptimal user experience where text had to be manually deleted. Adding placeholders using `_tr` with a default parameter ensures that strings display even if translation bundles are missing or fail to load.
**Action:** When working on PySide6 apps, systematically apply `setClearButtonEnabled(True)` and default string fallbacks to search and filter `QLineEdit` elements.
