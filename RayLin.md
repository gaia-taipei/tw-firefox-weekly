# 10/17 ~ 10/21

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - review:
      - Part 1: Layout reflow fix    r?dholbert
    - layout:
      - issues fixed -> revision 2
      - dholbert PTO 10/21 - 10/25
    - a11y:
      - accessible tree fixed

  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - patch done and pushed. Will add review flag once Bug 1271765 landed

  - Bug 1311700 - Add test to confirm that video control show controls in different sizes correctly
    - have problem probing style(size, display) in mochitest, looking for similar UI test case as reference

  - Bug 1312324 - Add test to confirm that fullscreen should(not) be available accordingly when video in an iframe
    - r?jaws

  - Video control test coverage enhancement tracker bug - Bug 1303958

### Video Control Planning ###

- [after visual refresh ~]
	- Test coverage improvement:
		- CC button and its menu, and CC should correspond with selected one - fixed
		- should show "noaudio" icon if video has no audio - Bug 1302320
		- the appearance of small size video - Bug 1311700
		- should show error state and error text should fit on most video size
		- should show fullscreen button accordingly when video in an iframe - Bug 1312324
		- top level synthetic media - buttons such as play, pause, mute, CC, fullscreen should work - Bug 1312334
- [deferred]
  - Split mobile/desktop bindings - bug 1292083
  - [De-XUL] Andriod - bug 1310907

### Autofill Planning ###

  - [November ~]
    - Discuss/Work together with Steve on two preference dialogs.
