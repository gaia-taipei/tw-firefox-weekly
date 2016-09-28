# 09/19 ~ 09/23

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - try to fix & survey possible layout problem
    - ask :astley for help with layout problem
    - notice potential issues about a11y-media test, study a11y test and its libs
  - Bug 1303245 - add a test to confirm that video control show closed caption button when video has supported text track
    - landed
  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - WIP
  - Bug 1303993 - "Save audio" option displayed when long tapping a video
    - help with finding causes

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
