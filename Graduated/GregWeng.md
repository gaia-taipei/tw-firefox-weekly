## 12/21 ~ 12/25 

### Stabilize LockScreen (reduce regressions)

* (Currently there were no newly urgent regressions; will solve old ones after the Raptor demo project get stabilized enough)

### Write more integration tests

* Bug 1235106 - Add integration test: |lockscreen_notification_tapping_test.js|
  * Review+

* Bug 1219682 - Implement *test_lockscreen_wake_with_notification.py* as an integration test in JavaScript
  * Reopen to invite QA verify it to prevent missing features

* Bug 1235105 - Add integration test: |lockscreen_unlock_handler_test.js| 
  * Landed

* Bug 1235048 - Add integration test: |lockscreen_camera_handler_test.js|
  * Landed

* Bug 1235007 - Add integration test: |lockscreen_camera_button_test.js|
  * Landed

* Bug 1232281 - Implement test_home_button.py (in Lockscreen) as an Integration test in JavaScript
  * Landed

### DeviceLock API

* (Queued after the Gij tests)

### Other tasks
* Bug 1234731 - Update lockscreen clock when screen turns on in a more direct manner
  * Performance issue
  * Landed

* Bug 1228492 - [PerformanceTool] (Tracking bug) Workable prototype to measure microbehaviors
  * Plan to write the driver in these two weeks

* From 11/17 to 11/21 we attended JSConf.Asia in Singapore
  * Will hold a Brown Bag after Mozlando

## 2015 Q4 Goals

1. Stabilize LockScreen: fixed all current regressions (measured by bug fixed), the current one is:
  1. Bug 1198417 - [Aries][Lockscreen] rotates with device but slider does not respond
    1. It has new symptom looks by full-screen video
2. Implement and migrate to DeviceLock API, as measured by progress on engineering planning and/or implementation
  1. Will start to write WebIDL and figure out the development flow first
3. Write more integration tests to prevent further regressions, as measured by # of tests planned and/or written.
4. After that, I may shift my work to System performance, including:
  1. Tool development
  2. Problem probing

## 2015 Q3 Delivered

1. Fixed security regressions caused by new bootstrapping of System app
2. Found out and proposed solution to LockScreen performance issue at device bootstrapping
3. Planned and discussed about new DeviceLock API
4. Delivered and tested an AOP tool that can help developers to write performance tests without messing up the codebase
5. Supported Academy NCU 2015 Program - JavaScript the best pratices


**Note: we changed the way to update the weely report, so now this report only keeps the latest version, and the progress is available on git log and diffs.


## 8/31 ~ 9/4

* Bug 1175623 - [FindMyDevice][Kill Switch]in the "Kill-Switch" mode, the device should be locked with a 6 digit passcode set on the website
  * UX didn't clarify lots of potential racing cases; asked; waiting response

* Bug 1199100 - [LockScreen] Implement DeviceLock API and use separated store to fix performance issue
  * Modified some parts of the spec
  * :pauljt said he shall be able to give some feedback this week

* Bug 1169842 - [Aries][Lockscreen] Holding down the camera button when the device is locked will break the lockscreen slider
  * Disappeared; there are great chances to mark it as RESOLVED WORKFORME after QA's verification

* Review bugs and feedbacks:
  * Bug 1187979 - Improve Lockscreen Inputpad's touch and visual feeback
  * Bug 1175623 - [FindMyDevice][Kill Switch]in the "Kill-Switch" mode, the device should be locked with a 6 digit passcode set on the website


#### Intermittent Errors only on TaskCluster:

* Bug 1193912 - Intermittent apps/system/test/marionette/lockscreen_statusbar_test.js | LockScreen status bar should show the maximised status bar only
* Bug 1192979 - Intermittent apps/system/test/marionette/lockscreen_mozsettings_test.js | LockScreen: ensure mozSettings API works test it can unlock ...
  * Environment got broken after updating Gaia; fixed; testing now
  * Debugging against some new suspects
  * Maybe it's too slow so the screen is off


## 08/17 ~ 08/21

### LockScreen: fix intermittent errors on Mulet

* Spent lots of time on debugging and diagnosing it
* Bug 1198140 - [LockScreen] Fix perma red notification tests on Mulet
  * review+; landed

