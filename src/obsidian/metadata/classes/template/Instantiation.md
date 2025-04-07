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
  id: f93742038
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
- name: hasSource
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f1735507246
- name: hasTarget
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1735507247
---