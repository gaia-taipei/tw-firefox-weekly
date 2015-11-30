## 11/23 ~ 11/27 ##

### Last week
* [Audio Channel Management]
  - Filed bugs to test all audio channel competitions.
    - Bug 1227824 - Normal audio channels compete with all kinds of audio channels.
    - Bug 1227825 - Content audio channel competes with all kinds of audio channels.
    - Bug 1227826 - Alarm audio channel competes with all kinds of audio channels.
    - Bug 1227827 - System audio channel competes with all kinds of audio channels.
    - Bug 1227828 - Ringer audio channel competes with all kinds of audio channels.
    - Bug 1227829 - Telephony audio channel competes with all kinds of audio channels.
    - Bug 1227830 - Notification audio channel competes with all kinds of audio channels.
    - Bug 1227831 - Public Notification audio channel competes with all kinds of audio channels.
  - Bug 1227824 - Normal audio channels compete with all kinds of audio channels.
    - Implemented test cased for normal v.s. normal, normal v.s. content, normal v.s. alarm, normal v.s. system, normal v.s. ringer, and normal v.s. telephony. 

* [Others]
  - Give a talk in Mozilla Academy Program.
    - http://evanxd.github.io/wot-introduction
  - Discussed with Eddie, Gred, and Fred how to present our add-ons works in all-hands meeting in Mozlando.

### This week
* [Audio Channel Management]
  - Bug 1227824 - Normal audio channels compete with all kinds of audio channels.
    - Update patch to fix some nits, and send review request.
  - Bug 1228925 - Fix marionette tests of normal audio channel competes notification and public notification audio channels.
    - Start to investigate and fix the bug.
  - Bug 1227825 - Content audio channel competes with all kinds of audio channels.
    - Start to implement all test cases.

* [Web of Things]
  - Implement the prototype for WoT demo in Mozlando.
    - Implement the notification feature.

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
