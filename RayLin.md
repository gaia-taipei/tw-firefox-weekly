# This Week
- [Keyboard]
  - Bug 1100781 - Implement the recently used emojis feature
    - REVIEW+
    - Should file another integration test for emoji. Such as recently used keys, switch tab and swipe panel.

  - Bug 1235939 - Intermittent text_keyboard_test.js | Text keyboard input tests \<textarea\> tests tap space bar and then wait for a while before tapping again
    - WIP
    - Tried to make my Z3C laggy to reproduce the issue. We need a short time interval to show suggestion and let first suggestion as auto correction candidate, if two space tapping in this interval, word won't be corrected as expected.
    - Could add waiting time between two space tapping.

- [Settings]
  - Bug 1217750 - bluetooth 'rename my device' dialog looks inconsistent with other ui
    - WIP

# 2015 Q4 Goals
1. Read Keyboard App to be capable to fix bugs or add new features.
2. Increase the coverage of unit/integration test, or Polish it.
3. Help to refactor Settings and Build Script (if possible).
