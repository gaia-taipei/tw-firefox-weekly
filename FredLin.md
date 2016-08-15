[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 8/8 ~ 8/12

Devtools

- tab motion design (PLAN)
  - helen (UX) sad she most wanted it than box-model view (Bug 1150496)
  - tabbar redesign bugs https://bugzilla.mozilla.org/buglist.cgi?quicksearch=%5Bdevtools-toolbar%5D&list_id=13146931

- integrate new web console with rep (PLAN)
  https://github.com/devtools-html/gecko-dev/issues/195#issuecomment-239498136

- Bug 1265759 - Create an HTML replacement for Search Box
  - r+ & landed

- Bug 1286259 - Reps: grip-array rep should support limited preview
  - r+

- Bug 1293591 - remove devtools/client/inspector/inspector.css
  - r+ & landed

- Bug 1291638 - change color theme of box-model view
  - feedback?

- Bug 1294486 - Fix inspector textbox-search-clear position in RTL locales
  - r?

- reproduce issue on linux and mac in Bug 1294480 - inspector-searchbox focus behavior is gone
  - identify its a windows only bug


Toolkit

- Bug 1190938 - "SHOW" disappearing & password field staying selected under doorhanger
    - f?

- Bug 1272849 - skip browser_notifications_2.js on linux to avoid Intermittent
  - r-, origin repo has skip=linux sentence for this tests; My previous patch removed them because I can successfully run tests on linux and treeherder, but now it occationally cause intermittent. So I'd rather add skip=linux to skip the test on linux
