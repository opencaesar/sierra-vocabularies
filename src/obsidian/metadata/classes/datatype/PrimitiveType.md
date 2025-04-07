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
  id: f-288439514
- name: hasQuantity
  type: Input
  path: ""
  id: f1589453125
- name: hasUnit
  type: Input
  path: ""
  id: f696976190
- name: hasDisplayUnit
  type: Input
  path: ""
  id: f1613071980
- name: hasMinimum
  type: Number
  path: ""
  id: f-1198042092
- name: hasMaximum
  type: Number
  path: ""
  id: f-1417840090
- name: hasPattern
  type: Input
  path: ""
  id: f1241296790
- name: isTypedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute or #state/Variable or #template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f-1432865321
- name: isTransmittedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f-1199521264
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---