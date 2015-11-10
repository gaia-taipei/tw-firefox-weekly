## 10/26 ~ 11/06
[TV System]
* [Bug 1211400](http://bugzil.la/1211400) - [TV][2.5] Preview an app on Marketplace
 * Completed back key feature - ability to back to previous page in preview window and dismiss preview window when history is empty.
 * Survey and understand appwindow life cycle in order to figure out where is the best place to kill preview app when it's unused by users.

[Build]
* [Bug 1215437](http://bugzil.la/1215437) - Upgrade b2g_sdk for supporting new gecko features
 * Try to upgrade gaia's b2g_sdk to 44.0a1 but it was backed out due to CI server issues and waiting for bug 1204800.

[Other]
* Attend to web summit 2015 in Dublin 11/1 - 11/7
* Clean up review and needinfo queues
 * [Bug 1220528](http://bugzil.la/1220528) - Configure the default build flag FIREFOX_SYNC to ENABLE in v2.5 branch, TV only
 * [Bug 1219302](http://bugzil.la/1219302) - Support removing files using the preprocessor when a flag is enabled
 * [Bug 1178242](http://bugzil.la/1178242) - Notes app can't sign in to Evernote

## 2015 Q4 Goals
1. Support TV 2.5 feature - Provide an ability to preview an app on Marketplace [[TV][2.5] Preview an app on Marketplace](https://bugzilla.mozilla.org/show_bug.cgi?id=1211400), as measured by implementation (completeness and stability of the feature)
2. To lift the restrictions for gaia developers to use third-party NPM packages, we'll continue the plan of [refactoring build system run-time to node.js](https://wiki.mozilla.org/Gaia/Build/RefactoringToNodejs), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
3. CI machines are able to run / switch multi-version node.js in order to support new gaia build (node.js v4.x) and testing framework (node.js v0.10.x), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
4. Investigate new Gaia build 2.0 - confidant with Gareth, as measured by planning progress.
5. Fix bugs of build system, as measured by blocker burn down and days of blocker turnarounds.

## 2015 Q3 Delivered
1. Investigated new configure of Gaia build 2.0 - confidant
2. Surveyed and do experiment for new Gaia build 2.0 - gaia-playground
3. Fixed bugs of build system
4. Fixed bugs of settings app and system app
5. Supported Academy NCU 2015 Program - Introduced Git, Github, Bugzilla, WebIDE and DevTools
