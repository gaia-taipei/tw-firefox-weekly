# 09/26 ~ 09/30

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - ask :astley for help with layout problem
    - fix some mochitests and a11y tests, but still try to make them green on all platforms.
    - a11y accessible tree is different from original XUL version. Get to tweak it in optimal way.
  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - WIP

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
