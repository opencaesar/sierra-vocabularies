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
  id: f1777377283
- name: isBoundBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#template/Instantiation and !\"metadata/templates\"')"
  path: ""
  id: f1463130439
- name: hasType
  type: File
  options:
    dvQueryString: "dv.pages('#datatype/StructuredType or #datatype/PrimitiveType or #datatype/DataType and !\"metadata/templates\"')"
  path: ""
  id: f1423283015
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---