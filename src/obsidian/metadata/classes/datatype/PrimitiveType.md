---
version: "2.1"
limit: 20
mapWithTag: true
icon: terminal
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: hasScalar
  type: Input
  path: ""
  id: f915428269
- name: hasQuantity
  type: Input
  path: ""
  id: f471008441
- name: hasUnit
  type: Input
  path: ""
  id: f1525811075
- name: hasDisplayUnit
  type: Input
  path: ""
  id: f717375118
- name: hasMinimum
  type: Number
  path: ""
  id: f1474093281
- name: hasMaximum
  type: Number
  path: ""
  id: f1149279647
- name: hasPattern
  type: Input
  path: ""
  id: f687470912
- name: isTypedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute or #template/Parameter or #state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f1424969781
- name: isTransmittedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f899140474
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---