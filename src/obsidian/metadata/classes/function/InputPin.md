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
  id: f1375067831
- name: isPinOf
  type: File
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f2068076354
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f1979932102
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function or #function/InputPin or #function/OutputPin or #function/Pin and !\"metadata/templates\"')"
  path: ""
  id: f-754516550
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---