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
- name: hasSourcePoint
  type: Select
  options:
    sourceType: ValuesList
    valuesList:
      "1": "start"
      "2": "end"
  path: ""
  id: f33291970
- name: hasTargetPoint
  type: Select
  options:
    sourceType: ValuesList
    valuesList:
      "1": "start"
      "2": "end"
  path: ""
  id: f292035199
- name: hasLowerBound
  type: Number
  path: ""
  id: f1456112782
- name: hasUpperBound
  type: Number
  path: ""
  id: f1925930552
- name: hasSource
  type: File
  options:
    dvQueryString: "dv.pages('#time/Interval or #operation/Mission or #operation/Activity or #operation/ActivityTemplate or #operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f569168165
- name: hasTarget
  type: File
  options:
    dvQueryString: "dv.pages('#time/Interval or #operation/Mission or #operation/Activity or #time/Point or #operation/ActivityTemplate or #operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f1770632586
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