# 11/21 ~ 11/25

- [Video Control]
  - Bug 1317909- Add a test to confirm error msg & icon present when open unsupported media
    - landing
  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - landed
  - Bug 1311700 - Add test to confirm that video control show controls in different sizes correctly
    - part 1, r+jaws
    - part 2, r?jaws
  - Bug 1312334 - add test to confirm that every control work fine when open media directly
    - WIP
  - Bug 1302310 - Consider make video control's width match the size of video element
    - landed
  - Bug 1313285 - Remove nsVideoFrame::mBorderPadding
    - landing
  - Bug 1319301 - New video controls have leave a gray overlay over videos
    - r?jaws
  - Bug 1319569 - Dead code in videocontrols.xml
    - WIP
  - Bug 1319584 - Remove right-border-radius
    - r?jaws, f?Dolske
  - Video control test coverage enhancement tracker bug - Bug 1303958

### Video Control Planning ###

- [after visual refresh ~]
	- Test coverage improvement:
		- the appearance of small size video - Bug 1311700
		- top level synthetic media - buttons such as play, pause, mute, CC, fullscreen should work - Bug 1312334
  - Regression && Polish:
    - dead code in videocontrols.xml
    - remove right-border-radius
    - shadow around scrubber thumb
  - Fennec
    - should play video when click on video element - Bug 1313563
    - should adjust all the controls' size accordingly - Bug 1316254
- [deferred]
  - Split mobile/desktop bindings - bug 1292083
  - [De-XUL] Andriod - bug 1310907

### Autofill Planning ###

  - [December ~]
    - join autofill sessions in Hawaii all hands
