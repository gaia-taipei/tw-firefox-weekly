## 10/26 ~ 10/30 ##

### Last week
* [Audio Channel Management]
  - Bug 1218666 - Play icon will hide when get a notification
    - Landed.
  - Bug 1217303 - Remove mozContentEvent and mozChromeEvent about controlling System's audio channel in shell.js
    - Landed.
  - Bug 1218593 - Dialer touch tones sounds intermittently stop playing audio in Dialer.
    - Investigated, this is a gecko bug.
  - Bug 1213666 - No sound in videos from France 24
    - Investigated, this is a gecko bug.
  - Bug 1218690 - Marionette tests for play icon
    - Already had a WIP patch, but Music app cannot be launched in local. Will fix it in next week.
  - Bug 1218692 - [meta] Marionette tests for Audio Channel Management
    - Listed test cases in the below bugs.
      - Bug 1096163 - Marionette tests for audio channel competing
      - Bug 1218690 - Marionette tests for play icon
        - Listed 5 test cases in http://bugzil.la/1218690#c2.
      - Bug 1218691 - Marionette tests for current volume type
      - Bug 1220053 - Make sure audio channel management works well for 3-rd-party app
        - Listed 2 test cases in https://bugzil.la/1220053#c1.

* [Web of Things]
  - Recorded a demo video for Web of Things Maker.
    - https://drive.google.com/a/mozilla.com/file/d/0B95rKL0BstcnSDRnc2gyaUxMUDg/view

### This week
* [Audio Channel Management]
  - (2.5?)Bug 1220320 - [Accessibility] Screen Reader prompt no longer plays, automatically in the FTU or after toggling volume up and down several times.
    - Start to investigate and fix the bug.
  - Bug 1218690 - Marionette tests for play icon
    - Fix the Music app issue and continue to write tests listed in http://bugzil.la/1218690#c2.
  - Bug 1199757 - brief sound after hang up
    - Start to investigate and fix the bug.
  -Bug 864416 - [music]Volume resets to being audible when you launch music app and play a song.
    - Start to investigate and fix the bug.

* [Web of Things]
  - Will attend MozFest 2015 during 11/4 and 11/10.
  - Prepare for MozFest demo.

## 2015 Q4 Goals
1. Investigate Media Focus. http://bugzil.la/1206691, as measured by (a) making a technical decision on whether or not to implement that, and (b) completeness on the implementation plan.
2. Fix blocker bugs of Audio Channel Management Module, as measured by blocker burn down and days of blocker turnarounds.
3. Fix blocker bugs of Settings App, as measured by blocker burn down and days of blocker turnarounds.
4. Support Web of Things Project: implement FoxCount project, as measured by implementation completeness.
5. Mentor Bluetooth Test App, as measured by implementation completeness.

## 2015 Q3 Delivered
1. Fixed blocker bugs of Audio Channel Management Module.
2. Fixed blocker bugs of Settings App.
3. Supported Web of Things Project: did prototyping(People Counter), built Web of Things Maker and presented it to Web of Things Group.
4. Supported Academy Program: plan the courses.
5. Made an addon(Robot Jan) and won the Best Design Award. It also can help UX Team do user experimentation.
