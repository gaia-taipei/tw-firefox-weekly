# 07/25 ~ 07/29

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - Prefer design 01
    - Consider special cases:
      - Play audio with \<video\> (no video frame presents)
      - Video without audio track
      - Extreme small size video
      - Error message refresh
  - Bug 1222273 - Convert HTML \<video\>/\<audio\> controls to be (mostly?) HTML instead of XUL
    - Struggle with mobile UI and XBL inheritance problem.
    - Conversion progress:
      - Desktop:
        - Mostly XUL converted, except \<xul:stack\> and \<xul:scale\>
        - All functions and interface work fine in normal/large size video.
        - In small size, e.g. 120px, audio button mis-align...need a subtle CSS adjustment.
      - Mobile:
        - Like desktop, xul tag mostly removed
        - Timeline bar's height could not sized as expected
        - Abnormal touch event on \<xul:scale\> after de-xul (some hack suppress events in original impl)

### Video Control Planning ###

After two weeks struggled with De-XUL, I realized the pain point of video control refactoring.
Old interface has tricky layouts which heavily leverage XUL features, such as thumb overhang timeline or volume control. Both of them inherited from \<xul:scale\> and shared between Desktop and Mobile layout. \<xul:scale\> interferes box model badly and also increases the complication.

With new visual design, we could get rid of \<xul:scale\> perfectly. I beleive it will be more convincing if we could deliver a new interface and then take a fairly easy path to go on further de-xul process. Besides, I plan to add cleanup and refactor bug for video control afterwards.

- [~ late Aug, about 1 month]
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
