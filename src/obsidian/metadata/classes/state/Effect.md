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
- name: hasFunction
  type: Input
  path: ""
  id: f471725157
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
- name: hasSource
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f921591268
- name: hasTarget
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f921591269
---