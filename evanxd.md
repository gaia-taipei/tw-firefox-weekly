## 12/21 ~ 12/25 ##

### Last week
* [Audio Channel Management]
  - Bug 1227804 - Marionette test to ensure all audio channels can be played in foreground and background.
    - r?
  - Bug 1227805 - Marionette test to ensure content audio channel can be played in background.
    - Fixed this in Bug 1227804.
    - RESOLVED DUPLICATE of bug 1227804
  - Bug 1228475 - Ensure System's audio channels are controlled by Audio Channel Service. 
    - r?
  - Bug 1233565 - Intermittent TEST-UNEXPECTED-FAIL | apps/system/test/marionette/audio_channel_competing_test.js | Audio channel competing Notification audio channel competes with audio channels Notification
    - The failure is about crash of FxOS. Looks like it is more about Gecko issue. Already call for help from Alastor.
  - Bug 1232363 - No audible sound coming from Alarm audio channel.
    - Help to review the patch and r+.

* [Bluetooth Test App]
  - Rehearsal with Hong Yong for presenting his work in demo day.

### This week
* [Audio Channel Management]
  - Bug 1232892 - Normal audio channel competes with all kinds of audio channels in one test app
    - Start to investigate and fix the bug.
  - Bug 1233565 - Intermittent TEST-UNEXPECTED-FAIL | apps/system/test/marionette/audio_channel_competing_test.js | Audio channel competing Notification audio channel competes with audio channels Notification
    - Figure out the crash issue with Alastor.
  - Bug 1218690 - Marionette tests for play icon
    - Start to write test cases.
  Bug 1235335 - Video cannot be played in background.
    - Start to write test cases.

* [Web of Things]
  - Meeting for WebEverywhere Architecture Open Discussion
  - Meeting for the next step of WebEverywhere

* [Others]
  - Plan 2016 Q1.

## 2015 Q4 Goals
1. Support Web of Things Project: implement FoxCount project, as measured by implementation completeness.
2. Define UI test cases for audio channel management and write the tests for audio channel competitions. http://bugzil.la/1096163, as measured by implementation completeness.
3. Fix blocker bugs of Audio Channel Management Module, as measured by blocker burn down and days of blocker turnarounds.
4. Fix blocker bugs of Settings App, as measured by blocker burn down and days of blocker turnarounds.
5. Mentor Bluetooth Test App, as measured by implementation completeness.

## 2015 Q3 Delivered
1. Fixed blocker bugs of Audio Channel Management Module.
2. Fixed blocker bugs of Settings App.
3. Supported Web of Things Project: did prototyping(People Counter), built Web of Things Maker and presented it to Web of Things Group.
4. Supported Academy Program: plan the courses.
5. Made an addon(Robot Jan) and won the Best Design Award. It also can help UX Team do user experimentation.
