# 09/05 ~ 09/09

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - r?jaws
    - a regression was found, so changed to r- from r+ on the weekend.
      - fixed and ask review again.
		- duration/position label localization issues fixed.
  - Bug 1300805 - Disable WebVTT breaks some controls of the native media player\<Paste\>
		- WIP
		- Jared asked to include test for CC button. I think it's a good starting point for test coverage improvement.
	- Bug 1301874 - Unable to maximise videos on liveleak.com (Firefox mobile)
		- find out why fullscreen button doesn't work on liveleak.com for Fennec.

- [Slide Link](https://docs.google.com/a/mozilla.com/presentation/d/1RLjpTh-EBEa5ok9Bqntu_RcIpPOhGCLN2ATtcq2o_i0/edit?usp=sharing)
	- WIP

### Video Control Planning ###

Jared provided a list of missing tests and suggestted me to prioritize test coverage bugs. So I defer original plan and schedule some essential tests according to the list. Still some missing part like context menu or iframe related test are not included in the schedule. I need to see how far I've gone for testing and then decide what it the next, either original plan or more tests, and that depends.

- [~ late Aug, about 1 month]
  - Visul refresh of media controls - bug 1271765
- [after visual refresh ~]
	- Test coverage improvement:
		- CC button and its menu, and CC should correspond with selected one
		- should show "noaudio" icon if video has no audio
		- buttons such as play, pause, mute, CC, fullscreen should work
		- the appearance of small size video
		- should show error state and error text should fit on most video size
- [deferred]
  - Split mobile/desktop bindings - bug 1292083
  - [De-XUL] Andriod - bug 726240
  - Code refactor/refine
