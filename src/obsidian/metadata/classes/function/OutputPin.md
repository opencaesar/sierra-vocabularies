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
- name: isOutputOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f720414287
- name: isPinOf
  type: File
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f289931347
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f585943578
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f235956917
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---