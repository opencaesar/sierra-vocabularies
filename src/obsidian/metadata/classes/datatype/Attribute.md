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
- name: isAttributeOf
  type: File
  options:
    dvQueryString: "dv.pages('#datatype/StructuredType and !\"metadata/templates\"')"
  path: ""
  id: f1901607445
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