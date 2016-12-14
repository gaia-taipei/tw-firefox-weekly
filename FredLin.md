[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 11/28 - 12/09

### Hawaii all hands
* Netmonitor meetup on Thurday
  - Main goal for 2017 Q1 is finishing the de-XUL related tasks and moving codebase to Github for easier contribution
  - Further goal is improve netmonitor's response speed to chrome's level
* Rewrite [postcss-bidirection](https://github.com/gasolin/postcss-bidirection) plugin (which was written during Jsconf.asia 2015 last year) to help debugger.html deal with cross-browser RTL support
  - with `postcss-bidirection`, CSS draft syntax like `margin-inline-start` will be failback to `margin-left`/`margin-right` with `dir="ltr"` prefix
  - debugger.html postcss loader [PR](https://github.com/devtools-html/debugger.html/pull/1419) is on the way

* Had a discussion with Greg Tatum about performance related tool status
  - He had rewritten Cleopatra, Trace Logger, and is planning to rewrite new devtools performance tool, all with react + redux
  - The UX involvement is limited now (may need TDC help?)
  - (from Bobby) Hasai project will hold a workweek in Jan, at Taipei, who(from devtools team) will come to Taipei is not confirmed yet


### Devtools

- netmonitor.html(deXUL netmonitor)
  - [Fx52 on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive), current project estimate finish release is Fx56
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]

- Bug 1317649 - Implement Cookies Panel
  - WIP
  - implemented cookies filter with redux
  - migrated net-group-list/net-params components from webconsole, consider using debugger.html accordion instead

[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor
