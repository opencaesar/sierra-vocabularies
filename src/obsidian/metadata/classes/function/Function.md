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
  id: f-1224447845
- name: hasInput
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/InputPin and !\"metadata/templates\"')"
  path: ""
  id: f120350032
- name: hasOutput
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f-385762245
- name: isPerformedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Actor and !\"metadata/templates\"')"
  path: ""
  id: f1404654765
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f499092503
- name: affects
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f-1088975874
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f1979932102
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f-754516550
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---