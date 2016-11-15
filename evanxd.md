## 11/07 - 11/10 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1173823 - Reader View ignores <base href="...">
        - Landed
        - Upated patch for comments.
      - Bug 1310075 - Tests for qq.com
        - Landed
      - Bug 1315490 - 2.33 - 3.82% tps (linux64, windows8-64) regression on push ef3d294a1cf6 (Wed Nov 2 2016)
        - Ran experiments to check the performance regression.
        - Found out maybe the regression cannot be caused by the patch.
        - Discussing how to measure it and waiting for response.
      - Bug 1176827 - Character encoding in Reader Mode is broken if page content without specified encoding is loaded off network with XHR (rather than using 'guessed' character encoding for existing document) - affects reloads, bookmarks, undo close tab, etc.
        - Found out the root cause and discussed possible solutions.

* [Fennec]
  - Bug 1280184 - Android: uninstalling firefox will delete all downloaded files, very annoying
    - Help reproduce the issue.
