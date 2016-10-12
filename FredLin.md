[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 10/03 - 10/07

Devtools

- Bug 1292592 - sourceeditor uses xul
  - r+ & landed

- netmonitor.html(deXUL netmonitor)
  - Project summary in [Project document]
    - We'll refactor Net panel code base in steps while keeping TryHerder green(as opposed to the Console and Debugger panel which are being replaced by new versions).
    - We'll use Bugzilla for bug tracking, follow standard review process, use Marco’s project management process
    - Project Q4 goal will be
      - Replace XUL by HTML
      - Use React/Redux libraries for the infrastructure
      - Use existing HTTP Inspector code (Console panel)
      - Remove Chrome privileged API
      - Better harness for tests (React/Redux)
  - Daily meetings to share architecture analysis and breakdown tasks, see [Meeting Notes].  
  - Most of the [Task breakdown] process is complete, Bugs and followups are filed [Bug 1307743 - Migrate Net panel to HTML]
  - We'll meet with marco next week to setup the project management process

[Meeting Notes]: https://docs.google.com/document/d/1FneFiHkLMJjWFhFYI13IWlr02W5mCRsEqZQPUJHWmSU/edit#
[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Task breakdown]: https://docs.google.com/document/d/1NUiCCwDutuuNQhKXYnBFt28LX0qFIylgXwmxHeuRKtY/edit#
[Bug 1307743 - Migrate Net panel to HTML]: https://bugzilla.mozilla.org/show_bug.cgi?id=1307743
