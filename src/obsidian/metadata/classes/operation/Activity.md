---
version: "2.1"
limit: 20
mapWithTag: true
icon: activity
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends:
savedViews: []
favoriteView:
fieldsOrder: []
fields:
- name: hasDrivingRequirement
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1883071369
- name: hasDerivedRequirement
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f1793444407
- name: hasAssumption
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f52007866
- name: involves
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#component/Component or #operation/Actor or #operation/Environment and !\"metadata/templates\"')"
  path: ""
  id: f425472754
- name: isImplementedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#function/Dataflow and !\"metadata/templates\"')"
  path: ""
  id: f1356519921
- name: isAnalyzedBy
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Scenario and !\"metadata/templates\"')"
  path: ""
  id: f1745804626
- name: hasConstraint
  type: File
  options:
    dvQueryString: "dv.pages('#condition/Condition or #state/Condition or #time/Condition and !\"metadata/templates\"')"
  path: ""
  id: f985868983
- name: contains
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1325057472
- name: isContainedBy
  type: File
  options:
    dvQueryString: "dv.pages('#operation/Activity or #operation/Mission and !\"metadata/templates\"')"
  path: ""
  id: f1320596534
- name: isInstanceOf
  type: MultiFile
  options:
    dvQueryString: "dv.pages('#operation/ActivityTemplate and !\"metadata/templates\"')"
  path: ""
  id: f748637828
- name: hasDescription
  type: Input
  path: ""
  id: f594177885
---