# 11/08 ~ 11/10

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - target on next release cycle
    - latest try: https://treeherder.mozilla.org/#/jobs?repo=try&revision=c890fe464ff2a4c13505db9d1e137fe752d90f5e&selectedJob=30963545
  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - patch done and pushed. Will add review flag once Bug 1271765 landed
  - Bug 1311700 - Add test to confirm that video control show controls in different sizes correctly
    - patch done and pushed. Will add review flag once Bug 1271765 landed
  - Bug 1312334 - add test to confirm that every control work fine when open media directly
    - WIP
  - Add a test to confirm error state and error text should display and fit on most video size
    - discuss with Alastor, our first diagnosis is that we can not produce error state manually. The `mError` is an internal used variable, and not exposed to any API. Since we could not easily to simulate state like network error or decode aborted in test environment, remove this test from plan.
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
