## 09/12 - 09/14 ##

* [Firefox]
  - QX
    - Bug 612228 - Move Reload/Bookmark All Tabs to the List All Tabs menu
      - RESOLVED WONTFIX
        - After discussion, Philipp and Stephen think we should keep "Reload/Bookmark All Tabs" items on the context menu.
    - Bug 565567 - FF should ask for confirmation before quitting with Cmd-Q (only on Mac)
      - ui-review?
        - Updated patched for Philipp's comments
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - After investigated, we could add two `richlistitem` elements(moz-action:visiturl and moz-action:searchengine ones) on the `#PopupAutoCompleteRichResult` panel when the `moz-action` is `visiturl`.
      - ui-review?
        - Discussed the UI changes with Stephen
        - Waiting for his response
      - review?
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - landed
  - Intermittent test failures
    - Bug 1302352 - browser_context_menu_iframe.js is skipped in e10s
      - landed
    - Bug 1192800 - Intermittent browser_context_menu.js | Uncaught exception - at :0 - Error: operation not possible on dead CPOW
      - Added debug message to investigate
      - Still finding the root cause
