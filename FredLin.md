[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 4/17 ~ 4/21

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

- write netmonitor.html refactor post
https://blog.gasolin.idv.tw/2017/03/28/current-progress-of-netmonitor-html/

- Do performance analysis on bug 1350969

- Bug 1356126 - Move column react component to separate files
  - r+ & landed

- Bug 1356957 use promise.all to fetch request data in parallel
  - r?

- Bug 1356957 - combine double updateRequest call while receive event in _onNetworkEventUpdate
  - WIP

Review

- [devtools-core] Remove unused moudles
- [launchpad] fix menus
- Bug 1349173 - Use div table layout to reduce reflow
- Bug 1357447 - Lock down devtools-core package

[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

