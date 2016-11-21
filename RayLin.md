# 11/14 ~ 11/18

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - landed
  - Bug 1317909- Add a test to confirm error msg & icon present when open unsupported media
    - landing
  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - will rebase & ask for review next week (W47)
  - Bug 1311700 - Add test to confirm that video control show controls in different sizes correctly
    - will rebase & ask for review next week (W47)
  - Bug 1312334 - add test to confirm that every control work fine when open media directly
    - WIP
    - solved the issue about passing DOM object across process. (from content process to chrome process)
  - Bug 1302310 - Consider make video control's width match the size of video element
    - WIP
  - Video control test coverage enhancement tracker bug - Bug 1303958

### Video Control Planning ###

- [after visual refresh ~]
	- Test coverage improvement:
		- should show "noaudio" icon if video has no audio - Bug 1302320
		- the appearance of small size video - Bug 1311700
		- top level synthetic media - buttons such as play, pause, mute, CC, fullscreen should work - Bug 1312334
  - Fennec
    - should play video when click on video element - Bug 1313563
    - should adjust all the controls' size accordingly - Bug 1316254
- [deferred]
  - Split mobile/desktop bindings - bug 1292083
  - [De-XUL] Andriod - bug 1310907

### Autofill Planning ###

  - [November ~]
    - Discuss/Work together with Steve on two preference dialogs.
