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
    dvQueryString: "dv.pages('#state/Condition or #condition/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f176322566
- name: hasDerivedRequirement
  type: File
  options:
    dvQueryString: "dv.pages('#state/Condition or #condition/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1736839396
- name: hasAssumption
  type: File
  options:
    dvQueryString: "dv.pages('#state/Condition or #condition/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1664451487
- name: involves
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Environment or #operation/Actor and !\"metadata/templates\"')"
  path: ""
  id: f841693359
- name: isImplementedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f939295694
- name: isAnalyzedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f2118598505
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#state/Condition or #condition/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f2138104681
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1751535873
- name: isContainedBy
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1718856547
- name: isInstanceOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f346864029
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---