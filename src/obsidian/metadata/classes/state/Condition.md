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
- name: hasExpression
  type: Input
  path: ""
  id: f153934394
- name: isExpressedIn
  type: Input
  path: ""
  id: f645785094
- name: hasContext
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Environment and !\"metadata/templates\"')"
  path: ""
  id: f1895303446
- name: isDrivingRequirementOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1431402332
- name: isDerivedRequirementOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f413374988
- name: isAssumptionOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1563229970
- name: isConstraintOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #operation/Activity or #operation/ActivityTemplate or #operation/Mission or #operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f282856838
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---