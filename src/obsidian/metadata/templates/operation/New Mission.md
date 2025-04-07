---
tags:
  - operation/Mission
hasDrivingRequirement:
hasDerivedRequirement:
hasAssumption:
involves:
isImplementedBy:
isAnalyzedBy:
hasConstraint:
contains:
isContainedBy:
isInstanceOf:
hasDescription:
---
<%* 
title = await tp.system.prompt("Enter name", "New Mission", true);  
await tp.file.rename(title);
%># Tags
`= this.tags`

# Description
```meta-bind
INPUT[textArea(placeholder(Write description here)):hasDescription]
```

# Template
Specify an activity template that  this mission is based on:
```dataview
TABLE WITHOUT ID file.link as "ActivityTemplate"
FROM #operation/ActivityTemplate 
WHERE this.isInstanceOf = file.link
```
# Driving Requirements
List the driving requirements for this mission:
```dataview
TABLE WITHOUT ID file.link as "Requirement"
FROM #condition/Condition or #time/Condition or #state/Condition 
WHERE contains(isDerivingRequirementOf, [[]])
```

`BUTTON[driving-requirement-condition]`

```meta-bind-button
label: New Requirement
icon: ""
hidden: true
class: ""
tooltip: Adds a new Requirement
id: driving-requirement-condition
style: primary
actions:
  - type: templaterCreateNote
    templateFile: metadata/templates/condition/New Condition.md
    folderPath: data/operational/conditions
    fileName: New Requirement
    openNote: true
    openIfAlreadyExists: true
```

```dataviewjs
const button = dv.el('button', 'New Requirement');
const templateContents = await app.vault.read(app.vault.getAbstractFileByPath("metadata/templates/operation/New Mission.md"));
button.onclick = () => { 
  app.vault.create("data/temp.md", templateContents);
}; 
button
```