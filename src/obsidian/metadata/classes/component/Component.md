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
- name: inInvolvedIn
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Mission or #operation/Activity and !\"metadata/templates\"')"
  path: ""
  id: f1023378064
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1751535873
- name: isContainedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1718856547
- name: specializes
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1952087510
- name: isSpecializedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f252311693
- name: performs
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f915242686
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