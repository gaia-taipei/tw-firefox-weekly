[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 7/18 ~ 7/22

Devtools

- motion design (PLAN)
  - talk with UX(Helen, Fang) and they said switch panel is ready
  - check codebase and found XUL does not support animation...
  - will followup the possible works

- [meta] bug 1288400 Create React component for inspector side panels
  - hold study meeting to trace devtools sidebar react
  - create proposal Bug 1288347 - inspector toolsidebar: add addPanelTab method to load react panel
    - feedback+
    - will not continue soon since its not in MVP scope

- Bug 1285449 - Firebug theme - Don't apply inverted filter for sidebar-toggle, rewind-timeline, pause-resume-timeline in Inspector
  - r+ & landed

- Bug 1279526 - Firebug theme: fix CSS for rule view property
  - r+ & landed

- Bug 1264686 - Reps: Use grip-array rep to display NamedNodeMap
  - r+ & landed

- Bug 1278774 - Breadcrumbs overlaps on the element hiding helper button
  - ask addon developer change the style
  - mark as invalid

- Bug 1287371 - Tabs hover style was changed in firebug theme
  - investigate the cause

- Bug 1286259 - Reps: grip-array rep should support limited preview
  - WIP


Firefox

- [CC] Bug 1206233 - Indicator for devices actively streaming or permissions being used
  - reviewer taken the bug