### LockScreen performance after rebooting

* Has new strategy: using separated store to avoid tangling with mozSettings performance issue at booting
* In order to do this, we need to change the way to access LockScreen related mozSettings
* Since we need to change the interface, we could design and use our 'device lock' API as we have discussed long ago
* Now I have the proposal for that. And I believe this can be done at the next week with two individual tasks
  * Cervantes can start to implement the store in platform first
  * I can complete the API and modify Gaia no matter whether the store is done or not
  * Then we can combine our work to test if it really improve the performance as we thought and discovered
* Bug 1199100 - [LockScreen] Implement DeviceLock API and use separated store to fix performance issue

### Performance Tools:
* Bug 1196085 - Intermittent apps/system/test/build/integration/raptor_transform_test.js ...
  * review+; landed

### Current task queue:

#### Intermittent Errors only on TaskCluster:

* Bug 1193912 - Intermittent apps/system/test/marionette/lockscreen_statusbar_test.js | LockScreen status bar should show the maximised status bar only
* Bug 1192979 - Intermittent apps/system/test/marionette/lockscreen_mozsettings_test.js | LockScreen: ensure mozSettings API works test it can unlock ...
  * The same failure, but still have no clue

#### Mulet Errors:

* Bug 1187715 - Green Mulet TaskCluster Gij 11
  * The same failure as the previous twos, but still have no clue

#### Others:

* Bug 1184791 - [Aries][Lockscreen] User is able to skip lockscreen if sliding bar left or right and hitting power button twice while it's without passcode

#### 2.5+

* Left From Previous Spark Team
  * Bug 1169842 - [Aries][Lockscreen] Holding down the camera button when the device is locked will break the lockscreen slider
    * Regression of Spark feature, but I was asked to take that
    * That's why this is definitely the last item in my task queue (since I'm not the most familiar person to their feature),
      unless Spark team want to handle that

* Performance:
  * Bug 1171923 - [Aries] Time, date and unlock slider are sometimes loaded half a second after the rest of the screen

* Others:
  * Bug 1195547 - [Music] Music widget is not present on lockscreen when first playing a song without skipping or re-selecting.
    * Regression of new bootstrapping of System app
    * Kevin says he can handle that, but he may need others' help; so I don't know who is the final assignee
  * Bug 1182342 - lock screen active based on time it last appeared and not time since last activity
    * Need regression window

## 08/10 ~ 08/14

LockScreen: fix intermittent errors on Mulet

* Bug 1194979 - Use Mulet in Gaia
  * Since I have no luck at debugging intermittent Gijs; I switch to this first.

* Bug 1110913 - Intermittent `lockscreen_media_playback_test.js`
  * Still can't reproduce it on my local console
  * Will submit a request to test it on a remote server
  * It seems no one has any better way to reproduce it on local; I suspect if I could successfully catch it, especially I'm obviously not the one who knows Mulet mostly.

* Still tracing the possible root case, and still can't successfully reproduce it on my local machine, no matter on Mac or Ubuntu
  * As a result I can only debug it on treeheader per half hour (modifying, pushing and collecting results)
  * Will keep trying to reproduce it on local consoles, but I have no further ideas; may ask Alexandre his best strategy

Performance Tools:
* Bug 1186762 - [Build][Raptor Transformer] Simplify the command to make Raptor + transforming process (r+)
  * Set checkin-needed but not get landed yet. Will land it manually later.

mozSettings Performance Tuning:
* Start to work on mozSettings with Cervantes

## 08/03 ~ 08/07

LockScreen: fix security issues about racing after rebooting

* Bug 1190079 - [LockScreen][pre-Gleipnir] Remove default values of LockScreen (landed)
  * For the racing bug at branches before 2.5
* Bug 1189641 - [LockScreen][pre-Gleipnir] Move listeners and observers from lockscreen.js to other controller (mid-term plan) (landed)
  * Fix the racing root cause for master
  * With some refactoring

Performance Tools:

* Bug 1186762 - [Build][Raptor Transformer] Simplify the command to make Raptor + transforming process (r+)
 * If this get laned it will be easier to run the command and transform the code
 * So we can start to write performance tests as much as possible
 * But now I've encountered another serious raptor issue to make it almost impossible to run a real raptor test on device
     * (I'm still investigating)
