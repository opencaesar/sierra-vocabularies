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
  id: f155991388
- name: hasQuantity
  type: Input
  path: ""
  id: f443809178
- name: hasUnit
  type: Input
  path: ""
  id: f1280119856
- name: hasDisplayUnit
  type: Input
  path: ""
  id: f695389632
- name: hasMinimum
  type: Number
  path: ""
  id: f853510986
- name: hasMaximum
  type: Number
  path: ""
  id: f1647067757
- name: hasPattern
  type: Input
  path: ""
  id: f97551991
- name: isTypedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute or #state/Variable or #template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f610528703
- name: isTransmittedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f426436927
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---