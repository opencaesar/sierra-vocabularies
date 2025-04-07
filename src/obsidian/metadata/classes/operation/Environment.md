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
- name: isInvolvedIn
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f-108390506
- name: hasStateVariable
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f1263468979
- name: isContextFor
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Condition and !\"metadata/templates\"')"
  path: ""
  id: f-1849931420
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---