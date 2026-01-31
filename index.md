![img](../images/logo.jpg)
# Introduction
---
This asset was created to reduce drag-and-drop actions when assigning reference fields in the Unity Editor.<br>
It provides the following two main features.

## 1. Reference Field Assignment
---
You can open a context menu on almost any reference field and quickly assign reference objects from the selection history.<br>
The context menu includes the following options:

- `Selection History`: Assign any object from the selection history
- `Hierarchy Tree`: Assign objects from parent-child relationships
- `Nearest Sibling`: Assign objects from previous or next siblings at the same hierarchy level
- `Get Component`: Assign references by executing GetComponent-related methods
- `Recently Selected`: Assign recently selected objects that match the target type
- `Last Assigned`: Assign the last object set using this asset

![img](../images/intro1.png)

## 2. Selection History
---
The history of selected objects is stored, and an access button is displayed at the top of the Inspector.<br>
You can quickly access objects in the history using a dropdown list or shortcut keys.<br>
Additionally, you can open the Inspector window for a selected object by **Ctrl+clicking** it.

- `Shift + Mouse Wheel Down`: Select the previous object in the selection history.
- `Shift + Mouse Wheel Up`: Select the next object in the selection history.

(Shortcut keys can be customized from the Edit/Shortcuts window.)

![img](../images/intro2.jpg)

## 3. Support

- Full Undo support.
- Supports Domain Reload (safe to use during script recompilation).
- Supported Unity version: Unity 2022 or later.
- Compatible with Odin Inspector.
- Bug reports can be submitted here: <br>
　motose6★gmail.com<br>
　<https://github.com/emptybraces/reference-selector/issues>