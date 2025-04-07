---
version: "2.1"
limit: 20
mapWithTag: true
icon: layout-dashboard
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f499092503
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-567445985
- name: hasParameter
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f868322863
- name: instantiates
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-246883639
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---