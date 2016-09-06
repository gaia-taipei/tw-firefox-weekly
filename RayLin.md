# 08/29 ~ 09/02

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - r?jaws
    - Locale: position/duration time string not localizer friendly.
      - revised and retain original behavior.
  - Try/Study video testing

- [Sharing]

  Prepare slide in W36

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
