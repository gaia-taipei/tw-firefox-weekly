## 10/03 - 10/14 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1167568 - Reader View displays only the first part of specific articles from ehow.com
        - review?
      - Bug 1177619 - Reader mode isn't offered on Blogger/Blogspot based blogs
        - review?
      - Bug 1309499 - [meta] Tests for High-profile Websites
        - Discussed the test plan with Gijs. We want to create tests for high-profile webistes listed on Alexa.
      - Bug 1310073 - Tests for wikipedia.org
        - review?
      - Bug 1310074 - Tests for yahoo.com
        - review?
      - Bug 1310075 - Tests for qq.com
        - Wrote [WIP patch][bug-1310075-wip-patch], but the test cannot be passed with [jsdom][jsdom] yet. Need to fix it.
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - review?
  - Fix Test
    - Bug 1273871 - Intermittent passwordmgr/test/browser/browser_capture_doorhanger.js | This test exceeded the timeout threshold. It should be rewritten or split up. If that's not possible, use requestLongerTimeout(N), but only as a last resort.
      - review?

[bug-1310075-wip-patch]: https://github.com/evanxd/readability/commit/a447bc33bf0bb69fc412b33a77b57056f1e99327
[jsdom]: https://www.npmjs.com/package/jsdom
