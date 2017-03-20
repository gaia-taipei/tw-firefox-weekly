[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 3/13 ~ 3/17

### Devtools#Netmonitor.html

- Honza wil come to Taipei at 3/20~24 to discuss Netmonitor related plan 

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive), current project estimate finish release is `Fx55`
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]
  - **All MVP bugs completed**
  - come out the mimimum schedule for transition from the netmonitor.html project
  - progress:
    - XUL to HTML (done) 
    - Performance improvement (WIP)
    - Refactor for running on browser tab (WIP)
      - remove chrome privillege API
      - wrap firefox specific code as module
    - Host netmonitor.html on Github

- [Netmonitor UI analysis] (https://docs.google.com/document/d/1Z9J8uY4aGRB_BcsLKQCqwBaxXo9MuZEW3ClyVjQ2XfQ/edit)
  - arrange an moztw meeting time (3/22 7:30pm) for Honza

* Create prove of concept branch to running netmonitor with browser tab
  - fix dependencies
  - https://github.com/gasolin/devtools-core/tree/netmonitor.html/packages/netmonitor

Bug 1343774 - remove unused functions
 - r?
 - port `waitForAllRequestsFinished` function to [devtools-performer](jsnajdr/devtools-performer) to work after bug 1343774 

Bug 1344158 netmonitor-controller 
 - r? PART 1: wrap webconsole;
 - r? PART 2: remove gNetwork and move getString to utils/client;

Bug 987975 - edit and resend doesn't properly encode query string values
 - mentor

Bug 1220758 - "Open in New Tab" on POST requests makes a GET request
 - mentor
 
[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

