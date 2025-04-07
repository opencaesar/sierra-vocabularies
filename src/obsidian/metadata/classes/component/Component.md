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
- name: isInvolvedIn
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f489400367
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1325057472
- name: isContainedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1320596534
- name: specializes
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f299621181
- name: isSpecializedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1790433844
- name: performs
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f1593369035
- name: hasStateVariable
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f1088100482
- name: isContextFor
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#state/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1245310086
- name: presents
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Interface and !\"metadata/templates\"')"
  path: ""
  id: f2052577913
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---