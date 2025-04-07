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
- name: inInvolvedIn
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1023378064
- name: performs
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f915242686
- name: presents
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Interface and !\"metadata/templates\"')"
  path: ""
  id: f1172683408
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---