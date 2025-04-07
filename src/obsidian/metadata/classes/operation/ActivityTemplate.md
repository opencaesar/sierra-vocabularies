---
version: "2.1"
limit: 20
mapWithTag: true
icon: layout-dashboard
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
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
- name: hasParameter
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f1556609176
- name: instantiates
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f2009895080
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---