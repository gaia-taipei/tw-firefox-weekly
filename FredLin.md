[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 4/5 ~ 3/14

- Build Firefox on Windows

### Devtools#Netmonitor.html

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive)
  - progress:
    - XUL to HTML (done) 
    - Performance improvement (WIP)
    - Refactor for running on browser tab (done)
      - remove chrome privillege API
      - wrap firefox specific code as module
      - tracked in [bug 1348737](https://bugzilla.mozilla.org/show_bug.cgi?id=1348737)
    - Host netmonitor.html on Github (The devtools repo will move to github at once)

- Bug 1343774 - remove unused functions
  - Update devtools-signed.xpi;
  - r+ & landed

- Bug 1352049 - Network panel documentation
  - r+ & landed
  - http://searchfox.org/mozilla-central/source/devtools/client/netmonitor/README.md

- write netmonitor.html refactor post
https://blog.gasolin.idv.tw/2017/03/28/current-progress-of-netmonitor-html/

- Do performance analysis on bug 1350969

- Bug 1356126 - Move column react component to separate files
  - r?

- Bug 1350227 - [Performance] fetch data when request is selected
  - WIP

Review

- Bug 1353535 - "Copy as cURL" can't copy POST without post data
- Bug 1350233 - Add [learn more] MDN link for statistics panel
- Bug 1350224 - Support for loading ContextMenu in Launchpad
- Bug 1350226 - Support for loading Editor in Launchpad
- Bug 1356146 - Link webpack alias to m-c shared
- [devtools-core] Match contextmenu onClick handler to the right menu item #333 

[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

