## 11/14 - 11/18 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1173548 - Reader View picks wrong direction for some RTL pages
        - review?
      - Bug 1255978 - Reader View displays list of other articles when used on article on www.independent.co.uk
        - review?
      - Bug 1317930 - Tests for msn.com
        - Landed.
      - Bug 1318605 - Do language detection for cases don't obtain a dir attribute
        - Wrote a WIP patch and discussed it with reviewer.
      - Bug 1315490 - 2.33 - 3.82% tps (linux64, windows8-64) regression on push ef3d294a1cf6 (Wed Nov 2 2016)
        - Proved that the patch doesn't make a regression.
        - RESOLVED WONTFIX
      - Bug 1176827 - Character encoding in Reader Mode is broken if page content without specified encoding is loaded off network with XHR (rather than using 'guessed' character encoding for existing document) - affects reloads, bookmarks, undo close tab, etc. 
        - After discussed with Gijs, it becomes a low priority bug and we skip it at this stage.
