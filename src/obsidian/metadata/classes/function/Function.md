---
version: "2.1"
limit: 20
mapWithTag: true
icon: square-function
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: hasPin
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f400250376
- name: hasInput
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/InputPin and !\"metadata/templates\"')"
  path: ""
  id: f136793352
- name: hasOutput
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f2079030265
- name: isPerformedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Actor and !\"metadata/templates\"')"
  path: ""
  id: f278255674
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f985868983
- name: affects
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f381355297
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f585943578
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f235956917
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---