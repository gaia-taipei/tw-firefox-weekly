## 11/02 ~ 11/06

### Stabilize LockScreen (reduce regressions)

* Bug 1215674 - If the user closes music and quickly locks the device, the music widget will still be present
  * RESOLVE FIXED

* Bug 1175809 - [NFC] Unable to share URL via NFC when play video on full screen mode
  * Will raise approval for 2.5

### Write more integration tests

* Bug 1218645 - [LockScreen] Re-write Gij tests that in the abandoned Gip
  * Will do some work in this week
  * Delayed because of the unexpected drilling down of Raptor tool

### DeviceLock API

* (Queued after the Gij tests)

### Other tasks
* Bug 942837 - [User Story] Show Alarm Time on Lock Screen 
  * After lots of rounds of reviewing, patch is ready to land

* Bug 1165814 - [raptor] Add an option to let user determinate when to flush the log, and add a Marionette phase for combing them together
  * This week I've focused on this bug, because the issue is more complicated than what I had thought. See:

### The Progress of Raptor Improvement

#### Issues

  1. The existing phases in Raptor don't support to only measure from one to another mark, so I need to implement it
  2. [https://github.com/mozilla-raptor/raptor-cli/blob/master/lib/phases/reboot.js#L109](The hack in Raptor) in fact makes inaccurate measure
    * I fixed that in my own phase by disabling it
    * But I worry it in fact affects **all** the existing measures, including our daily reports
  3. Without a customized phase, Raptor will only execute Marionette actions **after** the logging finished (that's why it's named as `afterEach`), so it is impossible to log marks **while** Marionette actions are performing
  4. Raptor in fact allow to specify the target phase via file path, but it's not an documented API or option. So I need to hack the patch to make it runs correctly, including:
    1. The way it was implemented to require an external phase (as module) will screw the loading paths of its dependencies. I need to wrap the official `require` to workaround that
    2. It's necessary to fetch the path of customized phase via an environment variable, since there is no such option

#### Results

  1. The first usable workflow for testing performance on app microbehaviors in Gaia, and **there is no need to patch Raptor**
     1. `RAPTOR_TRANSFORM_RULES=/Users/snowmantw/Projects/gaia/apps/system/test/raptor make raptor-transformer`
     2. `RUNNING_PHASE=<where the phase is> raptor test /Users/snowmantw/Projects/gaia/apps/system/test/raptor/lockscreen-lock2unlock-test.js`
  2. Immediately captured one performance issue of screen lock (it costs 500ms from lock to unlock), although a double check is necessary to see if my testing method is reliable
     * Bug 1222901 - [LockScreen] From |LockScreen#lock| to |LockScreenWindowManager#respondUnlock|, Z3C takes more than 500ms to complete the action

#### Future work:
  1. Find someone can cowork with me to verify if the method is correct and accurate
  2. Start a discussion about how to measure what kinds of microbehaviors in Gaia
  3. Implement more tests to improve the tool, and start to raise the test coverage
  4. Discuss with performance and Gaia team to see how to use this on Gaia components

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
