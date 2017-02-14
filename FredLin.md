[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 2/2 - 2/10

### Devtools#Netmonitor.html

- Honza wil come to Taipei at 3/20~24 to discuss Netmonitor related plan 

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive), current project estimate finish release is `Fx55`
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]
  - Most of sidebar panels are landed

- 1308449 – Implement custom request view
  - r+ & landed
  - address nits
  - fix edit & send function
  - fix button style
  - fix tests
  - fix query params construction
  - use single updateRequest method to update all form values

- Bug 1337015 - show multiple select params correctly
  - r+ & landed

- Bug 1314921 - Reduce number of top-level files in devtools/client/netmonitor/
  - WIP
  - propose treatments

### Devtools#Debugger.html
  - Treat ltr as default and only render affected styles into rtl rules
    - [landed](https://github.com/gasolin/postcss-bidirection/issues/6)

Review

- Bug 1317645 - Implement NetworkDetailsPanel

### Firefox

- Curate a list of web extension resources
  - https://github.com/gasolin/awesome-webextension

[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

