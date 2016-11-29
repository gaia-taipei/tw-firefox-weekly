## 11/21 - 11/25 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1173548 - Reader View picks wrong direction for some RTL pages
        - review+
        - Landed in GitHub repo.
      - Bug 1255978 - Reader View displays list of other articles when used on article on www.independent.co.uk
        - review+
        - Landed in GitHub repo.
        - Discussed and updated the patch quite a lot to figure out a good solution with the reviewer.
      - Bug 1318605 - Do language detection for cases don't obtain a dir attribute
        - review?
        - Updated patch for few times, I think we're almost done there.
  - Others
    - Bug 1273871 - Intermittent passwordmgr/test/browser/browser_capture_doorhanger.js | This test exceeded the timeout threshold. It should be rewritten or split up. If that's not possible, use requestLongerTimeout(N), but only as a last resort.
      - Landed.
