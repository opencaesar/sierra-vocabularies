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
- name: isStateVariableOf
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Environment and !\"metadata/templates\"')"
  path: ""
  id: f137120313
- name: isAffectedBy
  type: File
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f1012256555
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