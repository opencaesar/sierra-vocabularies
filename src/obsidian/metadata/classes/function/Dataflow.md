---
version: "2.1"
limit: 20
mapWithTag: true
icon: arrows-up-down
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: transmits
  type: File
  options:
    dvQueryString: "dv.pages('#datatype/StructuredType or #datatype/PrimitiveType or #datatype/DataType and !\"metadata/templates\"')"
  path: ""
  id: f1143515908
- name: implements
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1285057171
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
- name: hasSource
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Pin or #function/Function or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f926469854
- name: hasTarget
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Pin or #function/Function or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f926469855
---