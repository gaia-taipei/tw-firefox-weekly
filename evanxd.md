## 09/05 - 09/09 ##

* [Firefox]
  - QX
    - Searching for bugs
      - Finished the cuts-os[1] meta bug.
      - Added into QX list
        - Bug 566526 - Firefox doesn't relocate to the connected screen on Mac
    - Bug 612228 - Move Reload/Bookmark All Tabs to the List All Tabs menu
      - ui-review?
      - feedback?
    - Bug 565567 - FF should ask for confirmation before quitting with Cmd-Q (only on Mac)
      - ui-review?
      - review?
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - After investigated, we could add two `richlistitem` elements(moz-action:visiturl and moz-action:searchengine ones) on the `#PopupAutoCompleteRichResult` panel when the `moz-action` is `visiturl`.
      - ui-review?
      - review?
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - review?

[1]: https://bugzilla.mozilla.org/show_bug.cgi?id=565518
