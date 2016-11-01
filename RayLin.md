# 10/24 ~ 10/28

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - r+dholbert
  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - patch done and pushed. Will add review flag once Bug 1271765 landed
  - Bug 1311700 - Add test to confirm that video control show controls in different sizes correctly
    - WIP
  - Bug 1312324 - Add test to confirm that fullscreen should(not) be available accordingly when video in an iframe
    - landed
  - Video control test coverage enhancement tracker bug - Bug 1303958

### Video Control Planning ###

- [after visual refresh ~]
	- Test coverage improvement:
		- should show "noaudio" icon if video has no audio - Bug 1302320
		- the appearance of small size video - Bug 1311700
		- should show error state and error text should fit on most video size
		- top level synthetic media - buttons such as play, pause, mute, CC, fullscreen should work - Bug 1312334
- [deferred]
  - Split mobile/desktop bindings - bug 1292083
  - [De-XUL] Andriod - bug 1310907

### Autofill Planning ###

  - [November ~]
    - Discuss/Work together with Steve on two preference dialogs.
