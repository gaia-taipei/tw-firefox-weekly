[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 3/20 ~ 3/24

### Devtools#Netmonitor.html

- Summary of Netmonitor.html workweek in Taipei
  - We have Prove-Of-Concept branches to prove we can run netmonitor on browser tab 🎉
  - We decide to stick on mozilla-central and use similar approach as inspector to run the netmonitor in a browser tab
  - We stopped Netmonitor.html phase I work immediately (convert XUL to HTML, MVP 100% completed)
  - We'll start Netmonitor.html phase II (To run Netmonitor on a browser tab, so we can debug Netmonitor with any browser's devtool) from this week
    - All phase II bugs are filed in [meta-bug]((https://bugzilla.mozilla.org/show_bug.cgi?id=1348737)), some low-hanging good-first-bugs are ready to grab
    - Have a meeting with jlaster, we'll land Netmonitor.html related share modules into `devtool-module`
  - We’ve triaged all new Netmonitor bugs 🐞
    - We agree that we should re-triage webconsole:http-inspector related bugs to Netmonitor
  - We also discussed about service-worker related UI and features with platform engineers, no recent plan from devtools team yet

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

* Create prove of concept branch to running netmonitor with browser tab
  - https://github.com/gasolin/devtools-core/tree/netmonitor.html/packages/netmonitor
  - just works

Bug 1343774 - remove unused functions
 - r?
 - port `waitForAllRequestsFinished` function to [devtools-performer](jsnajdr/devtools-performer) to work after bug 1343774 

Bug 1344158 netmonitor-controller 
 - r+ & landed PART 1: wrap webconsole;
 - r+ & landed PART 2: remove gNetwork and move getString to utils/client;

Bug 1349415 - pass connection data into netmonitorController to run on both toolbar and browser tab
 - r?

Bug 1031956 - "Copy as cURL" is building GET when it should be POST
 - mentor, r+ & landed

[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

