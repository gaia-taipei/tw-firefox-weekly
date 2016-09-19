# 09/12 ~ 09/14

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - r+jaws
    - found a few test failures. (3 files)
      - fixed 2 of 3
      - We did a hack to determine whether plaform is mobile or desktop by deferring initialization process. Unfortunately, it conceptually opposes to SimpleTest's framework, and breaks one of the test cases. Need a workaround here.
  - Bug 1300805 - Disable WebVTT breaks some controls of the native media player\<Paste\>
		- file another bug: Bug 1303245
  - Bug 1303245 - add a test to confirm that video control show closed caption button when video has supported text track
    - WIP
  - Study testing
    - better understanding of mochitest

- [Sharing]
	- Video Control - XBL & De-XUL

### Video Control Planning ###

- [~ late Aug, about 1 month]
  - Visul refresh of media controls - bug 1271765
- [after visual refresh ~]
	- Test coverage improvement:
		- CC button and its menu, and CC should correspond with selected one - 1303245
		- should show "noaudio" icon if video has no audio - 1302320
		- buttons such as play, pause, mute, CC, fullscreen should work
		- the appearance of small size video
		- should show error state and error text should fit on most video size
- [deferred]
  - Split mobile/desktop bindings - bug 1292083
  - [De-XUL] Andriod - bug 726240
  - Code refactor/refine
