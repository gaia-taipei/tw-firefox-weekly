[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 11/14 - 11/18

Devtools

- netmonitor.html(deXUL netmonitor)
  - 2nd iteration starts(till Jan), current project estimate finish date is Fx56
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]

- JS performance
  - meeting with JS engineer and performance team(bobby, greg, kanru, thinker, fred, ricky) to gather a concrete pros & cons list of current tools, send the list to related people in devtools team

- Bug 1309496 - Set up enzyme testing framework for netmonitor
  - r+ & landed

- Bug 1314528 - [webconsole] enable mocha test on windows
  - r+ & landed

- Bug 1309866 - Migrate RequestsMenuView to a React component with Redux store
  - review the huge patch (3.3k+/2.8k-)
  - conduct Shako to setup the auto test environment to compare the load time between nightly and the target build

- Bug 1309185 - Copy HTTPi code into netmonitor/shared panel directory
  - study webconsole and netmonitor related code to integrate HTTP inspectors


[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor
