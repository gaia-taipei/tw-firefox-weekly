# 05/16 ~ 05/20

- [Firefox for Android]
  - Bug 1086911 - Update style of about:firefox
    - WIP
    - header background stack finished
  - Bug 1273468 - Full-screen button is missing in 47 Beta 6
    - Help investigate and find regression
  - Bug 1091241 - Make add-on detail page look more like a detail page
    - r? Margaret
    - fixed border issue, review again
  - Bug 1267935 - Video controls are not correctly scaled for several video types
    - approval-mozilla-aurora?
- [Firefox]
  - Bug 887934 - [webvtt] Update \<video\> controls to include options for closed captioning
    - WIP
    - Three approaches to vertically move up subtitle while control bar is showing:
      1. addEventListener when frameUpdate - has a pitfall that we could not re-style caption box when video is paused
      2. expose an attribute like "mozCaptionBox" on \<video\> element to let control adjust caption box.
    - Currently work on second approach
  - Bug 1203481 - All dividers in the URL bar should have the same style
    - r+
