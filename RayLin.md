# 08/08 ~ 08/12

- [Video Control]
  - Bug 1291013 - Closed-caption button spacing is asymetric
    - FIXED
  - Bug 1291009 - Closed-caption button fuzzy in hidpi mode
    - FIXED
  - Bug 1293601 - \[Fennec\] The video controls are missing the time slider and show a random number at the start of video playback on YouTube
    - r+, checkin-needed
  - Bug 1271765 - Visual refresh of media controls
    - WIP
    - :dolske and :jaws gave some feedback.
    - Got a spec draft from Peko.
  - Bug 1292083 - Split mobile/desktop video control and make them inherited from a minimal base binding
    - Deferred

### Video Control Planning ###

- [~ late Aug, about 1 month]
  - Visul refresh of media controls - bug 1271765
    - Iteration of Implementation and getting feedback from Peko
  - Split mobile/desktop bindings - bug 1292083
    - For better maintenance in the future and is also about to fairly reduce the hacks of de-xul process.
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
