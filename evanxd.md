## 08/22 ~ 08/26 ##

* [Firefox]
  - QX
    - Added into QX list
      - Bug 260611 - leave bookmarks menu open when I middle click or ctrl click a bookmark
      - Bug 565567 - FF should ask for confirmation before quitting with Cmd-Q (only on Mac)
      - Will move the above issues into Bug 1270272
    - Duplicate of another issue
      - Bug 565566 - Support opening in new windows when qualifiers are active for form submits and searches
    - Closed the invalid issues
      - Bug 444080 - "Lost" bookmarks falling into the unsorted bookmarks blackhole
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - After investigated, we could add two `richlistitem` elements(moz-action:visiturl and moz-action:searchengine ones) on the `#PopupAutoCompleteRichResult` panel when the `moz-action` is `visiturl`.
      - feedback?
      - ui-review?
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - Somehow `login.username` is `null` so the intermittent failures happen. Need to continue to figure out why `login.username` is null here.
  - Dev Tools
    - Bug 1289062 - Order the Event's properties
      - landed
