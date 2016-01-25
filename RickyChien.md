## 01/11 ~ 01/22
[TV System]
* [Landed] [Bug 1237541](http://bugzil.la/1237541) - [TV][2.5] Preview window back key also trigger on parent app window
* [Landed] [Bug 1239907](http://bugzil.la/1239907) - [TV][2.5] Improve and make l10n strings consistent for preview experience
* [Landed] [Bug 1239914](http://bugzil.la/1239914) - [TV][2.5] Fallback to old system banner

[Build System] [RefactoringToNodejs#Milestone_1](https://wiki.mozilla.org/Gaia/Build/RefactoringToNodejs#Milestone_1)
* [Landed] [Bug 1207073](http://bugzil.la/1207073) - RUN_ON_NODE=1 make is broken
* [Landed] [Bug 1131519](http://bugzil.la/1131519) - Running push-to-device.js on node.js
* [Landed] [Bug 1131524](http://bugzil.la/1131524) - Running shared-utils.js on node.js
* [Landed] [Bug 1131505](http://bugzil.la/1131505) - Running homescreen-manager.js on node.js
* [Landed] [Bug 1131522](http://bugzil.la/1131522) - Running rebuild.js on node.js
* [Landed] [Bug 955998](http://bugzil.la/955998) - Running webapp-optimize.js on node.js
* [Landed] [Bug 1131521](http://bugzil.la/1131521) - Running r-wrapper.js on node.js
* [r?] [Bug 1131516](http://bugzil.la/1131516) - Running post-app.js on node.js
 
[Other]
* Mentor Scott Wu to refactor [Bug 1131497](http://bugzil.la/1131497) - Running build-test.js on node.js
* [Review History](https://bugzilla.mozilla.org/page.cgi?id=review_history.html&requestee=rchien%40mozilla.com)

## 2015 Q4 Goals
1. Support TV 2.5 feature - Provide an ability to preview an app on Marketplace [[TV][2.5] Preview an app on Marketplace](https://bugzilla.mozilla.org/show_bug.cgi?id=1211400), as measured by implementation (completeness and stability of the feature)
2. To lift the restrictions for gaia developers to use third-party NPM packages, we'll continue and deliver detailed plan for [refactoring build system run-time to node.js](https://wiki.mozilla.org/Gaia/Build/RefactoringToNodejs), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
3. CI machines are able to run / switch multi-version node.js in order to support new gaia build (node.js v4.x) and testing framework (node.js v0.10.x), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
4. Investigate new Gaia build 2.0 - confidant with Gareth, as measured by planning progress.
5. Fix bugs of build system, as measured by blocker burn down and days of blocker turnarounds.

## 2015 Q3 Delivered
1. Investigated new configure of Gaia build 2.0 - confidant
2. Surveyed and do experiment for new Gaia build 2.0 - gaia-playground
3. Fixed bugs of build system
4. Fixed bugs of settings app and system app
5. Supported Academy NCU 2015 Program - Introduced Git, Github, Bugzilla, WebIDE and DevTools
