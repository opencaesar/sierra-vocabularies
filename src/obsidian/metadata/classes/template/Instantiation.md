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
- name: binds
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f648327789
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
- name: hasSource
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f1870951843
- name: hasTarget
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1870951844
---