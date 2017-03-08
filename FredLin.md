[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 2/20 - 3/3

### Devtools#Netmonitor.html

- Honza wil come to Taipei at 3/20~24 to discuss Netmonitor related plan 

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive), current project estimate finish release is `Fx55`
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]
  - **All MVP bugs completed**
  - progress:
    - XUL to HTML (done) 
    - Performance improvement (WIP)
    - Refactor for running on browser tab (WIP)
      - remove chrome privillege API
      - wrap firefox specific code as module
    - Host netmonitor.html on Github

- [Netmonitor UI analysis] (https://docs.google.com/document/d/1Z9J8uY4aGRB_BcsLKQCqwBaxXo9MuZEW3ClyVjQ2XfQ/edit)
  - triage bugs till bug 1020281 (2009~2013)
  - add UI improvement proposals
    - list tooltip reorg
    - custom request UI validation
    - Raw Headers
    - Service worker integration
    - Cookie management
    - Timing Panel
    - Headers Panel Improvements

- make netmonitorController refactor proposal
  - we'll wrap firefox specific code as module

- Bug 1316291 - Rename the "requests-menu" CSS classes in netmonitor.css
  - PART 1:Rename the requests-menu CSS classes in netmonitor.css
  - PART 2:remove request-list elements with fixed IDs
  - PART 3:Remove toolbar elements with fixed IDs
  - r+ & landed

Bug 1340464 - handle connection state in util/client
 - trace debugger.html code to have similar call path
 - PART 1: wrap init process into bootstrap function;
 - PART 2: handle connection state in util/client
 - r+ & landed

Bug 1341975 - fix Regression: empty list UI is broken
 - r+ & landed

Bug 1343122 - support multiple params with same name
 - r+ & landed
 - uplift to aurora

Bug 1343774 - remove unused functions
 - r?

Bug 987975 - edit and resend doesn't properly encode query string values
 - mentor

Review

Bug 1323454 - Network panel: integrate HTTP Status code with MDN
  * mentor bug
  * r+ & landed

Bug 1308441 - Use react-virtualized for RequestList in NetMonitor panel

Bug 1338386 - Make it clear if request comes from the browser cache

[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

