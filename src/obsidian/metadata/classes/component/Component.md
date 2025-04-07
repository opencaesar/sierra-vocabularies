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
  id: f-108390506
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f-567445985
- name: isContainedBy
  type: File
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f-1202413408
- name: specializes
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f-871772712
- name: isSpecializedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component and !\"metadata/templates\"')"
  path: ""
  id: f1913446134
- name: performs
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Function and !\"metadata/templates\"')"
  path: ""
  id: f431162674
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