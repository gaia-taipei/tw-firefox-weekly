# 08/22 ~ 08/26

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - WIP, will ask :jaws for review early next week(W35)
    - Adjust breakpoints
      - video: (control resize)[https://drive.google.com/open?id=0B6XCugEDFBX8dUctM3VzNGluTjQ]
    - Width problem
      - sent the video and explain our intent to Stephen.
      - It's about 4 lines of code which calc width before adjustment. We can quickly respond to the decision.
    - Test & Fix:
      - audio only / no audio
      - closed caption button
      - fullscreen unavailable
      - all Fennec functionality
    - TODO
      - refine patch
      - final check with UI/UX

- [Sharing]

below is my outline draft:

  - Write and Test XUL/XBL without rebuilding firefox
  - Basic XBL concept
  - Namespce
  - Inspect XBL binding/anonymous content in content
  - Inheritance
  - De-XUL


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
