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
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-1024439129
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f499092503
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---