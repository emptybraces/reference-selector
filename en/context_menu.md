## Custom Context Menu
---
By right-clicking on a reference field, you can open the custom Reference Selector menu.<br>
It supports not only standard reference fields, but also array and list fields.

![img](../images/context_menu1.png)

## Selection History 
---
You can assign any object from the selection history as a reference.<br>
Only objects whose types are assignable to the target reference field are displayed.

![img](../images/context_menu2.jpg)

## Hierarchy Tree
---
Searches for and assigns objects of the same type as the target reference field from parent, child, and sibling objects in the hierarchy.<br>
When multiple objects are selected, the process is performed individually for each object.<br>
For non-active objects, the search is also performed based on their respective positions in the hierarchy.<br>
If no matching object is found, the reference is set to null.

![img](../images/context_menu3.jpg)

## Nearest Siblings
---
Searches through preceding and following sibling objects in the same hierarchy level until an object of the same type as the reference field is found.<br>
Allows bidirectional copying of references between the nearest matching objects.<br>
Supports array fields, and when multiple objects are selected, the process is performed individually for each object.

![img](../images/context_menu4.png)

## Get Component
---
Executes operations equivalent to the GetComponent family of APIs directly within the editor.<br>
Supports array fields, and when multiple objects are selected, the process is performed individually for each object.

![img](../images/context_menu5.png)

## Recently Selected
---
Automatically assigns the most recently assignable reference object from the Selection History.

## Last Assigned
---
Reassigns the reference object that was most recently assigned via the Reference Selector menu.

