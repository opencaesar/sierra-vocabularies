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
    dvQueryString: "dv.pages('#function/Pin or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f847877830
- name: hasInput
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/InputPin and !\"metadata/templates\"')"
  path: ""
  id: f1016949677
- name: hasOutput
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f713429527
- name: isPerformedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Actor and !\"metadata/templates\"')"
  path: ""
  id: f1028304654
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#state/Condition or #condition/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f2138104681
- name: affects
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f544335954
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Pin or #function/Function or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f1755473825
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Pin or #function/Function or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f704254362
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---