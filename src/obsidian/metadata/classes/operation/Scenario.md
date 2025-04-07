---
version: "2.1"
limit: 20
mapWithTag: true
icon: file-text
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: analyzes
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1931073515
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#state/Condition or #condition/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f2138104681
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---