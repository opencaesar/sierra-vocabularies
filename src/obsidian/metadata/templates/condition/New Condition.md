---
tags:
  - condition/Condition
isDrivingRequirementOf:
isDerivedRequirementOf:
isAssumptionOf:
isConstraintOf:
hasDescription:
---
<%* 
title = await tp.system.prompt("Enter name", "", true);  
await tp.file.rename(title);
%># Tags
`= this.tags`

# Description
```meta-bind
INPUT[textArea(placeholder(Write description here)):hasDescription]
```