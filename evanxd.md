## 10/17 - 10/21 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1167568 - Reader View displays only the first part of specific articles from ehow.com
        - Low priority, will work Bug 1177619 first.
      - Bug 1177619 - Reader mode isn't offered on Blogger/Blogspot based blogs
        - review?
        - Updated the patch for review comments.
        - Did performance experiment. The result is not good enough in our original benchmark tests(run on nodejs).
        - Next step, we will run the performance test on gecko and need some code modification in mozilla-central.
      - Bug 1310073 - Tests for wikipedia.org
        - Cleaning up the HTML source code of the test webpage.
      - Bug 1310074 - Tests for yahoo.com
        - Cleaning up the HTML source code of the test webpage.
      - Priority reader mode bugs
        - https://public.etherpad-mozilla.org/p/reader-mode-priorities
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - Updated the patch for revie comments
      - Landed
  - Fix Test
    - Bug 1273871 - Intermittent passwordmgr/test/browser/browser_capture_doorhanger.js | This test exceeded the timeout threshold. It should be rewritten or split up. If that's not possible, use requestLongerTimeout(N), but only as a last resort.
      - Need to find the root cause. Splitting up tests might not be the correct solution.
