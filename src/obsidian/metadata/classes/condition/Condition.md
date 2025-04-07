---
version: "2.1"
limit: 20
mapWithTag: true
icon: 
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: isDrivingRequirementOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1789758585
- name: isDerivedRequirementOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f2062456460
- name: isAssumptionOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1711080900
- name: isConstraintOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #function/Function or #operation/Activity or #operation/ActivityTemplate or #operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f1609375631
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---