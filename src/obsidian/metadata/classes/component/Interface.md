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
- name: sendsTo
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Interface and !\"metadata/templates\"')"
  path: ""
  id: f656300466
- name: isPresentedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Actor and !\"metadata/templates\"')"
  path: ""
  id: f1436511877
- name: receivesFrom
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Interface and !\"metadata/templates\"')"
  path: ""
  id: f1338465248
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---