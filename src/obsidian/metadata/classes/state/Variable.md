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
  id: f1570799194
- name: isAffectedBy
  type: File
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f378677941
- name: hasType
  type: File
  options:
    dvQueryString: "dv.pages('#datatype/DataType or #datatype/PrimitiveType or #datatype/StructuredType and !\"metadata/templates\"')"
  path: ""
  id: f696957172
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---