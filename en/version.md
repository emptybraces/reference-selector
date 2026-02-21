# Version
---
## 2.1.0
- [Selection History] Objects assigned as references are now automatically added to the Selection History, allowing quick re-access even if they were not directly selected.
- [Preferences] Added an option to automatically restore the previously selected object when opening a folder. This helps prevent the Inspector from unexpectedly switching to a folder view, reducing workflow interruptions.
- [Preferences] Migrated settings previously stored in EditorPrefs to a ScriptableObject-based system.
- [Preferences] Fixed an issue where some options were not visible in the Preferences window.

## 2.0.0
- Refactoring resulted in slight performance improvements.
- Updated all documentation and logo images.
- [Context Menu] Added a GetComponent action to the context menu.
- [Context Menu] Added Sibling actions to the context menu.
- [Context Menu] Updated the Hierarchy Tree action so that, when used during multi-object editing, references are searched within each selected object’s own hierarchy tree.
- [Inspector Menu] Changed the default shortcuts for Prev/Next actions to Shift + Mouse Wheel Down/Up.
- [Inspector Menu] Updated the appearance of Open History feature.
- [Inspector Menu] Added an option to open the Properties editor window by Ctrl + Click when selecting an item in Open History.
- [Inspector Menu] Added "Edit Preferences", "Editor Shortcuts", and "Version" to the right-side configuration button menu.
- [Preferences] Added a dedicated Reference Selector section.
- [Preferences] Added a maximum selection history count option.

## 1.0.2
- [Bugfix] Opening the context menu for a field in a specific generic class causes an exception.

## 1.0.1
- [Bugfix] There are specific cases where components with namespaces under UnityEngine cannot be retrieved.

## 1.0.0 
- First release
