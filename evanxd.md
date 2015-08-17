## 08/10 ~ 08/14 ##

### Last week

* [Audio Channel Management]
  - [Bug 1184876](http://bugzil.la/1184876) - Gaia part to add devices information in audio volume event
    - After disscussion, we don't need to do any change in gaia. So it doesn't dpendence on gaia. Nice! :)
  - [Bug 1190434](http://bugzil.la/1190434) - Browser app stops playing audio when screen turns off
    - Waiting for UX response.

* [Settings Bugs]
  - [Bug 1160374](http://bugzil.la/1160374) - [Settings][Call Barring] Cancel and OK button not working on Enter passcode screen
    - Landed.

* [BLE Test App]
  - [Bug 1194582](http://bugzil.la/1194582) - Test App for Bluetooth Low Energy Server APIs.
    - Created the [wireframe](https://bug1194582.bmoattachments.org/attachment.cgi?id=8647888).

* [WoT]
  - Disscussed [IoT ideas](https://docs.google.com/document/d/1HP4C5bfbvI0nflVFMOt7HKEbpff0jo8UsUw6AoMlrec/edit) with the team.
    - An IoT application hleps people check the availability of restroom in the browser.

### This week

* [Audio Channel Management]
  - [Bug 1195191](http://bugzil.la/1195191) - [Dialer] Volume Audio Channel is incorrect after a call
  - [Bug 1193759](http://bugzil.la/1193759) - No sound on alerts/notifications

* [Settings Bugs]
  - [Bug 1170236](http://bugzil.la/1170236) - Sometimes the screen to connect to a hidden network doesn't have the OK button enabled
  - [Bug 1160992](http://bugzil.la/1160992) - [Notifications]When the cell phone service goes out, the data traffic option in Notification is not available.
  - [Bug 1155995](http://bugzil.la/1155995) - WiFi certificate import lacks proper feedback to the user
  - [Bug 1182924](http://bugzil.la/1182924) - Cannot add new data APN

* [Systme 2 Refactoring]
  - [Bug 1093516](http://bugzil.la/1093516) - [System2] Migrate AppUpdate/InstallDialog to SystemDialog

* [BLE Test App]
  - [Bug 1194582](http://bugzil.la/1194582) - Test App for Bluetooth Low Energy Server APIs
    - Disscued the code architecture with Eddie.

* [WoT]
  - Build a [prototype](https://github.com/evanxd/restroom-checker) for the restroom idea.
  - Design a architecture of the IoT application.
  - Meetings for how to implement the restroom idea and design the architecture of it.

## 08/03 ~ 08/07 ##

### Last week

* [Audio Channel Management]
  - Bug 1180618 - Ringer is not managed by Audio Channel Service
    - Patch is ready.
    - Blocked by gecko Bug 1167465.
  - Bug 1183870 - [B2G] Set current audio channel to "none" when there is no any audio playing
    - Patch is ready.
    - Blocked by gecko Bug 1191207.
  - Bug 1186572 - [FTU] Skipping through initial screen of tutorial will cause tutorial animated images to stop loading
    - Figured out the root cause. This is a gecko bug.
  - Bug 1189115 - [Keyboard] Keyboard click sound stops playing after 2 keys are pressed
    - A duplicate bug of Bug 1183033.

* [JS Marionette]
  - Bug 1191705 - Make VERBOSE log readable
    - Landed.

### This week

* [Audio Channel Management]
  - Bug 1184876 - Gaia part to add devices information in audio volume event
  - Bug 1192725 - Configurable Audio Channel Policy
    - Provide a easy and fast way to config audio channel policy
  - Bug 1190434 - Browser app stops playing audio when screen turns off
    - Discussed the UI spec.

* [Fix Settings bugs]
  - Bug 1160374 - [Settings][Call Barring] Cancel and OK button not working on Enter passcode screen
    - 2.5+ bug

* Others
  - Disscuss IoT ideas with Eddie and Cindy.
  - Disscuss BLE test app with dwi2.
