# 10/03 ~ 10/14

- [Video Control]
  - Bug 1271765 - Visual refresh of media controls
    - review:
      - Part 1: Layout reflow fix    r?dholbert
      - Part 2: Visul refresh        r+jaws
      - Part 3: Tests fix            r+jaws
    - layout:
      - discussed with :astley offline
      - dholbert PTO til 10/17
    - a11y:
      - study ARIA and optimize new a11y tree
      - get help from a11y team (:marcoZ and :surkov)
      - ask them to verify new impl if it is still accessible
    - l10n:
      - don't use single quote in locale string(Bug 1294275) -> workaround with JavaScript
    - mochitest-5:
      - system default font breaks one of case which highly rely on precise font size(width)
      - `font-size-adjust` fix font issue on platforms individually
    - Hope to land by the end of next week (10/21)

  - Bug 1302320 - add a test to confirm that video control show "noaudio" icon when video has no audio
    - patch done and pushed. Will add review flag once Bug 1271765 landed

  - Next week:
		- add the appearance tests for small size video.
      - would be based on new layout


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
