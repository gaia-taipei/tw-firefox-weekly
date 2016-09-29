## 09/19 - 09/23 ##

* [Firefox]
  - QX
    - Bug 565567 - FF should ask for confirmation before quitting with Cmd-Q (only on Mac)
      - Stop working on it after product team finish their [design research][design-research].
      - Philipp said "I'd like to pause work on this bug until we have answers from research".
    - Bug 1167568 - Reader View displays only the first part of specific articles from ehow.com
      - Investigating...
      - If we resort `topCandidates ` array and make the item whose content length is maximum as `topCandidates[0]`, then we can get correct result. Looks like the score counting algorithm might be not correct.
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - After investigated, we could add two `richlistitem` elements(moz-action:visiturl and moz-action:searchengine ones) on the `#PopupAutoCompleteRichResult` panel when the `moz-action` is `visiturl`.
      - ui-review+
      - feedback+
      - Continue to update patch for the review comments and fix failed tests.
    - Bug 1192800 - Intermittent browser_context_menu.js | Uncaught exception - at :0 - Error: operation not possible on dead CPOW
      - Will fix another intermittent failure bug [Bug 1273871][bug-1273871] first, it has higher priority.
      - No new progress

[design-research]: https://bugzilla.mozilla.org/show_bug.cgi?id=565567#c41
[bug-1273871]: https://bugzilla.mozilla.org/show_bug.cgi?id=1273871
