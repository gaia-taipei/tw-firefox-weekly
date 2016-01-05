## 12/28 ~ 12/31 ##

### Last week
* [Audio Channel Management]
  - Bug 1227804 - Marionette test to ensure all audio channels can be played in foreground and background.
    - Landed.
  - Bug 1235335 - Video cannot be played in background.
    - WIP patch: https://github.com/evanxd/gaia/commit/2e6f4bad8c84005df291765ffd8a158ee9a8b0db
    - Found out a issue, test video cannot be played in the test. Continue to fix it next week.
  - Bug 1233565 - Intermittent TEST-UNEXPECTED-FAIL | apps/system/test/marionette/audio_channel_competing_test.js | Audio channel competing Notification audio channel competes with audio channels Notification
    - The crash issue might be caused by Bug 1175116. Continue to fix this bug next week.
  - Bug 1235538 - Intermittent TEST-UNEXPECTED-FAIL | apps/music/test/marionette/Player_test.js | Music player tests Status bar Check the play icon is in the status bar. moztrap:9742
    - Help to review the patch and r+.

* [Web of Things]
  - After discussion, we have a tech architecture. We'll introduce that in a brownbag next week.
  - Next step, we need to find out good use cases to help WebEverwhere group pass Gate 0.
  - I'll host a brownbag and brainstorming events to get more good ideas.

* [Brief Idea about 2016 Q1 Plan]
  - Help WebEverwhere group pass Gate 0. We'll need showcase ideas, tech architecture, and prototypes of showcases.
  - Help System merge things. Merge audio channel management module.
  - Marionette tests for audio channel management. See Bug 1218692.

### This week
* [Audio Channel Management]
  - Bug 1233565 - Intermittent TEST-UNEXPECTED-FAIL | apps/system/test/marionette/audio_channel_competing_test.js | Audio channel competing Notification audio channel competes with audio channels Notification
    - Change a new and stable way to assert states of audio channels. It can fix this failure https://tools.taskcluster.net/task-inspector/#Anxgl-A_TE6kW-0ecGICxw/3.
  - Bug 1235335 - Video cannot be played in background.
    - Fix the issue test video cannot be played in the test.
  - Bug 1218690 - Marionette tests for play icon
    - Start to write test cases.

* [Web of Things]
  - Prepare stuffs for the brownbag.

* [2016 Q1 Plan]
  - Discuss 2016 Q1's goals with manager.

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
