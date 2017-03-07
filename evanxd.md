## 03/01 - 03/03 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1323861 - Reader Mode displays "Failed to load article from page" on all Breitbart articles
        - Landed in m-c.
      - Bug 1217007 - using reader mode on medium.com can omit leading paragraphs/sections
        - Landed in m-c.
      - Bug 1177360 - Amazon pages offer Reader Mode, produce either random review content or Amazon Prime / shipping offers - should work better or not be offered
        - review+
        - Wrote a patch.
      - Bug 1340799 - Add an automated test for clicking hash links in reader mode scrolling to the anchor (rather than exiting reader mode)
        - Landed.
      - Bug 1180900 - Stack Exchange pages seem to show only the question or one answer in Reader View
        - Wrote a WIP patch.
      - Replied comments, set labels, and reproduced the issues for GitHub Issues And Bugzilla bugs
        - https://bugzilla.mozilla.org/show_bug.cgi?id=1343205#c2
      - Investigated how to move reader move to a system add-on
        - https://public.etherpad-mozilla.org/p/move-reader-mode-to-system-addon
