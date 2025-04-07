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
  id: f-199940293
- name: hasTargetPoint
  type: Select
  options:
    sourceType: ValuesList
    valuesList:
      "1": "start"
      "2": "end"
  path: ""
  id: f2095093637
- name: hasLowerBound
  type: Number
  path: ""
  id: f1889553719
- name: hasUpperBound
  type: Number
  path: ""
  id: f-1001292746
- name: hasSource
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/ActivityTemplate or #operation/Mission or #operation/Scenario or #time/Interval and !\"metadata/templates\"')"
  path: ""
  id: f-276755627
- name: hasTarget
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/ActivityTemplate or #operation/Mission or #operation/Scenario or #time/Interval or #time/Point and !\"metadata/templates\"')"
  path: ""
  id: f-261155637
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