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
  id: f1342950355
- name: isTypedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#datatype/Attribute or #state/Variable or #template/Parameter and !\"metadata/templates\"')"
  path: ""
  id: f610528703
- name: isTransmittedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f426436927
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---