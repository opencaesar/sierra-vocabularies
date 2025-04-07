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
  id: f1742067114
- name: isTypedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute or #template/Parameter or #state/Variable and !\"metadata/templates\"')"
  path: ""
  id: f1424969781
- name: isTransmittedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f899140474
- name: hasDescription
  type: Input
  path: ""
  id: f1582917706
---