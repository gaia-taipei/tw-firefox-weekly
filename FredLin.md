[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 5/23 ~ 5/27

[Site permissions]
- currently bug 1193006(Fred) and bug 1204007(Ricky) are workable
- Related CSS refactor is landed in Bug 1147981 - Cleanup doorhanger notification anchor ID & class duplication. Now discussion is going on bug 1274480 (svg sprite), other bugs should work after it land
- UX opened UI spec for comment on google doc (bug 1271868)

Firefox

- [devtool] Bug 1266415 - about:debugging should display a warning if service workers are disabled
  - r+ & landed

- Bug 1273023 - Convert xpcshell-tests in toolkit/components/places/tests/bookmarks/test_385829.js to Bookmarks.jsm API
  - r+

- Bug 1256767 - Fix ESLint errors/warnings in devtools/client/webconsole/console-commands.js
  - r+

- Bug 1275100 - browser_notifications_2.js is going to permafail when Gecko 49 merges to Aurora
  - r+

- [CC] Bug 1193006 - Show icons next to non-default permissions in the Permissions section of the Control Center
  - wait for bug 1274480

- Bug 1174900 - Capture doorhanger password field should stay disabled for master password users
  - WIP

- Bug 1275145 - Convert xpcshell-tests in toolkit/components/places/tests/bookmarks/test_388695.js to Bookmarks.jsm API
  - mentor bug


WebVR

- hold WebVR workshop at 5/28 moz community space
- create slide https://docs.google.com/presentation/d/1qbHbSgkAA0byhkWtJh9-KxyLkvYDLzVdTD2UTFn4hww/edit#slide=id.g141d63d176_0_119 & 3 labs https://github.com/gasolin/webvrdemo/wiki
