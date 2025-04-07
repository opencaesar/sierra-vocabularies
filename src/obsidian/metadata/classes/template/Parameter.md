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
- name: isParamaterOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f1624210744
- name: isBoundBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#template/Instantiation and !\"metadata/templates\"')"
  path: ""
  id: f785894076
- name: hasType
  type: File
  options:
    dvQueryString: "dv.pages('#datatype/DataType or #datatype/PrimitiveType or #datatype/StructuredType and !\"metadata/templates\"')"
  path: ""
  id: f1119905006
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---