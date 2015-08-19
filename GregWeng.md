## 08/10 ~ 08/14

LockScreen: fix interrmitent errors on Mulet

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
