# 11/28 - 12/23

- [Video Control]
  - Bug 1317909- Add a test to confirm error msg & icon present when open unsupported media
    - landed
  - Bug 1311700 - Add test to confirm that video control show controls in different sizes correctly
    - landed
  - Bug 1313285 - Remove nsVideoFrame::mBorderPadding
    - landed
  - Bug 1319301 - New video controls have leave a gray overlay over videos
    - landed
  - Bug 1319569 - Dead code in videocontrols.xml
    - landed
  - Bug 1319584 - Remove right-border-radius
    - r?jaws
  - Bug 1321416 - Unnecessary scrollbars appear on video document
    - landed
  - Bug 1319598 - Time label for playback position/duration shifts around
    - reviewed & landed
    - Jared spotted this issue occurred only on Mac, so setting `Helvetica Neue` for OSX work fine.
  - Bug 1323640 - refactor head.js -> getAnonElemWithinVideoByAttribute method to avoid using potential undefined variable
    - landed
  - Bug 1323767 - Fix the indentation and inconsistent brace-style, and switch to using ES6 method definitions in videocontrols.xml
    - reviewed & landed
  - Bug 1322512 - \<audio\> with vertical writing mode doesn't render anything visible
    - r?dholbert
  - Video control test coverage enhancement tracker bug - Bug 1303958

- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - study autocomplete bindings and popup mechanism under the hood.

### Video Control Planning ###

- [after visual refresh ~]
  - Regression && Polish:
    - remove right-border-radius

### Autofill Planning ###

  - Support multiple column
