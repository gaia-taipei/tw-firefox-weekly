## 11/01 - 11/04 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1177619 - Reader mode isn't offered on Blogger/Blogspot based blogs
        - Landed
      - Bug 1310074 - Tests for yahoo.com
        - Landed
      - Bug 1173823 - Reader View ignores <base href="...">
        - r?
      - Bug 1240035 - Page from books.portonvictor.org is misparsed and everything gets stuck in an <a> tag
        - RESOLVED DUPLICATE of bug 1170955
        - Found out the root cause and wrote a patch for it. Then found out that could be solved by bug 1170955.
