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
  id: f2020231820
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
- name: hasSource
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f1348532487
- name: hasTarget
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1348532488
---