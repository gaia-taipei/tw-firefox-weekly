## 08/01 ~ 08/05 ##

* [Firefox]
  - Dev Tools
    - Bug 1289912 - Can't scroll in JSON Viewer in Nightly, landed
    - Bug 1284838 - Reps: render events more uniformly, review?
      - Updated patch for the review comments, still on review process.
    - Bug 1288854 - Pressing "escape" to cancel the eye dropper does not always cancel it
      - Duplicate of Bug 1289433.
    - Bug 1289062 - Order the Event's properties
      - Discussed the interesting Event rep's properties with reviewer(Honza).
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - Traced code to prepare write patch for the bug. Will write patch this week.
    - Bug 1282367 - Location bar detects anything with a dot as a URL
      - Duplicate of bug 1256074
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - Sent try pushes and get some test failures. Will figure out it this week.
