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
    dvQueryString: "dv.pages('#datatype/DataType or #datatype/PrimitiveType or #datatype/StructuredType and !\"metadata/templates\"')"
  path: ""
  id: f1052869571
- name: implements
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-915384400
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
- name: hasSource
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f1854238713
- name: hasTarget
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f1854238714
---