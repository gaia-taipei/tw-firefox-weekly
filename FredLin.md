[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 4/18 ~ 4/22

Firefox

- Update [workflow of Mozilla Gecko project](http://blog.gasolin.idv.tw/2016/04/the-newbies-workflow-on-mozilla-gecko.html)

- Bug 1262639 - Fix NS_ERROR_ILLEGAL_VALUE spam by not run getLivemark without valid node id
  - r+ & landed

- Bug 1011023 - Simplify test_bookmarks_restore_notification.js to use add_task
  - add notification observer check via promiseTopicObserved
  - r+

- Bug 1256772 - eslint fix for devtools/client/webconsole/jsterm.js
  - r?
  - Fix issues & complexity with new ESLint setting
- Bug 1256767 - [ESLint] Fix ESLint errors/warnings in devtools/client/webconsole/console-commands.js
  - r?

- Bug 1217134 - Replace show password placeholder with conventional show password checkbox
  - WIP
  - fix tests
  - identify null username test case as a separate bug

- Sent & reply apply webby concept on Firefox and Mobile with Mark Finkle
