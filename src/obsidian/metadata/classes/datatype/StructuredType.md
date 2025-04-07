---
version: "2.1"
limit: 20
mapWithTag: true
icon: book-plus
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: hasAttribute
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute and !\"metadata/templates\"')"
  path: ""
  id: f-1073052382
- name: isTypedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute or #state/Variable or #template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f-1432865321
- name: isTransmittedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f-1199521264
- name: hasDescription
  type: Input
  path: ""
  id: f-1825843966
---