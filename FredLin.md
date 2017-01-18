[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 1/9 - 1/13

### Devtools

- Quantum flow workweek
  - setup Cleopatra and devtool addon to test performance https://github.com/jsnajdr/devtools-performer
  - updates:
    - (Bryan) said Quantum flow related support is p0 for devtools
    - (Greg) The improvement will be done on cleopatra, and it will replace devtools performance panel (sometime)
    - (Jim) Devtools will share same Chrome Remote Debugging Protocol with Servo (sometime this year)

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive), current project estimate finish release is `Fx55`
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]
  - Most of sidebar panels are landed

- Bug 1317649 - Implement Cookies Panel
  - r+ & landed
  - apply properties-view on cookies panel
  - show cookies object properties
  - fix tests

- 1308449 – Implement custom request view
  - f?
  - use thunk to handle sendHTTPRequest
  - use flex layout for all side panels and statistics view (instead of -moz-box)

[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

