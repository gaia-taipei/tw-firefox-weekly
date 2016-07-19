## 07/11 - 07/15 ##

### Last week
* [Firefox]
  - Setup development environment
    - Fixed the try problems: cannot push try
      - Bug 1286200 - Request hg access be restored
    - Made a new repo[1] to share documents and config files for new guys
  - Watch Location Bar module
    - Bug 647162 - Location Bar does not update
      - RESOLVED WORKSFORME
  - Dev Tools
    - Bug 1282791 - Reps: uninteresting props algorithm is wrong
      - Fixed the uninteresting props issue
      - Fixed the max number issue
    - Rep Tester[2]
      - Be a collaborator of Rep Tester
      - Issue 1 for prototypes - Add config file to config mozilla-central and devtools paths[3], landed
      - Issue 1 for rep-tester - Remove Source Directory Structure section[4], landed
      - Filed new bugs
        - Issue 2 - Need to run `npm install` twice to install all dependency modules
        - Issue 3 - Improve the process of running Rep Tester

* [SensorWeb]
  - Bug 1286142 - Update contributor list

### This week
* [Firefox]
  - Dev Tools
    - Help taipei members understand how to use Rep Tester
    - Bug 1282791 - Reps: uninteresting props algorithm is wrong
      - Fix the order issue[5]
    - Bug 1276376 - Reps: uninteresting props are not filtered correctly
  - Watch Location Bar module and look for bugs to fix
  - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1

[1]: https://github.com/evanxd/firefox-newbie
[2]: https://github.com/janodvarko/rep-tester
[3]: https://github.com/janodvarko/prototypes/pull/2
[4]: https://github.com/janodvarko/rep-tester/pull/4
[5]: https://bugzilla.mozilla.org/show_bug.cgi?id=1282791#c2
