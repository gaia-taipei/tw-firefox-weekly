# 08/15 ~ 08/19

- [Video Control]
  - Bug 1291013 - Closed-caption button spacing is asymetric
    - Uplifted -> Aurora
  - Bug 1291009 - Closed-caption button fuzzy in hidpi mode
    - Uplifted -> Aurora
  - Bug 1293601 - \[Fennec\] The video controls are missing the time slider and show a random number at the start of video playback on YouTube
    - Uplifted -> Aurora
  - Bug 1271765 - Visual refresh of media controls
    - WIP. New interface are mostly implemented (100% xhtml + css)
    - TODO:
      - Error page layout
      - Adjust breakpoints for different video size

- [Sharing]
  - think of topic and scope


### Video Control Planning ###

- [~ late Aug, about 1 month]
  - Visul refresh of media controls - bug 1271765
- [~ late Sep, about 1 month]
  - [De-XUL] Andriod - bug 726240
  - Split mobile/desktop bindings - bug 1292083
  - Clean up scale or other unused bindings
- [early Oct ~]
  - Code refactor/refine
    - Indent consistency
    - Better CSS structure
  - [De-XUL] Totally remove video control from XBL to HTML
    - Need to look under the hood to understand whether it is feasible.
  - Consider treat \<audio\> as 1st-class - bug 681553
