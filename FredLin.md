[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 3/27 ~ 3/31

PTO at Fri.

### Devtools#Netmonitor.html

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive)
  - progress:
    - XUL to HTML (done) 
    - Performance improvement (WIP)
    - Refactor for running on browser tab (WIP)
      - remove chrome privillege API
      - wrap firefox specific code as module
      - tracked in [bug 1348737](https://bugzilla.mozilla.org/show_bug.cgi?id=1348737)
    - Host netmonitor.html on Github (The devtools repo will move to github at once)

- [devtools-core] add npm badges for all modules
  - landed

- Bug 1350219 - Bundle shared UI components into devtools add tree component into devtools-modules
  - landed

- Bug 1350219 - Bundle shared UI components into devtools-modules add search-box component into sham-modules
 - landed

- Set webpack alias to run with devtools-modules
  - merged in Bug 1350217

- Bug 1343774 - remove unused functions
  - r?

- Bug 1349415 - pass connection data into netmonitorController to run on both toolbar and browser tab
  - r?

- write netmonitor.html refactor post
https://blog.gasolin.idv.tw/2017/03/28/current-progress-of-netmonitor-html/

Review

- Bug 1350215 - Move store.js into utils/store.js
- Bug 1350215 - Move MC code into src/ and left panel.js, index.xhtml in top level
- Bug 1350235 - Support Copy submenu in the Context men
- Bug 1350217 - Introduce webpack.config.js

[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

