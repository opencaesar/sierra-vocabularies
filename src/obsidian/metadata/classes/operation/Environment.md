---
version: "2.1"
limit: 20
mapWithTag: true
icon: orbit
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: inInvolvedIn
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1023378064
- name: hasStateVariable
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f1178292347
- name: isContextFor
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1259877664
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---