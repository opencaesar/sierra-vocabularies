---
version: "2.1"
limit: 20
mapWithTag: true
icon: user
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
- name: performs
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f431162674
- name: presents
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Interface and !\"metadata/templates\"')"
  path: ""
  id: f-1276666088
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---