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
  id: f554502366
- name: hasTargetPoint
  type: Select
  options:
    sourceType: ValuesList
    valuesList:
      "1": "start"
      "2": "end"
  path: ""
  id: f1311222779
- name: hasLowerBound
  type: Number
  path: ""
  id: f118179373
- name: hasUpperBound
  type: Number
  path: ""
  id: f454047118
- name: hasSource
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/ActivityTemplate or #operation/Mission or #operation/Scenario or #time/Interval and !\"metadata/templates\"')"
  path: ""
  id: f623745299
- name: hasTarget
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/ActivityTemplate or #operation/Mission or #operation/Scenario or #time/Interval or #time/Point and !\"metadata/templates\"')"
  path: ""
  id: f170054822
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