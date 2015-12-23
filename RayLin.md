# This Week
- [Keyboard]
  - Bug 1216432 - Keys on Emoji swipe panel does not layout correctly in landscape mode
    - REVIEW?
    - Added Unit test about rotate

  - Bug 1177658 - choosing a keyboard auto completed word should append a space
    - REVIEW?
    - Deep understanding about IME. Since we could not easily probe and modify test in input DOM, the magic is to record cursor and data, then manipulate & update it. Making our data consistent with view is very important.
    - Tried two different approaches: Andriod-like and iOS-like. We chose iOS-like to deliver better user experience.

- [Settings]
  - Bug 835257 - [OPEN_][WIFI] Setting a custom AP which ssid name is over 32 characters also can be saved.(617001981003)
    - RESOLVE FIXED

  - Bug 1210673 - use dialog service to show media storage dialogs
    - RESOLVE FIXED

  - Bug 1210674 - use dialog service to show improve_browser_os_send_feedback dialogs
    - RESOLVE FIXED

  - Bug 1202945 - [settings] separate openIncompatibleSettingsDialog with DialogService
    - REVIEW?

# 2015 Q4 Goals
1. Read Keyboard App to be capable to fix bugs or add new features.
2. Increase the coverage of unit/integration test, or Polish it.
3. Help to refactor Settings and Build Script (if possible).
