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
  id: f-1105983278
- name: isExpressedIn
  type: Input
  path: ""
  id: f-1234608630
- name: hasContext
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Environment and !\"metadata/templates\"')"
  path: ""
  id: f-1311049291
- name: isDrivingRequirementOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1080572221
- name: isDerivedRequirementOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1163532967
- name: isAssumptionOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1266115532
- name: isConstraintOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #operation/Activity or #operation/ActivityTemplate or #operation/Mission or #operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f970460894
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---