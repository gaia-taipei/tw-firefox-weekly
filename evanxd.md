## 10/24 - 10/28 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1177619 - Reader mode isn't offered on Blogger/Blogspot based blogs
        - review? (almost done)
        - Ran performance experiment[1] on gecko. Reviewer and I agreed that the result is good enough.
        - Next step, add tests for patch.
      - Bug 1310073 - Tests for wikipedia.org
        - Landed.
        - Cleaned up the HTML source code of the test webpage.
      - Bug 1310074 - Tests for yahoo.com
        - Cleaned up the HTML source code of the test webpage.
        - The tests can be passed with JSDOMParser, but cannot be passed with jsdom.
        - Next step, figure out the above issue.
      - Prioritized reader mode bugs
        - P3.1: Bug 1177619, test suites(Bug 1309499), and issues with the result of reader mode
        - P3.2: UI bugs, like high contrast mode or integration with bookmarks
        - P3.3: Issues with whether or not pages are reader-able

[1]: https://docs.google.com/spreadsheets/d/1vk7bU_Z0KG4F7OEGlVWX_SA8IrH94lwrNVcw6zYBR6E
