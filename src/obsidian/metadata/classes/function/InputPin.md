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
- name: isInputOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f1422365167
- name: isPinOf
  type: File
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f1639481770
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Pin or #function/Function or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f1755473825
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Pin or #function/Function or #function/InputPin or #function/OutputPin and !\"metadata/templates\"')"
  path: ""
  id: f704254362
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---