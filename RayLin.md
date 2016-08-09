# 08/01 ~ 08/05

- [Video Control]
  - Bug 1291013 - Closed-caption button spacing is asymetric
    - review cancelled, :jaws is overloaded
    - ask again after flag removed
  - Bug 1291009 - Closed-caption button fuzzy in hidpi mode
    - r+, :jaws
  - Bug 1291268 - HiDPI image are missing from video controls on Windows and Linux
    - code review, granted and landed
  - Bug 1292083 - Split mobile/desktop video control and make them inherited from a minimal base binding
    - WIP
    - :jaws agrees with this idea.
  - Bug 1271765 - Visual refresh of media controls
    - Stephen reviewed the concept and mainly agreed
    - Peko will offer icons in SVG format first and then spec
  - Bug 1222273 - Convert HTML \<video\>/\<audio\> controls to be (mostly?) HTML instead of XUL
    - Depends on: 1292083

### Video Control Planning ###

- [~ late Aug, about 1 month]
  - Split mobile/desktop bindings - bug 1292083
    - For better maintenance in the future and is also about to fairly reduce the hacks of de-xul process.
  - Visul refresh of media controls - bug 1271765
    - Iteration of Impl and get feedback from Peko
- [~ late Sep, about 1 month]
  - [De-XUL] Desktop - bug 726240
  - [De-XUL] Andriod - bug 726240
  - Clean up scale or other unused bindings
- [early Oct ~]
  - Code refactor/refine
    - Indent consistency
    - Better CSS structure
  - [De-XUL] Totally remove video control from XBL to HTML
    - Need to look under the hood to understand whether it is feasible.
  - Consider treat \<audio\> as 1st-class - bug 681553
