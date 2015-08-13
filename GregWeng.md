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
