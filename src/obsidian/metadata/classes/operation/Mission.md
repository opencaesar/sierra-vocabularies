---
version: "2.1"
limit: 20
mapWithTag: true
icon: rocket
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: hasDrivingRequirement
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f170676790
- name: hasDerivedRequirement
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1310426656
- name: hasAssumption
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f-345291643
- name: involves
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Actor or #operation/Environment and !\"metadata/templates\"')"
  path: ""
  id: f636733270
- name: isImplementedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f698794991
- name: isAnalyzedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f1232767961
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f499092503
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-567445985
- name: isContainedBy
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-1202413408
- name: isInstanceOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f-1221670378
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---